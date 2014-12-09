## v1.2.0.1:
* Hot fix: There are cookbooks that call node.save during a recipe so
in order to preserve all the node attributes for after the save, we temporarily
save them to to restore them.

## v1.2.0:
* Fixed library class namespacing issue to work with chef 11.14 +

## v1.1.0:

* [COOK-1886] - add `ohai_time` as a default whitelisted attribute

## v1.0.0:

* Initial release
