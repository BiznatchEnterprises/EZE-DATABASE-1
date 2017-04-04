# EZE-DATABASE
Version 1.0 - Dynamic database class written in PHP (OOP)

(C) 2002 - Biznatch Enterprises (Biznaturally.ca)

Semi-stable release (Experimental). Tested on: PHP 4, PHP 5, PHP 7

Version 2.0 is currently in development


"Raw Data" is stored in a similar way as a Hard Drive. Database files (Drive IDs) contains Partitions accociated with Sectors of individual data. These Data Sectors within Partitions are stored in a flat-file with unique identifiers and can be individually encrypted with unique keys or "linked" by hashing or other means... To sectors contained in partitions stored in seperate database files.

Multiple databases can be loaded concurrently as unique "objects" within the class, accessing their methods (functions) individually.

Once parsed from the database: All data can be read by a PHP script by using a double array.
$DATABASE[partition][sector]


This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License.

