EXTRA_DIST=autogen.sh libafcgi.pc.in

ACLOCAL_AMFLAGS=-I m4

AM_CFLAGS=$(GLIB_CFLAGS)

lib_LTLIBRARIES=libafcgi.la
libafcgi_la_SOURCES=libafcgi.c
libafcgi_la_LIBADD=$(GLIB_LIBS)
libafcgi_la_LDFLAGS= -version-info 0:0:0

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libafcgi.pc

$(pkgconfig_DATA): config.status

include_HEADERS = libafcgi.h libafcgi-config.h
