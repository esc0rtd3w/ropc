#########################################################################
#                                                                       #
#                            Objective Caml                             #
#                                                                       #
#            Xavier Leroy, projet Cristal, INRIA Rocquencourt           #
#                                                                       #
#   Copyright 1999 Institut National de Recherche en Informatique et    #
#   en Automatique.  All rights reserved.  This file is distributed     #
#   under the terms of the GNU Library General Public License, with     #
#   the special exception on linking described in file ../../LICENSE.   #
#                                                                       #
#########################################################################

# $Id: Makefile 8489 2007-11-08 09:17:48Z frisch $

# Common Makefile for otherlibs on the Unix ports

CAMLC=ocamlc
CAMLOPT=ocamlopt.opt
CFLAGS=-I$(ROOTDIR)/byterun -O $(SHAREDCCCOMPOPTS) $(EXTRACFLAGS)

include ../Makefile.shared
# Note .. is the current directory (this makefile is included from
# a subdirectory)
