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
lispdir = 
program_transform_name = s,x,x,
so = so
tcltk_dep = 
timidity_LDFLAGS = 

SUFFIXES = .ptcl .tcl .so

SUBDIRS = motif_bitmaps bitmaps pixmaps

INCLUDES =  	-I$(top_srcdir) 	-I$(top_srcdir)/timidity 	-I$(top_srcdir)/libarc 	-I$(top_srcdir)/utils 	$(EXTRAINCS)


noinst_LIBRARIES = libinterface.a

libinterface_a_SOURCES =  	dumb_c.c 	wrdt_dumb.c 	wrdt_tty.c


EXTRA_libinterface_a_SOURCES =  	ncurs_c.c 	slang_c.c 	motif.h 	motif_c.c 	motif_i.c 	motif_p.c 	tk_c.c 	emacs_c.c 	vt100.h 	vt100.c 	vt100_c.c 	xaw.h 	xaw_c.c 	xaw_i.c 	xaw_redef.c 	xskin.h 	xskin_c.c 	xskin_i.c 	xskin_loadBMP.c 	xskin_spectrum.c 	wrdt_x.c 	x_sherry.c 	x_sherry.h 	x_wrdwindow.c 	x_wrdwindow.h 	VTPrsTbl.c 	VTparse.h 	x_mag.c 	x_mag.h 	dynamic_c.c 	mac_c.c 	mac_c.h 	mac_mag.c 	mac_mag.h 	mac_trace.c 	mac_wrdwindow.c 	mac_wrdwindow.h 	wrdt_mac.c 	wrdt_wcon.c 	gtk_c.c 	gtk_h.h 	gtk_i.c 	gtk_p.c 	soundspec.c 	soundspec.h 	x_sherry.c 	x_sherry.h 	check.xbm 	arrow.xbm 	on.xbm 	off.xbm 	server_c.c 	server_defs.h 	alsaseq_c.c 	w32g.h 	w32g_c.c 	w32g_ini.c 	w32g_rec.h 	w32g_res.h 	w32g_res.rc 	w32g_utl.c 	w32g_utl.h 	w32g_ut2.c 	w32g_ut2.h 	w32g_i.c 	w32g_playlist.c 	w32g_pref.c 	w32g_pref.h 	w32g_subwin.c 	w32g_subwin.h 	w32g_btn.bmp 	w32g_icon.ico 	w32g_sleep.bmp 	w32g_subbtn.bmp


#WRD_OBJS = 	wrdt_x.o 	x_wrdwindow.o 	VTPrsTbl.o 	x_mag.o 	x_sherry.o

#WRD_WINCON_OBJS = wrdt_wcon.o

#DYNAMIC_OBJS = dynamic_c.o

#SOUND_SPEC_OBJS = 	soundspec.o

#W32GUI_DEPS = w32g_res.res

MCD_OBJS = muldiv.o

INTERFACE_OBJS = $(INTERFACE_SRCS:.c=.o)

libinterface_a_LIBADD =  	$(INTERFACE_OBJS) 	$(WRD_OBJS) 	$(WRD_WINCON_OBJS) 	$(DYNAMIC_OBJS) 	$(SOUND_SPEC_OBJS) $(MCD_OBJS)


libinterface_a_DEPENDENCIES =  	$(top_builddir)/interface.h 	$(libinterface_a_LIBADD) 	$(tcltk_dep) 	$(W32GUI_DEPS)


# Tcl interface sources
TCLSRCS = tkmidity.ptcl tkpanel.tcl browser.tcl misc.tcl
# Tcl/Tk sources
TCLF = tkmidity.tcl tkpanel.tcl browser.tcl misc.tcl
ALLTCLF = $(TCLF) tclIndex

EXTRA_DIST =  	tkmidity.ptcl 	tkpanel.tcl 	browser.tcl 	misc.tcl 	timidity.el 	tclIndex 	interface_T.txt 	interface_a.txt 	interface_e.txt 	interface_g.txt 	interface_i.txt 	interface_m.txt 	interface_n.txt 	interface_s.txt

#install_tk = install.tk
#install_tk = install.tk
#install_xaw = install.xaw
#install_xaw = install.xaw

#ELFILES = 
#install_el = install.el

###
### For dynamic interfaces
###

#dynamic_targets = 
#install_dynamics = install.dynamics
#n_so_libs = 
#s_so_libs = 
#m_so_libs = 
#k_so_libs = 
#e_so_libs = 
#T_so_libs = 
#a_so_libs = 
#i_so_libs = 
#g_so_libs = 
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
libinterface_a_OBJECTS =  dumb_c.o wrdt_dumb.o wrdt_tty.o
AR = ar
CFLAGS =  -g -Zmt -Zdll
COMPILE = $(CC) $(DEFS) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(LDFLAGS) -o $@
DIST_COMMON =  Makefile.am Makefile.in


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = gtar
GZIP_ENV = --best
SOURCES = $(libinterface_a_SOURCES) $(EXTRA_libinterface_a_SOURCES)
OBJECTS = $(libinterface_a_OBJECTS)

