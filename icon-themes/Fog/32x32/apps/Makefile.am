themedir = $(datadir)/icons/Fog
size = 32x32
context = apps

iconsdir = $(themedir)/$(size)/$(context)

icons_DATA =			\
	preferences-desktop-display.png

EXTRA_DIST =		\
	$(icons_DATA)

if LEGACY_ICON_MAPPING
install-data-local: install-iconsDATA
	(cd $(DESTDIR)$(themedir)/$(size) && $(ICONMAP) -c $(context))
endif
