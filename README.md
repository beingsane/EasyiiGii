# Easyii Gii
Yii2 Gii (generator) with Relation person to PostgreSQL

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```bash
$ composer require thtmorais/easyiigii:dev-master
```

or add

```
"thtmorais/easyiigii": "dev-master",
```

to the `require` section of your `composer.json` file.


Then you must add this code at your config\main.php.

```php
'modules' => [
      'gridview' => [
          'class' => '\kartik\grid\Module',
      ],
      'datecontrol' => [
          'class' => '\kartik\datecontrol\Module',
      ],
  ],
```
See gridview settings on http://demos.krajee.com/grid#module

See datecontrol settings on http://demos.krajee.com/datecontrol#module

## Usage :
Go to your gii tools, and notice the new EasYii Gii Generator for models & CRUD


#Features
## Model :
1. Generate optimistic lock
2. Generate Timestamp Behaviors
3. Generate Blameable Behavior
4. Generate UUID Behavior
5. Generate validations for e-mail, CPF/CNPJ

## CRUD :
1. Generate all CRUD with wildcard (*) of table
2. Generate related input output
3. Specify your name/label attribute for foreign keys
4. Set your column to hidden
5. Specify your skipped columns
6. Specify your skipped relations
7. Set pluralize or not
8. PDF Printable view
9. Expandable / collapsible row at index grid view for related data
10. Views with or without TabularForms

## Migration Generator :
1. Generate migration from your database structure (based on : https://github.com/deesoft/yii2-gii)

# To Do
1. One-page-CRUD template
2. Implement generator for Soft Delete Behavior (https://github.com/yii2tech/ar-softdelete)

I'm open for any improvement


# Screenshot

## Model Generator

![enhanced gii - model](https://cloud.githubusercontent.com/assets/5844149/13099130/db81fc46-d561-11e5-85ca-a9f3c38e68d8.PNG)

## CRUD Generator

![enhanced gii - crud](https://cloud.githubusercontent.com/assets/5844149/16199521/10efff98-3734-11e6-8bab-2fc6e85c0b38.png)

## Index 
### Grid View
![enhanced gii - index grid](https://cloud.githubusercontent.com/assets/5844149/16200077/0f478092-3736-11e6-9c85-873ea463816d.png)
### List View
![enhanced gii - index list](https://cloud.githubusercontent.com/assets/5844149/16200165/5911c818-3736-11e6-9f85-38b8c0dbc65d.png)

## View
![enhanced gii - view](https://cloud.githubusercontent.com/assets/5844149/16200282/ddf2f1b0-3736-11e6-8792-a541a5571adb.png)

## Form
![enhanced gii - create](https://cloud.githubusercontent.com/assets/5844149/16201809/39ce715c-373d-11e6-86cd-bf80b37fafd6.png)

![enhanced gii - update](https://cloud.githubusercontent.com/assets/5844149/16201857/61b09bd2-373d-11e6-9a46-bb6c82bb183f.png)

## Nested / Tree
![enhanced gii - nested](https://cloud.githubusercontent.com/assets/5844149/16476447/bdae9a1c-3eb1-11e6-8dc3-a20a06a3148b.png)

# Migration Generator
![migration form](https://cloud.githubusercontent.com/assets/5844149/15350030/08ab4d58-1d01-11e6-87b7-4dd621a5bef6.JPG)


# Thanks To
1. Jiwanndaru (jiwanndaru@gmail.com) for creating the tradition
2. kartik-v (https://github.com/kartik-v) for most of widgets
3. schmunk42 (https://github.com/schmunk42) for bootstrap & model base & extension
4. mdmunir (https://github.com/mdmunir) for JsBlock & Migration Generator (from https://github.com/deesoft/yii2-gii)
5. mootensai(https://github.com/mootensai) for yii2-enhanced-gii(https://github.com/mootensai/yii2-enhanced-gii)