all: all-redirect
.SUFFIXES:
.SUFFIXES: .so .S .c .o .ptcl .s .tcl
$(srcdir)/Makefile.in: Makefile.am $(top_srcdir)/configure.in $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --gnu --include-deps interface/Makefile

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

distclean-compile:
	-rm -f *.tab.c

maintainer-clean-compile:

libinterface.a: $(libinterface_a_OBJECTS) $(libinterface_a_DEPENDENCIES)
	-rm -f libinterface.a
	$(AR) cru libinterface.a $(libinterface_a_OBJECTS) $(libinterface_a_LIBADD)
	$(RANLIB) libinterface.a

# This directory's subdirectories are mostly independent; you can cd
# into them and run `make' without going through this Makefile.
# To change the values of `make' variables: instead of editing Makefiles,
# (1) if the variable is set in `config.status', edit `config.status'
#     (which will cause the Makefiles to be regenerated when you run `make');
# (2) otherwise, pass the desired values on the `make' command line.



all-recursive install-data-recursive install-exec-recursive \
installdirs-recursive install-recursive uninstall-recursive  \
check-recursive installcheck-recursive info-recursive dvi-recursive:
	@set fnord $(MAKEFLAGS); amf=$$2; \
	dot_seen=no; \
	target=`echo $@ | sed s/-recursive//`; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    dot_seen=yes; \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	   || case "$$amf" in *=*) exit 1;; *k*) fail=yes;; *) exit 1;; esac; \
	done; \
	if test "$$dot_seen" = "no"; then \
	  $(MAKE) $(AM_MAKEFLAGS) "$$target-am" || exit 1; \
	fi; test -z "$$fail"

mostlyclean-recursive clean-recursive distclean-recursive \
maintainer-clean-recursive:
	@set fnord $(MAKEFLAGS); amf=$$2; \
	dot_seen=no; \
	rev=''; list='$(SUBDIRS)'; for subdir in $$list; do \
	  rev="$$subdir $$rev"; \
	  test "$$subdir" = "." && dot_seen=yes; \
	done; \
	test "$$dot_seen" = "no" && rev="$$rev ."; \
	target=`echo $@ | sed s/-recursive//`; \
	for subdir in $$rev; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	   || case "$$amf" in *=*) exit 1;; *k*) fail=yes;; *) exit 1;; esac; \
	done && test -z "$$fail"
tags-recursive:
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  test "$$subdir" = . || (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) tags); \
	done

tags: TAGS

ID: $(HEADERS) $(SOURCES) $(LISP)
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	here=`pwd` && cd $(srcdir) \
	  && mkid -f$$here/ID $$unique $(LISP)

TAGS: tags-recursive $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
   if test "$$subdir" = .; then :; else \
	    test -f $$subdir/TAGS && tags="$$tags -i $$here/$$subdir/TAGS"; \
   fi; \
	done; \
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

subdir = interface

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
	for subdir in $(SUBDIRS); do \
	  if test "$$subdir" = .; then :; else \
	    test -d $(distdir)/$$subdir \
	    || mkdir $(distdir)/$$subdir \
	    || exit 1; \
	    chmod 777 $(distdir)/$$subdir; \
	    (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) top_distdir=../$(top_distdir) distdir=../$(distdir)/$$subdir distdir) \
	      || exit 1; \
	  fi; \
	done
VTPrsTbl.o: VTPrsTbl.c VTparse.h
dumb_c.o: dumb_c.c ../config.h ../timidity/timidity.h ../utils/support.h \
	../timidity/common.h ../libarc/url.h ../utils/mblock.h \
	../timidity/output.h ../timidity/controls.h \
	../timidity/instrum.h ../timidity/playmidi.h \
	../timidity/readmidi.h
ncurs_c.o: ncurs_c.c ../config.h ../timidity/timidity.h \
	../utils/support.h ../timidity/common.h ../libarc/url.h \
	../utils/mblock.h ../timidity/instrum.h ../timidity/playmidi.h \
	../timidity/readmidi.h ../timidity/output.h \
	../timidity/controls.h ../timidity/miditrace.h ../utils/timer.h \
	../utils/bitset.h ../libarc/arc.h ../timidity/aq.h \
	../timidity/mid-j.defs
