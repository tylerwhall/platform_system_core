pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libmincrypt/mincrypt.pc

lib_LTLIBRARIES = libmincrypt.la
libmincrypt_la_CFLAGS = -Iinclude
libmincrypt_la_SOURCES = \
	libmincrypt/rsa.c \
	libmincrypt/rsa_e_3.c \
	libmincrypt/rsa_e_f4.c \
	libmincrypt/sha.c
mincryptincludedir = $(includedir)/mincrypt
mincryptinclude_HEADERS = \
	include/mincrypt/sha.h \
	include/mincrypt/rsa.h
