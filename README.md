Ubuntu Keyboard
===============

Ubuntu Keyboard is the official QML and C++ based keyboard plugin for Ubuntu 
Touch. We follow an open source model where the code is available to anyone 
to branch and hack on.

Updating presage language models
================================

If the source material used for **presage** prediction models is updated, the 
databases can be regenerated by running `make lang_db_$lc` within the plugin's
**src** directory (where `$lc` is the language code for the updated language, 
e.g. `make lang_db_en` for English)


Building with crossbuilder
==========================
The easiest way to build this is using crossbuilder by simply running:

```
crossbuilder
```

See [crossbuilder on github](https://github.com/ubports/crossbuilder) for 
details.

Useful Links
============
Here are some useful links with regards to the keyboard plugin development.

* [UBports](https://ubports.com/)
* [building with crossbuilder](http://docs.ubports.com/en/latest/systemdev/testing-locally.html#cross-building-with-crossbuilder)
* [crossbuilder on github](https://github.com/ubports/crossbuilder)