wrdt_dumb.o: wrdt_dumb.c ../config.h ../timidity/timidity.h \
	../utils/support.h ../timidity/common.h ../libarc/url.h \
	../utils/mblock.h ../timidity/instrum.h ../timidity/playmidi.h \
	../timidity/readmidi.h ../timidity/controls.h ../timidity/wrd.h
wrdt_tty.o: wrdt_tty.c ../config.h ../timidity/timidity.h \
	../utils/support.h ../timidity/common.h ../libarc/url.h \
	../utils/mblock.h ../timidity/instrum.h ../timidity/playmidi.h \
	../timidity/readmidi.h ../timidity/controls.h ../timidity/wrd.h
wrdt_x.o: wrdt_x.c ../config.h ../timidity/timidity.h ../utils/support.h \
	../timidity/common.h ../libarc/url.h ../utils/mblock.h \
	../timidity/instrum.h ../timidity/playmidi.h \
	../timidity/readmidi.h ../timidity/controls.h ../timidity/wrd.h \
	x_wrdwindow.h x_mag.h x_sherry.h
x_mag.o: x_mag.c ../config.h ../timidity/timidity.h ../utils/support.h \
	../timidity/common.h ../libarc/url.h ../utils/mblock.h x_mag.h \
	../timidity/controls.h ../timidity/wrd.h
x_sherry.o: x_sherry.c ../config.h ../timidity/timidity.h \
	../utils/support.h ../timidity/common.h ../libarc/url.h \
	../utils/mblock.h ../timidity/controls.h ../timidity/wrd.h \
	../timidity/aq.h x_sherry.h
x_wrdwindow.o: x_wrdwindow.c ../config.h ../timidity/timidity.h \
	../utils/support.h ../timidity/common.h ../libarc/url.h \
	../utils/mblock.h x_mag.h x_wrdwindow.h VTparse.h \
	../timidity/wrd.h ../timidity/controls.h ../timidity/aq.h

info-am:
info: info-recursive
dvi-am:
dvi: dvi-recursive
check-am: all-am
check: check-recursive
installcheck-am:
installcheck: installcheck-recursive
install-exec-am: install-exec-local
install-exec: install-exec-recursive

install-data-am:
install-data: install-data-recursive

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-recursive
uninstall-am:
uninstall: uninstall-recursive
all-am: Makefile $(LIBRARIES)
all-redirect: all-recursive
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs: installdirs-recursive
installdirs-am:


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
mostlyclean-am:  mostlyclean-noinstLIBRARIES mostlyclean-compile \
		mostlyclean-tags mostlyclean-generic

mostlyclean: mostlyclean-recursive

clean-am:  clean-noinstLIBRARIES clean-compile clean-tags clean-generic \
		mostlyclean-am

clean: clean-recursive

distclean-am:  distclean-noinstLIBRARIES distclean-compile \
		distclean-tags distclean-generic clean-am

distclean: distclean-recursive

maintainer-clean-am:  maintainer-clean-noinstLIBRARIES \
		maintainer-clean-compile maintainer-clean-tags \
		maintainer-clean-generic distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-recursive

.PHONY: mostlyclean-noinstLIBRARIES distclean-noinstLIBRARIES \
clean-noinstLIBRARIES maintainer-clean-noinstLIBRARIES \
mostlyclean-compile distclean-compile clean-compile \
maintainer-clean-compile install-data-recursive \
uninstall-data-recursive install-exec-recursive \
uninstall-exec-recursive installdirs-recursive uninstalldirs-recursive \
all-recursive check-recursive installcheck-recursive info-recursive \
dvi-recursive mostlyclean-recursive distclean-recursive clean-recursive \
maintainer-clean-recursive tags tags-recursive mostlyclean-tags \
distclean-tags clean-tags maintainer-clean-tags distdir info-am info \
dvi-am dvi check check-am installcheck-am installcheck \
install-exec-local install-exec-am install-exec install-data-am \
install-data install-am install uninstall-am uninstall all-redirect \
all-am all installdirs-am installdirs mostlyclean-generic \
distclean-generic clean-generic maintainer-clean-generic clean \
mostlyclean distclean maintainer-clean


include $(top_builddir)/common.makefile

.ptcl.tcl:
	sed -e 's@%TCL_DIR%@$(TCL_DIR)@g' $< > $@
clean:
	rm -f tkmidity.tcl
	rm -f *.o
	rm -f *.$(so)

tclIndex: $(TCLSRCS)
	rm -f tclIndex
	echo 'auto_mkindex . *.tcl; exit' | $(WISH)

install.tk: $(ALLTCLF) install.bitmaps
	test -d $(DESTDIR)$(TCL_DIR) || mkdir -p $(DESTDIR)$(TCL_DIR)
	for f in $(ALLTCLF) ''; do case ".$$f" in .);; *) $(INSTALL_DATA) $$f $(DESTDIR)$(TCL_DIR);; esac; done

