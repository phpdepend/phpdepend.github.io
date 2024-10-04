A toolset to visualize dependencies within a project.

This is **not** a replacement for [pdepend](https://pdepend.org)!

## Usage

The toolset contains two different tools:

1. The [callmap plugin for PHPStan](https://github.com/phpdepend/callmap).
   This plugin can be used to generate a callmap.json file that contains
   informations about
   which method is called from which method.
2. The [PHPDepend CLI](https://github.com/phpdepend/phpdepend) which allows to
   generate different
   visualizations from this callmap.json file.
