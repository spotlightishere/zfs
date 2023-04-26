include $(top_srcdir)/config/Rules.am

pkgexecdir = $(datadir)/@PACKAGE@/zfs-tests/bin

pkgexec_PROGRAMS = idmap_util

idmap_util_SOURCES = idmap_util.c
idmap_util_LDADD = \
	$(abs_top_builddir)/lib/libspl/libspl.la
