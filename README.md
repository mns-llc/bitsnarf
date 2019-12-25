bitsnarf
===========

[![Build Status](https://travis-ci.org/mns-llc/bitsnarf.svg?branch=master)](https://travis-ci.org/mns-llc/bitsnarf)

A fork of [CommonRegex](https://github.com/madisonmay/CommonRegex) by [Madison May](https://github.com/madisonmay) which finds useful information in English/US strings using regular expressions. bitsnarf has an expanded set of regexes to work with, a more structured naming convention, and *extremely* limited support for common international formats.

Notably, this repository adds a number of low-confidence regular expressions to try to sniff out Personally Identifiable Information (PII) that would be wasteful in CommonRegex (ex. [very approximate name detection](https://stackoverflow.com/questions/7653942/find-names-with-regular-expression)).

Installation
-------
Install via setup.py

    python setup.py install

Supported Methods/Attributes
-----------------------------

  - `obj.dates`, `obj.dates()`
  - `obj.times`, `obj.times()`
  - `obj.phones`, `obj.phones()`
  - `obj.phones_with_exts`, `obj.phones_with_exts()`
  - `obj.links`, `obj.links()`
  - `obj.emails`, `obj.emails()`
  - `obj.ips`, `obj.ips()`
  - `obj.ipv6s`, `obj.ipv6s()`
  - `obj.prices`, `obj.prices()`
  - `obj.hex_colors`, `obj.hex_colors()`
  - `obj.credit_cards`, `obj.credit_cards()`
  - `obj.btc_addresses`, `obj.btc_addresses()`
  - `obj.street_addresses`, `obj.street_addresses()`
  - `obj.zip_codes`, `obj.zip_codes()`
  - `obj.po_boxes`, `obj.po_boxes()`
  - `obj.ssn_number`, `obj.ssn_number()`
