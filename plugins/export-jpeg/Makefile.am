dist_gq_bin_SCRIPTS = geeqie-export-jpeg

gq_desktopdir = $(appdir)/applications
gq_desktop_in_files = export-jpeg.desktop.in
gq_desktop_DATA = $(gq_desktop_in_files:.desktop.in=.desktop)
@INTLTOOL_DESKTOP_RULE@

EXTRA_DIST = $(gq_desktop_in_files)
CLEANFILES = $(gq_desktop_DATA)
