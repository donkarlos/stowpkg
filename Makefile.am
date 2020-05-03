##								-*-Makefile-*-
##  Makefile.am			- stowpkg `Makefile.in' template
##
##  Copyright (C) 2020 Das Computerlabor (DCl-M)
##
##  This program is free software; you can redistribute it and/or modify
##  it under the terms of the GNU General Public License as published by
##  the Free Software Foundation; either version 2 of the License, or
##  (at your option) any later version.
##
##  This program is distributed in the hope that it will be useful,
##  but WITHOUT ANY WARRANTY; without even the implied warranty of
##  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
##  GNU General Public License for more details.
##
##  You should have received a copy of the GNU General Public License along
##  with this program; if not, write to the Free Software Foundation, Inc.,
##  51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
##
##  AUTHOR(S):	ks	Karl Schmitz <carolus.faber@gmail.com>
##
##  WRITTEN BY:	ks	2020-05-03
##  CHANGED BY:
##
##  NOTE:   (1)	Update the build system with autoreconf(1).
##----------------------------------------------------------------------------
##  Initialization:
##----------------------------------------------------------------------------
include $(top_srcdir)/auto/autofinish.am

##----------------------------------------------------------------------------
##  Extra primaries:
##----------------------------------------------------------------------------
stowdir			= $(prefix)/stow

##----------------------------------------------------------------------------
##  Distribute license:
##----------------------------------------------------------------------------
dist_noinst_DATA        = LICENSE

##----------------------------------------------------------------------------
##  Finish and install scripts, libraries, and package data:
##----------------------------------------------------------------------------
bin_SCRIPTS		= bin/stowpkg

