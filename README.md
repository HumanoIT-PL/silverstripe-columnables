﻿## Overview

A column-layout plugin for TinyMce used in Silverstripe's HTMLEditorField

## Installation ##

`composer require cwchong/silverstripe-columnables ^1`

Run `dev/build` to activate the plugin on your HTMLEditorFields

Inject the column stylesheet to your pages (or experiment with your own):

`Requirements::css('cwchong/silverstripe-columnables: client/dist/css/columns.css');`

Add the css class "typography" to the element containing your content:

`<div class="typography">$Content</div>`

## Bugtracker ##

Bugs are tracked on github.com (https://github.com/cwchong/silverstripe-columnables/issues)

## Links ##

 * [Developer](https://movingmouse.com)
 
