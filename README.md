Seamate is an add-on for Seahub, the web interface of the file syncing and sharing software Seafile, that allows the easy modification of Seahub‘s look. 

It integrates in the global settings of Seahub and requires no coding knowledge whatsoever. Modifying Seahub to meet your personal / corporate standards is no more than changing a few field values in the familiar Seahub settings.

## Technical implementation



Seahub employs more than xxx  CSS classes. With Seamate, some 35 can be modified right within Seahub. Why "only" this small fraction? Things get unwieldy quickly! We believe -- till proven wrong -- that the set of configurable parameters meets the demand of the large majority of Seamate users. For all other uses, more classes would mean more headache. Additionally, all those that wish to take the customization even further can still import a separate custom CSS file or make use of the custom CSS in the Seahub settings.

## Use
Seamate expands the Branding block in the settings menu in Seahub's admin panel.

Seamate Seahub's five central UI elements (login, top bar, navigation sidebar, main, and popups).  Additionally, global settings can be set. Whenever possible, colorpickers or dropdown lists are provided for ease of use.

In Seamate's *global settings*, four CSS classes can be manipulated (the class' name in brackets):
* Font                          [GLOBAL\_FONT]
* Border color                  [GLOBAL\_BORDER\_COLOR]
* Border radius                 [GLOBAL\_BORDER\_RADIUS]
* Border thickness              [GLOBAL\_BORDER\_THICKNESS]

For each of Seahub's *five central UI elements*, the following six CSS classes can be modified using colorpickers (the class' name in brackets):
* Background color              [...\_BACKGROUND]
* Text color default            [...\_TEXT]
* Text color link               [...\_LINK]
* Text color hover              [...\_LINK\_HOVER]
* Icon and button color         [...\_ICBU]
* Icon and button color hover   |...\_ICBU_HOVER]

Additionally, the following two elements can be modified in the main element (the class' name in brackets):
* Border color                  [MAIN_TABLE_BORDER_COLOR]
* Border thickness              [MAIN_TABLE_BORDER_THICKNESS]

The custom CSS field in the Branding box can be used to manipulate any other CSS classes not addressed by Seamate. Any specification must be made in [common CSS syntax](https://www.w3schools.com/css/css_syntax.asp). 

## Installation


## Change log
### Seamate 1.0 (DATE)
Initial release of Seamate


## Compatability list
Seamate can be used with Seafile's community as well as professional server. 

As a rule, a Seamate version that works with the community server also works nicely with the professional server and vice versa. Since the CSS classes for the two servers partially vary, there may be exceptions. For more details, see compatability tables below which shows known working combinations.



### Seafile Server Community Edition 

| Seafile 6.3       | Seafile 6.2       | Seafile 6.1         | Seafile 5.x         |
| ----              | -----             | ----                | ---                 |
| Seamate 1.0       | Seamate 1.0       | Seamate 1.0         | untested            |      

### Seafile Server Professional Edition

| Seafile 6.3       | Seafile 6.2       | Seafile 6.1         | Seafile 5.x         |
| ----              | -----             | ----                | ---                 |
| Seamate 1.0       | Seamate 1.0       | Seamate 1.0         | untested            |      

## Outlook
