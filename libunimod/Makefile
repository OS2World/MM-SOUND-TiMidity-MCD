# Makefile.in generated automatically by automake 1.4 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.

# TiMidity++ -- MIDI to WAVE converter and player
# Copyright (C) 1999-2001 Masanao Izumo <mo@goice.co.jp>
# Copyright (C) 1995 Tuukka Toivonen <tt@cgs.fi>
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.


SHELL = /bin/sh

srcdir = .
top_srcdir = ..

prefix = /usr/local
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = c:
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/TiMidity++
pkglibdir = $(libdir)/TiMidity++
pkgincludedir = $(includedir)/TiMidity++

top_builddir = ..

ACLOCAL = aclocal
AUTOCONF = autoconf
AUTOMAKE = C:/timid2104/missing automake
AUTOHEADER = autoheader

INSTALL = c:/utils/ginstall -c
INSTALL_PROGRAM = ${INSTALL} $(AM_INSTALL_PROGRAM_FLAGS)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL}
transform = s,x,x,

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_alias = @build_alias@
build_triplet = i386-pc-os2-emx
host_alias = @host_alias@
host_triplet = i386-pc-os2-emx
target_alias = @target_alias@
target_triplet = i386-pc-os2-emx
ALSA_CFLAGS = 
ALSA_LIBS = 
CC = gcc
ELFILES = 
EMACS = no
ESD_CFLAGS = 
ESD_CONFIG = 
ESD_LIBS = 
EXTRALIBS =  -los2me
GTK_CFLAGS = 
GTK_CONFIG = 
GTK_LIBS = 
INTERFACE_SRCS =  mcd_c.c
LN_S = ln
MAKEINFO = C:/timid2104/missing makeinfo
NETSRCS = 
PACKAGE = TiMidity++
RANLIB = :
SHCFLAGS =  -fPIC
SHELL = /bin/sh
SHLD = gcc -shared  -Lc -L/emx/lib;c -L/xfree86/lib -L/usr/local/lib
SYSEXTRAS =  dart_a.c
VERSION = 2.10.4
WISH = wish
dynamic_targets = 
lispdir = 
program_transform_name = s,x,x,
so = so
tcltk_dep = 
timidity_LDFLAGS = 

INCLUDES =  	-I$(top_srcdir) 	-I$(top_srcdir)/timidity 	-I$(top_srcdir)/utils 	-I$(top_srcdir)/libarc 	$(EXTRAINCS)


noinst_LIBRARIES = libunimod.a

libunimod_a_SOURCES =  	load_669.c 	load_amf.c 	load_dsm.c 	load_far.c 	load_gdm.c 	load_imf.c 	load_it.c 	load_m15.c 	load_med.c 	load_mod.c 	load_mtm.c 	load_okt.c 	load_s3m.c 	load_stm.c 	load_stx.c 	load_ult.c 	load_uni.c 	load_xm.c 	mloader.c 	mlutil.c 	mmsup.c 	munitrk.c 	unimod.h 	unimod_priv.h

mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = ../config.h ../interface.h
CONFIG_CLEAN_FILES = 
LIBRARIES =  $(noinst_LIBRARIES)


DEFS = -DHAVE_CONFIG_H -I. -I$(srcdir) -I.. -I..
CPPFLAGS =  -Ic -I/emx/include;c -I/xfree86/include -I/usr/local/include -DAU_DART -DMCD -D__ST_MT_ERRNO__ -DLAGRANGE_INTERPOLATION $(DEF_PKGDATADIR) $(DEF_PKGLIBDIR) $(DEF_DEFAULT_PATH) -DTIMIDITY_OUTPUT_ID=\"d\"
LDFLAGS =  -Lc -L/emx/lib;c -L/xfree86/lib -L/usr/local/lib
LIBS = -lsocket -lm  timidmcd.def -ldl      -los2me
X_CFLAGS = 
X_LIBS = 
X_EXTRA_LIBS = 
X_PRE_LIBS = 
libunimod_a_LIBADD = 
libunimod_a_OBJECTS =  load_669.o load_amf.o load_dsm.o load_far.o \
load_gdm.o load_imf.o load_it.o load_m15.o load_med.o load_mod.o \
load_mtm.o load_okt.o load_s3m.o load_stm.o load_stx.o load_ult.o \
load_uni.o load_xm.o mloader.o mlutil.o mmsup.o munitrk.o
AR = ar
CFLAGS =  -g -Zmt -Zdll
COMPILE = $(CC) $(DEFS) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(LDFLAGS) -o $@
DIST_COMMON =  AUTHORS Makefile.am Makefile.in


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = gtar
GZIP_ENV = --best
SOURCES = $(libunimod_a_SOURCES)
OBJECTS = $(libunimod_a_OBJECTS)

