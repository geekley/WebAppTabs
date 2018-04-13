This is a fork of the original extension from Mossop that just fixes the icon problem.  
It gets the icon URLs from google automatically, but also allows the user to set a custom URL.  
The XPI that can be installed into Thunderbird is in the releases tab.

The original project is not mantained anymore. Part of the original README follows below.

---

WebApp Tabs
===========

This is an extension for Thunderbird which allows you to view webapps in
Thunderbird's tabs.

Project Goals
-------------

There are many extensions for viewing webpages in Thunderbird. This isn't what
I think Thunderbird is for, webpages can be viewed in Firefox or whatever
browser you prefer. Thunderbird is my communications centre and I use it to
display communications related webapps like Google+, Google Reader,
Google Groups, etc. and I want to be able to use those easily, opening links in
the default browser where relevant.

The main goals are:

* Allow the user to configure a set of available webapps
* Provide a way for the user to open each webapp in a tab
* Any attempt to open a configured webapp (e.g. from a link in an email or
  anywhere else) should open it in the existing tab for the webapp if one exists
  or a new tab for the webapp in Thunderbird
* Any links clicked in the webapp that are to other sites should open in the
  default browser
* The webapp should behave as well in Thunderbird as it would if opened in
  Firefox

License
------------

As always feel free to fork. This project is MPL/GPL/LGPL tri-licensed.
