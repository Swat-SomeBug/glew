# glew

build2 packaged glew library.
This package uses [Perlmint/glew](https://github.com/Perlmint/glew-cmake.git) as upstream as include files and sources are pre-generated. Package version tracks upstream releases.

The package introduces two config variables:
* `config.glew.glewinfoinstall` (default `false`): that enables one to install the glewinfo utility that is generated as a package test. The utility useful to understand system capabilities and the generated report is recommend when filing bugs with GLEW.
* `config.glew.regal` (default `false`): Use Regal Library
* `config.glew.osmesa` (default `false`): Use OSMesa Library



