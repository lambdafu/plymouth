SUBDIRS = src themes images scripts systemd-units

if BUILD_DOCUMENTATION
SUBDIRS += docs
endif

AM_DISTCHECK_CONFIGURE_FLAGS = --disable-tests --without-system-root-install

EXTRA_DIST = ChangeLog                                                         \
             README

MAINTAINERCLEANFILES = aclocal.m4                                              \
                       config.h.in                                             \
                       config.h.in~                                            \
                       config.sub                                              \
                       configure                                               \
                       Makefile.in
