if HAVE_CXX11
EXAMPLES_CPP11 = examples/cpp11
endif

if HAVE_CXX14
EXAMPLES_CPP14 = examples/cpp14
endif

SUBDIRS = $(EXAMPLES_CPP11) $(EXAMPLES_CPP14)

DIST_SUBDIRS = examples/cpp11 examples/cpp14 examples/cpp17

EXTRA_DIST = \
	Makefile.mgw \
	Makefile.msc \
	tools/handlerviz.pl

MAINTAINERCLEANFILES = \
	$(srcdir)/Makefile.in
