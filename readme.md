TinyMCE - Spellchecker for PHP - (B42 Digital Fork)
=================================================

This is the PHP backend for the TinyMCE 4.0 spellchecker plugin. It enables you to use different PHP implementations such as Enchant, Google or PSpell.
Currently only Pspell has been tested by B42 Digital and it requires that Pspell is enabled in PHP.


How to Install
--------------

 - Copy the 'includes' directory and the 'spellchecker.php' file into tinymce/plugins/spellchecker/
 - Ensure the 'engine' parameter in $tinymceSpellCheckerConfig in 'spellchecker.php' is set to 'pspell'
 - Add the 'spellchecker' plugin and button to your tinymce config.
 - Add the path to 'spellchecker.php' to your tinymce config under the key 'spellchecker_rpc_url' e.g.
```
spellchecker_rpc_url: '/js/lib/tinymce/plugins/spellchecker/spellchecker.php',
```



Original Readme Below
=====================

How to build TinyMCE Spellchecker for PHP
------------------------------------------

Install Node.JS and Jake globally using npm. Then just run jake to build a release package.

```JavaScript
npm jake -g
npm install
jake
```

Contributing to the TinyMCE Spellchecker for PHP project
---------------------------------------------------------
You can read more about how to contribute to this project at [http://tinymce.moxiecode.com/contributing](http://tinymce.moxiecode.com/contributing)
