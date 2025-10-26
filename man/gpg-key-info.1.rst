..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


=================
gpg-key-info
=================

--------------------------------------------------------------
GNU Privacy Guard Key Info
--------------------------------------------------------------
:Version: gpg-key-info |version|
:Manual section: 1


Synopsis
========

gpg-key-info *[options]* *key*


Description
===========

Retrieves info from a GNU Privacy Guard key file


Options
=======

-o output-type          Can be 'fingerprint', 'id', 'name'
                        or 'email'.
-t key-type             Can be 'public' or 'private'.
-H gnupg-home           GnuPG configuration directory.

-h                      Display help.
-c                      Enable color output
-v                      Enable verbose output


Bugs
====

https://github.com/themartiancompany/gpg-key-info/-/issues


Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.


See also
========

# gpg
* gpg-signature-info
* gpg-signature-verify
* evm-gpg
* evm-gpg-decrypt
* evm-gpg-key-address-check
* evm-gpg-signature-verify

.. include:: variables.rst
