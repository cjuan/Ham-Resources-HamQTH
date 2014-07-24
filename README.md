Ham-Resources-HamQTH version 0.06
=================================

This is the README file for Ham::Resources::HamQTH, an object oriented front end for the HAMQTH.com Amateur Radio Callsign free database.

After installation, please consult the tutorial for how to use it. 
'perldoc Ham::Resources::HamQTH' should work on most systems.


INSTALLATION

To install this module type the following:

   perl Makefile.PL
   make
   make test
   make install

DEPENDENCIES

This module requires these other modules and libraries:

  - LWP::UserAgent
  - XML::LibXML::Reader
  - Internet connection
  - A valid account for use the HamQTH.com database service. Register is free.

ADDITIONAL TEST

You can found the file 'Ham-Resources-HamQTH-test.pl' on the 't' folder for test the module, if you have a valid HamQTH.com account.

COPYRIGHT AND LICENCE

This module is free software; you can redistribute it and/or
modify it under the terms of the Artistic License 2.0. For
details, see the full text of the license in the file LICENSE.

This program is distributed in the hope that it will be
useful, but it is provided "as is" and without any express
or implied warranties. For details, see the full text of
the license in the file LICENSE.

Copyright (C) 2012-2014 by Carlos Juan Diaz (CJUAN) - EA3HMB <ea3hmb_at_gmail.com>
