## $Id: Makefile.am 618 2006-01-15 06:42:19Z dugsong $

include $(top_srcdir)/Makefile.am.common

ACLOCAL_AMFLAGS = -I m4

SUBDIRS =	include man src python test

bin_SCRIPTS =	dnet-config

EXTRA_DIST =	LICENSE Makefile.am.common acconfig.h

CLEANFILES =	dnet-config

AUX_DIST =	$(ac_aux_dir)/acinclude.m4	\
		$(ac_aux_dir)/config.guess	\
		$(ac_aux_dir)/config.sub	\
		$(ac_aux_dir)/install-sh	\
		$(ac_aux_dir)/ltmain.sh		\
		$(ac_aux_dir)/missing		\
		$(ac_aux_dir)/mkinstalldirs
