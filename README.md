Description
===========

*THIS COOKBOOK HAS BEEN DEPRECATED.*  Please use the `java` cookbook with the proper `install_flavor` attribute set.

The default recipe in this cookbook simply points to the `java::default` recipe with the `node["java"]["install_flavor"]` attribute set to `sun`

Requirements
============

Platform: Ubuntu, Debian.

Usage
=====

Simply include the recipe where you want Sun Java installed.

License and Author
==================

Copyright 2008-2010, Opscode, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