install.xaw: install.bitmaps

install.bitmaps:
	cd bitmaps; $(MAKE) install.bitmaps

install.el: $(ELFILES)
	test -d $(DESTDIR)$(ELISP_DIR) || mkdir -p $(DESTDIR)$(ELISP_DIR)
	for f in $(ELFILES) ''; do case ".$$f" in .);; *) $(INSTALL_DATA) $$f $(DESTDIR)$(ELISP_DIR);; esac; done

w32g_res.res: w32g_res.h w32g_rec.h w32g_res.rc \
	w32g_btn.bmp w32g_icon.ico w32g_sleep.bmp w32g_subbtn.bmp
	windres -o $@ -O coff w32g_res.rc

#all-am: $(dynamic_targets)

#install.dynamics: $(dynamic_targets)
#	test -d $(DESTDIR)$(SHLIB_DIR) || mkdir -p $(DESTDIR)$(SHLIB_DIR)
#	for f in $(dynamic_targets) ''; do case ".$$f" in .);; *) $(INSTALL_PROGRAM) $$f $(DESTDIR)$(SHLIB_DIR);; esac; done

#.c.$(so):
#	$(COMPILE) $(SHCFLAGS) -c $< -o $@

#bitset.$(so): $(top_srcdir)/utils/bitset.c
#	$(COMPILE) $(SHCFLAGS) -o $@ -c $<

#timer.$(so): $(top_srcdir)/utils/timer.c
#	$(COMPILE) $(SHCFLAGS) -o $@ -c $<

#url_buff.$(so): $(top_srcdir)/libarc/url_buff.c
#	$(COMPILE) $(SHCFLAGS) -o $@ -c $<

#support.$(so): $(top_srcdir)/utils/support.c
#	$(COMPILE) $(SHCFLAGS) -o $@ -c $<

#interface_n.$(so): ncurs_c.$(so) support.$(so) bitset.$(so) timer.$(so)
#	$(SHLD) -o $@ ncurs_c.$(so) support.$(so) bitset.$(so) timer.$(so) $(n_so_libs)

#interface_s.$(so): slang_c.$(so) support.$(so) timer.$(so)
#	$(SHLD) -o $@ slang_c.$(so) support.$(so) timer.$(so) $(s_so_libs)

#interface_m.$(so): motif_c.$(so) support.$(so) motif_i.$(so) motif_p.$(so)
#	$(SHLD) -o $@ motif_c.$(so) support.$(so) motif_i.$(so) motif_p.$(so) $(m_so_libs)

#interface_k.$(so): tk_c.$(so) support.$(so)
#	$(SHLD) -o $@ tk_c.$(so) support.$(so) $(k_so_libs)

#interface_e.$(so): emacs_c.$(so) support.$(so)
#	$(SHLD) -o $@ emacs_c.$(so) support.$(so) $(e_so_libs)

#interface_T.$(so): vt100_c.$(so) support.$(so) vt100.$(so) bitset.$(so) timer.$(so)
#	$(SHLD) -o $@ vt100_c.$(so) support.$(so) vt100.$(so) bitset.$(so) timer.$(so) $(T_so_libs)

#interface_a.$(so): xaw_c.$(so) support.$(so) xaw_i.$(so) timer.$(so)
#	$(SHLD) -o $@ xaw_c.$(so) support.$(so) xaw_i.$(so) timer.$(so) $(a_so_libs)

#interface_i.$(so): xskin_c.$(so) support.$(so) xskin_i.$(so) xskin_loadBMP.$(so) xskin_spectrum.$(so) url_buff.$(so)
#	$(SHLD) -o $@ xskin_c.$(so) support.$(so) xskin_i.$(so) xskin_loadBMP.$(so) xskin_spectrum.$(so) url_buff.$(so) $(i_so_libs)

#interface_g.$(so): gtk_c.$(so) support.$(so) gtk_i.$(so) gtk_p.$(so)
#	$(SHLD) -o $@ gtk_c.$(so) support.$(so) gtk_i.$(so) gtk_p.$(so) $(g_so_libs)

#interface_r.$(so): server_c.$(so) support.$(so)
#	$(SHLD) -o $@ server_c.$(so) support.$(so)

#interface_A.$(so): alsaseq_c.$(so) support.$(so)
#	$(SHLD) -o $@ alsaseq_c.$(so) support.$(so)

clean-compile:
	-rm -f *.$(so)

install-exec-local: $(install_tk) $(install_xaw) $(install_el) $(install_dynamics)
########## End of Makefile

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
