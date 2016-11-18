True/False WIRIS question type
[![Build Status](https://travis-ci.org/wiris/moodle-qtype_truefalsewiris.svg?branch=master)](https://travis-ci.org/wiris/moodle-qtype_truefalsewiris)

The True/False WIRIS question type extends Moodle True/False question type adding mathematical functionalities to it.

All mathematical items are generated in a single calculation section and they can be referenced from anywhere in the content, question wording, answer, feedback for the student, etc.

On the side of the student, he will be able to introduce his answers by using a WYSIWYG formula editor and, if the teacher so specifies, they will have access to a WIRIS cas session to make some calculations. The answer syntax check will prevent the students from unnecessary errors and misspellings.

## Install instructions

To install it using git, type this command in the root of your Moodle install:
```
git clone https://github.com/wiris/moodle-qtype_truefalsewiris.git question/type/truefalsewiris
```
Then add /question/type/truefalsewiris to your git ignore.

Alternatively, download the zip from <https://github.com/wiris/moodle-qtype_truefalsewiris/archive/master.zip> it into the question/type folder, and then rename the new folder to "truefalsewiris".

## License

WIRIS True/False question type is Licensed under the [GNU General Public, License Version 3](https://www.gnu.org/licenses/gpl-3.0.en.html).