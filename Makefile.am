include $(top_srcdir)/build/modmake.rulesam
MODNAME=mod_test10086

mod_LTLIBRARIES = mod_test10086.la
mod_test10086_la_SOURCES  = mod_aliasr.c
mod_test10086_la_CFLAGS   = $(AM_CFLAGS)
mod_test10086_la_CPPFLAGS = $(test10086_CFLAGS) $(AM_CPPFLAGS)
mod_test10086_la_LIBADD   = $(switch_builddir)/libfreeswitch.la
mod_test10086_la_LDFLAGS  = $(test10086_LIBS) -avoid-version -module -no-undefined -shared
