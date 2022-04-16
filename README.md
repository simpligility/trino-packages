# trino-packages

A repository for the creation of binary packages of Trino. Currently contains
the following:

* RPM

Future potential additions:

* RPM suitable for different distros
* Other Linux package formats
* Various docker container images:
  * Minimal Trino base to use for custom containers with limited plugins
  * Lakehouse Trino
  * Generic example how to create a container off the base with custom
    selection of plugins
  * Container with different base Linux distro
  * Trino CLI only container
* Homebrew or other special packages
* Example for custom tarball with startup and config scripts included
* Example for custom tarball with reduced plugin selection
