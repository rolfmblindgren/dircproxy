## Process this file with automake to produce Makefile.in

AM_CPPFLAGS = -I$(top_srcdir)

bin_PROGRAMS = \
	dircproxy-crypt

dircproxy_crypt_SOURCES = \
	main.c

if BUILD_BUNDLED_GETOPT
dircproxy_crypt_LDADD = \
	../getopt/libgetopt.a
endif
