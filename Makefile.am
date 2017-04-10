EXTRA_DIST = \
	$(srcdir)/src \
	$(srcdir)/COPYING \
	$(srcdir)/AUTHORS \
	$(srcdir)/README.md

themedir = $(datadir)/icons

install-data-hook:
	test -d $(DESTDIR)$(themedir) || $(MKDIR_P) $(DESTDIR)$(themedir)
	cp -Rv $(srcdir)/Arc $(DESTDIR)$(themedir)/.

uninstall-hook:
test -d $(DESTDIR)$(themedir)/src && rm -rf $(DESTDIR)$(themedir)/src
