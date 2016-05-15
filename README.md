# DNA Matcher with AJAX in Drupal - April 22, 2016

## Description

There are two main functionalities of this Drupal App:

1. Rendering AJAX calls.

Click on any of the article links found on the left side of the page in the sidebar. If you have JavaScript enabled in your browser, the server will send you the article via an AJAX request without the need to refresh the page. If you disable JavaScript, you can still view the article, but you will be directed to another page.

2. DNA Matcher

DNA can be broken down into their building blocks called nucleotides, which consist of a nitrogenous base, a pentose and a phosphate group. There are 4 nitrogenous bases found in DNA: Ctyosine, Guanine, Adenine, Thymine. Each of these can only be paired up with its 'partner' base - Cytosine matches with Guanine and Adenine matches with Thymine - forming what is called a base pair. The sequence of these bases are often represented by their first letter. For example, Cytosine and Guanine would be shown as AG, and their matching pairs found on the other strand of the double helix would be TC.

The DNA Matcher on this app allows you to type in any combination of nitrogenous bases found on one strand of DNA to match it with its complimentary strand.

Example:

* Input: AGCT

* Output: TCGA

Keep in mind that you must enter one of these four in order to return a result. For those RNA fans out there, we are working on a custom module that calculates the complimentary strand of RNA in which Uracil replaces Thymine.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [MAMP](http://www.mamp.com)

## Installation

* Git clone `https://github.com/jwuerch/Drupal-CR-4.git`.
* Change into the new directory.
* Start up MAMP and point servers to main directory.
* Go to localhost:8888/phpmyadmin in browser and import `drupal_cr4.sql.zip`. The           DB can be found in Drupal-CR-1/sites/DB-Backup.
* Create DB username `admin20` with password `admin20`.
* Go to localhost:8888 to view Drupal project.
* Log-in as administrator with username `admin20` and password `admin20`.

## Databases Used
* `drupal_cr4`

## Usernames and Passwords
* DB: `admin20:admin20`
* Drupal site maintenance account: `admin20:admin20`

## Running / Development

* Visit your app at [http://localhost:8888](http://localhost:8888).

### Deploying

All you need to deploy is to visit localhost:8888. The app is currently not hosted.

##License

This software is licensed under the MIT license.
Copyright (c) 2016 _**Jason Wuerch**_.
