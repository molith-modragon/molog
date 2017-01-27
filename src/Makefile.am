AM_CFLAGS = $(WFLAGS)

sbin_PROGRAMS = \
	molog

AM_CPPFLAGS = \
	-DCONFDIR=\"$(sysconfdir)\" \
	-I$(top_srcdir)/gnulib/lib

molog_SOURCES = \
	helpers.h \
	molog.c \
	molog.h \
	molog_p.h
	syslognames.h
molog_LDADD = $(top_builddir)/gnulib/lib/libgnu.a