all: all-redirect
.SUFFIXES:
.SUFFIXES: .S .c .o .s
$(srcdir)/Makefile.in: Makefile.am $(top_srcdir)/configure.in $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --gnu --include-deps libunimod/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status


mostlyclean-noinstLIBRARIES:

clean-noinstLIBRARIES:
	-test -z "$(noinst_LIBRARIES)" || rm -f $(noinst_LIBRARIES)

distclean-noinstLIBRARIES:

maintainer-clean-noinstLIBRARIES:

.c.o:
	$(COMPILE) -c $<

.s.o:
	$(COMPILE) -c $<

.S.o:
	$(COMPILE) -c $<

mostlyclean-compile:
	-rm -f *.o core *.core

clean-compile:

distclean-compile:
	-rm -f *.tab.c

maintainer-clean-compile:

libunimod.a: $(libunimod_a_OBJECTS) $(libunimod_a_DEPENDENCIES)
	-rm -f libunimod.a
	$(AR) cru libunimod.a $(libunimod_a_OBJECTS) $(libunimod_a_LIBADD)
	$(RANLIB) libunimod.a

tags: TAGS

ID: $(HEADERS) $(SOURCES) $(LISP)
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	here=`pwd` && cd $(srcdir) \
	  && mkid -f$$here/ID $$unique $(LISP)

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	test -z "$(ETAGS_ARGS)$$unique$(LISP)$$tags" \
	  || (cd $(srcdir) && etags $(ETAGS_ARGS) $$tags  $$unique $(LISP) -o $$here/TAGS)

mostlyclean-tags:

clean-tags:

distclean-tags:
	-rm -f TAGS ID

maintainer-clean-tags:

distdir = $(top_builddir)/$(PACKAGE)-$(VERSION)/$(subdir)

subdir = libunimod

distdir: $(DISTFILES)
	@for file in $(DISTFILES); do \
	  d=$(srcdir); \
	  if test -d $$d/$$file; then \
	    cp -pr $$d/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done
load_669.o: load_669.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_amf.o: load_amf.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_dsm.o: load_dsm.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_far.o: load_far.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_gdm.o: load_gdm.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_imf.o: load_imf.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_it.o: load_it.c ../config.h unimod_priv.h unimod.h ../libarc/url.h
load_m15.o: load_m15.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_med.o: load_med.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_mod.o: load_mod.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_mtm.o: load_mtm.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_okt.o: load_okt.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_s3m.o: load_s3m.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_stm.o: load_stm.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_stx.o: load_stx.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_ult.o: load_ult.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_uni.o: load_uni.c ../config.h unimod_priv.h unimod.h \
	../libarc/url.h
load_xm.o: load_xm.c ../config.h unimod_priv.h unimod.h ../libarc/url.h
mloader.o: mloader.c ../config.h unimod_priv.h unimod.h ../libarc/url.h
mlutil.o: mlutil.c ../config.h unimod_priv.h unimod.h ../libarc/url.h
mmsup.o: mmsup.c unimod_priv.h unimod.h ../libarc/url.h
munitrk.o: munitrk.c ../config.h unimod_priv.h unimod.h ../libarc/url.h

info-am:
info: info-am
dvi-am:
dvi: dvi-am
check-am: all-am
check: check-am
installcheck-am:
installcheck: installcheck-am
install-exec-am:
install-exec: install-exec-am

install-data-am:
install-data: install-data-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-am
uninstall-am:
uninstall: uninstall-am
all-am: Makefile $(LIBRARIES)
all-redirect: all-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs:


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
mostlyclean-am:  mostlyclean-noinstLIBRARIES mostlyclean-compile \
		mostlyclean-tags mostlyclean-generic

mostlyclean: mostlyclean-am

clean-am:  clean-noinstLIBRARIES clean-compile clean-tags clean-generic \
		mostlyclean-am

clean: clean-am

distclean-am:  distclean-noinstLIBRARIES distclean-compile \
		distclean-tags distclean-generic clean-am

distclean: distclean-am

maintainer-clean-am:  maintainer-clean-noinstLIBRARIES \
		maintainer-clean-compile maintainer-clean-tags \
		maintainer-clean-generic distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-am

.PHONY: mostlyclean-noinstLIBRARIES distclean-noinstLIBRARIES \
clean-noinstLIBRARIES maintainer-clean-noinstLIBRARIES \
mostlyclean-compile distclean-compile clean-compile \
maintainer-clean-compile tags mostlyclean-tags distclean-tags \
clean-tags maintainer-clean-tags distdir info-am info dvi-am dvi check \
check-am installcheck-am installcheck install-exec-am install-exec \
install-data-am install-data install-am install uninstall-am uninstall \
all-redirect all-am all installdirs mostlyclean-generic \
distclean-generic clean-generic maintainer-clean-generic clean \
mostlyclean distclean maintainer-clean


include $(top_builddir)/common.makefile

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
