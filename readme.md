# D7 Custom Module Template: Add JS to a Form

## Contact

### Current maintainers:

* Vid Rowan ([_vid](http://drupal.org/user/631512/))

## Drupal Version

* Drupal 7

## Purpose
The d7_custom_mod_add_js_to_form module is a simple custom module that provides a js file for a specific form.

## Scope: What this module does

* Uses hook_form_alter to act on a specific form 
* Uses hook_help to provide information about the module to the site admin
* Uses drupal_add_js to add a js file to the specified form
* Uses drupal_set_message to push some debugging messages to the screen. These should be commented out on a live site
* Includes some sample code for passing PHP vars to JS and using those vars in the js file
* Includes some console logging in the js file

## Out of Scope: What this module does not do

* This module does not declare the js file in the .info file. We do not want to load this js file on every page
* This module does not have an admin settings page

## Requirements

* None

## Installation

* Install module as usual, see [Installing contributed modules](http://drupal.org/node/70151
  for further information.

## Usage

### In short:
* Enable the module

### To make this module your own: 
* Rename the module directory to a new name
* Rename all the files to match the new dir. name
* Replace all references to "d7_custom_mod_add_js_to_form" in the files to your new name. 
* Add your custom code
* Deploy

## Git Repo Notes:
* The master branch can only be written to by Vid. 
* Feel free to create new branches and push them up. The dev branch can be written to by anyone.
