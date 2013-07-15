nagios-check_tftp
=================

Nagios plugin to check connections to a TFTP server


## Usage

    check_tftp:  Nagios plugin to check a tftp server

    Usage:
      check_tftp [<flags>] -H host [-p port] [-v]
      check_tftp --help
      check_tftp --man
      check_tftp --version

    Options:
      --hostname    The name of the host running the tftp server.
      --port        The port on which the tftp service should be running.
      --verbose|-v  Show details of progress (give more than once for more info).
      --help        Show this usage text.
      --man         Show the comprehensive documentation.
      --version     Show the version (0.1.2).


## Requirements

This plugin needs a tftp binary that accepts commands on standard input.


## To Do

Move from utils.pm to Nagios::Plugin.  Patches welcome :-)


## License

This code is licensed under the Perl Artistic License, version 2.0.  For
more information, please see the file Artistic_2.0, which was included with
this distribution, or http://opensource.org/licenses/artistic-license-2.0.php
