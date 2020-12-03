ACLOCAL_AMFLAGS = -I m4
include_HEADERS = ../inc/common-socket.h ../inc/tcp-socket.h
AM_CFLAGS = -I../inc -Wall -fPIC -Wl,-rpath,.
lib_LTLIBRARIES = libstcp.la
libstcp_la_SOURCES = tcp-socket.c 
libstcp_la_LDFLAGS = -llog -ldl -version-info 1:0:0
