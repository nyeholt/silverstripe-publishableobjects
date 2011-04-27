# SilverStripe Publishable Objects Module

Maintainer Contact
-----------------------------------------------
Marcus Nyeholt

<marcus (at) silverstripe (dot) com (dot) au>

Requirements
-----------------------------------------------
SilverStripe 2.4.x

Documentation
-----------------------------------------------

This module provides a simple re-implementation of key parts of SiteTree as 
an extension so normal dataobjects can be "publishable". This effectively 
applies the Versioned extension to the data object type, and implements some
methods for doPublish type functionality. 

Quick Usage Overview
-----------------------------------------------

`Object::add_extension('YourDataObjectType', 'PublishableObject');`


API
-----------------------------------------------

Troubleshooting
-----------------------------------------------

