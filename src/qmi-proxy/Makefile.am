
libexec_PROGRAMS = qmi-proxy

qmi_proxy_CPPFLAGS = \
	$(GLIB_CFLAGS) \
	-I$(top_srcdir) \
	-I$(top_srcdir)/src/libqmi-glib \
	-I$(top_srcdir)/src/libqmi-glib/generated \
	-I$(top_builddir)/src/libqmi-glib \
	-I$(top_builddir)/src/libqmi-glib/generated

qmi_proxy_SOURCES = qmi-proxy.c

qmi_proxy_LDADD = \
	$(GLIB_LIBS) \
	$(top_builddir)/src/libqmi-glib/libqmi-glib.la
