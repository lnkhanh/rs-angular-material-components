# Angular Material File Input for @angular/material 7.x, 8.x, 9.x

[![Build Status](https://travis-ci.com/h2qutc/angular-material-components.svg?branch=master)](https://travis-ci.com/h2qutc/angular-material-components)
[![codecov](https://codecov.io/gh/h2qutc/angular-material-components/branch/master/graph/badge.svg)](https://codecov.io/gh/h2qutc/angular-material-components)
[![License](https://img.shields.io/npm/l/angular-material-components.svg)](https://www.npmjs.com/package/angular-material-components)
[![npm version](https://badge.fury.io/js/%40angular-material-components%2Ffile-input.svg)](https://www.npmjs.com/package/@angular-material-components/file-input)

## Description

A Angular Material File Input.

[![button](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=SAAY32BP5KPPC&source=url)

## DEMO

@see [LIVE DEMO](https://h2qutc.github.io/angular-material-components/)

## Getting started
```
npm install --save  @angular-material-components/file-input
```

## Setup

```
import { NgxMatFileInputModule } from '@angular-material-components/file-input';

@NgModule({
   ...
   imports: [
        ...
        NgxMatFileInputModule
   ]
   ...
})
export class AppModule { }
```

## Using the component

### File Input (ngx-mat-file-input)

```
<mat-form-field>
    <ngx-mat-file-input [formControl]="fileControl" [multiple]="multiple" [accept]="accept">
    </ngx-mat-file-input>
  </mat-form-field>
```

#### List of @Input

| @Input        	| Type     	| Default value 	| Description                                                          	|
|---------------	|----------	|---------------	|----------------------------------------------------------------------	|
| **multiple**      	| boolean  	| false          	| If true, the file input allows the user to select more than one file.                	|
| **accept**    	   | string   | false           | Limiting accepted file types (For example: accept="image/png, image/jpeg" or accept=".png, .jpg, .jpeg" — Accept PNG or JPEG files.) 	|

## Theming
- @see @angular/material [Using a pre-built theme](https://material.angular.io/guide/theming#using-a-pre-built-theme)
- Add the Material Design icon font to your index.html
```
<link href="https://fonts.googleapis.com/icon?family=Material+Icons&display=block" rel="stylesheet">
```

## License
MIT