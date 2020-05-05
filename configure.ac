dnl								-*-Autoconf-*-
dnl configure.ac		- stowpkg Autotools configuration
dnl
dnl Copyright (C) 2020 Das Computerlabor (DCl-M)
dnl
dnl This program is free software; you can redistribute it and/or modify
dnl it under the terms of the GNU General Public License as published by
dnl the Free Software Foundation; either version 2 of the License, or
dnl (at your option) any later version.
dnl
dnl This program is distributed in the hope that it will be useful,
dnl but WITHOUT ANY WARRANTY; without even the implied warranty of
dnl MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
dnl GNU General Public License for more details.
dnl
dnl You should have received a copy of the GNU General Public License along
dnl with this program; if not, write to the Free Software Foundation, Inc.,
dnl 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
dnl
dnl AUTHOR(S):	ks	Karl Schmitz <carolus.faber@gmail.com>
dnl
dnl WRITTEN BY:	ks	2020-05-03
dnl CHANGED BY:	ks	2020-05-05	Release 0.2.
dnl
dnl NOTE:   (1)	Update the build system with autoreconf(1).
dnl	    (2)	AM_INIT_AUTOMAKE() already invokes AC_ARG_PROGRAM, AC_PROG_-
dnl		MAKE_SET, AC_PROG_INSTALL and AM_MISSING_PROG(ACLOCAL/AUTO-
dnl		CONF/AUTOMAKE/AUTOHEADER/MAKEINFO, ...).
dnl
dnl Initialization:
dnl
AC_INIT([Build and manage self-deploying stowable packages],
    [0.3~0], [carolus.faber@gmail.com], [stowpkg])
AC_PREREQ([2.61])
AC_CONFIG_SRCDIR([bin/stowpkg.un])
AC_CONFIG_AUX_DIR([auto])
AC_CONFIG_MACRO_DIRS([auto])
AM_INIT_AUTOMAKE([foreign no-define dist-xz no-dist-gzip 1.13])
AF_INIT([auto/gensubst])

dnl
dnl Generate output files:
dnl
AF_FINISH_FILES([
    bin/stowpkg
])
AC_CONFIG_FILES([
    Makefile
])
AC_OUTPUT
