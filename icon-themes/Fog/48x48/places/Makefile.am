themedir = $(datadir)/icons/Fog
size = 48x48
context = places

iconsdir = $(themedir)/$(size)/$(context)

icons_DATA =			\
	folder-documents.png	\
	folder-download.png	\
	folder-music.png	\
	folder-pictures.png	\
	folder.png		\
	folder-publicshare.png	\
	folder-remote.png	\
	folder-saved-search.png	\
	folder-templates.png	\
	folder-videos.png	\
	user-desktop.png	\
	user-home.png

EXTRA_DIST =		\
	$(icons_DATA)

if LEGACY_ICON_MAPPING
install-data-local: install-iconsDATA
	(cd $(DESTDIR)$(themedir)/$(size) && $(ICONMAP) -c $(context))
endif
