if HAVE_SNDFILE
pkglib_LTLIBRARIES = sndfile.la
sndfile_la_SOURCES = sndfile.c
sndfile_la_LDFLAGS = -module -avoid-version

sndfile_la_LIBADD = $(LDADD) $(SNDFILE_LIBS)
AM_CFLAGS = $(CFLAGS) $(WAVPACK_CFLAGS) -std=c99
endif
