laravel-netbeans-autocompletion
===============================

Task file of Laravel that run via artisan to generate helper file for autocompletion in Netbeans. <a href="example_ide_helper.php">Example code that I generated</a>.

If you see problem, please open issue. Thanks!

How to use?
===========

1. Put **ccg.php** to **/application/tasks/** in your laravel projects.
2. open your dos or shell and type this command at your root of laravel project **php artisan ccg:save ide_helper.php**
You will get **ide_helper.php** for Netbeans use in autocompletion.

Another things that you must do
==============================

1. In Netbeans click **Tools** -> **Options**.
2. Click **Editor** -> **Code Completion** tab.
3. Click dropdown change **All languages** to **PHP**.
4. Checkbox **Also Non-Static Methods after "::"**.
5. Click **OK** and reopen Netbeans.

Credit and Thanks!
==================

- Inspired and base code : http://forums.laravel.io/viewtopic.php?id=742&p=2
- Guide code (for me) : https://github.com/danielboendergaard/laravel-helpers/blob/master/ide_helper.php
