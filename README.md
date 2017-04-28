# Shift Cipher by Koji Nakagawa

#### Drupal 2nd Week Independent Project for Epicodus, 4.28.2017

## Description
* This website is the second independent project for Epicodus "Drupal" class.
* This website offers shift-cipher module.

## Specifications

|Behavior|Input|Output|
|--------|-----|------|
| shift the character based on input value | value = 3, direction = right, phrase = 'hello' | 'knoor' |
| shift the character order base on direction | value = 1, direction = left, phrase = 'hi there!' | 'gh sgdqd!' |
| cycleback to the beginning if the value was over the bounds of the alphabet | value = 53, direction = left, phrase = 'abc!' | 'zab!' |

## Prerequisites
You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [MAMP](https://www.mamp.info/en/)


## Installation
* `git clone this repository`
* `launch MAMP program`
* `set the Apache Port to 8888 (MAMP)`
* `set the MySQL Port to 8889 (MAMP)`
* `set Bookstore folder as your Document Root (MAMP)`
* `open the phpMyAdmin and import the database backup file (cipher/sites/db-backup)`
* `go to privilege and create user (see Sample Database section)`
* `after imported successfully, go to localhost:8888`

For additional information, please look at [here](https://www.learnhowtoprogram.com/drupal/site-building-with-the-drupal-interface/drupal-local-development-workflow)

## Sample Database
* Database name: cipher
* Database username: cipher
* Database password: cipher
* Site maintenance username: cipher
* Site maintenance password: cipher

## Technologies Used
  * Drupal core 7.5.4
  * HTML/CSS
  * PHP

## License
  _Copyright (c) 2017 **Koji Nakagawa**_

  _Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:_

  _The above copyright notice and this permission notice shall be included in all
  copies or substantial portions of the Software._

  _THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
  SOFTWARE._
