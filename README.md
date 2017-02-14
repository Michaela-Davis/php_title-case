# _Title Case Generator_

#### _A webpage that will take a user's string of words and convert them to title case, 14 February 2017_

#### By _**Michaela Davis**_


## Description

_A webpage that will take a user's string of words and convert them to title case- capitalizing letters like we'd find in a book title._

## Setup/Installation Requirements

* In terminal run the following commands to setup the database:

1. _Fork and clone this repository from_ [gitHub](https://github.com/michaela-davis/php_title-case.git).
2. Navigate to the root directory of the project in which ever CLI shell you are using and run the command: `composer install`.
3. Create a local server in the /web directory within the project folder using the command: `php -S localhost:8000` (assuming you are using a mac).
4. Open the directory http://localhost:8000/ in any standard web browser.

## Specifications

|    *Behavior*   |    *Input*    |     *Output*    |
|-----------------|---------------|-----------------|
| It capitalizes the first letter of a single word  | "beowulf" | “Beowulf"|
| It capitalizes the first letter of a multiple word string  | "beowulf begins" | “Beowulf Begins" |
| It does not capitalize designated words (prepositions, conjunctions, etc,)| "beowulf from brighton beach" | "Beowulf from Brighton Beach|
| It capitalizes designated words if they are the first word | “from beowulf to the hulk" | “From Beowulf to the Hulk" |
| It handles non-letter characters | “57 beowulf alternative endings!!!" | “57 Beowulf Alternative Endings!!!" |
| It manages all uppercase entries | “BEOWULF ON THE ROCKS" | “Beowulf on the Rocks" |
| It manages mixed case entries | “BeoWulf aNd mE" | “Beowulf and Me" |

## Known Bugs

_None so far._

## Support and contact details

_Please contact michaela.delight@gmail.com with concerns or comments._

## Technologies Used

* _HTML_
* _CSS_
* _PHP_
* _PHPUnit_
* _Composer_
* _Silex_
* _Twig_

### License

*MIT license*

Copyright (c) 2017 **_Michaela Davis_**
