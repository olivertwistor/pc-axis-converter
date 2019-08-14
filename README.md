# PC-Axis Converter
This is a Java program that converts database or CSV input to PC-Axis output.

The PC-Axis file format (.px) is standard for showing statistical databases. 
You can read more about the file format and various software used to view and 
work with the files on [Statistics Sweden][4].

## Table of contents
* [Who is this for?](#who-is-this-for)
* [Prerequisites](#prerequisites)
* [Installation instructions](#installation-instructions)
* [Usage](#usage)
* [Licensing](#licensing)
* [How to contribute](#how-to-contribute)
* [Versioning](#versioning)

## Who is this for?
One of my former employers was a governmental agency tasked with, among other 
things, to collect statistics about the private sector. Since we chose to work 
with PC-Axis, the standard in the field, we ran into the problem that the file 
format is not entirely easy to work with, especially if you're used to 
relational databases such as MySQL, PostgreSQL or MS SQL Server. PC-Axis is a 
file based database.

There are many tools available for converting *from* the PC-Axis format to 
various formats, but I haven't found any other tool that converts *to* the 
PC-Axis format. There is of course [PX-Edit][11], but I have found it rather 
difficult to work with.

The aim of this project is to provide an easy to use tool for converting to the 
PC-Axis format.

## Prerequisites
To run this program you will need the following:

* [Java SE 1.7 or later][12]

## Installation instructions
This section will be added once the first version has been released.

## Usage
This section will be added once the first version has been released.

## Licensing
This application is licensed under the [MIT License][2]. For detailed license
terms, please read [LICENSE][8].

## How to contribute
Thank you for wanting to contribute to this project. Open source is all about
community. Go and read the document [CONTRIBUTING.md][9] for more information
on with what you can contribute and how to go about it.

## Versioning
This project uses [Semantic Versioning 2.0.0][3] for version numbering. To see
what's changed between versions, please read [CHANGELOG.md][10]. That file also
has links to the download section of each release.


[2]: https://opensource.org/licenses/MIT
[3]: https://semver.org/
[4]: https://www.scb.se/en/services/statistical-programs-for-px-files/ "Statistic Sweden about PC-Axis"
[8]: LICENSE
[9]: CONTRIBUTING.md
[10]: CHANGELOG.md
[11]: http://www.stat.fi/tup/tilastotietokannat/px-tuoteperhe_en.html
[12]: https://www.oracle.com/technetwork/java/javase/downloads/index.html
