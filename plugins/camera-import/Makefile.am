dist_gq_bin_SCRIPTS = geeqie-camera-import geeqie-camera-import-hook-script

gq_desktopdir = $(appdir)/applications
gq_desktop_in_files = camera-import.desktop.in
gq_desktop_DATA = $(gq_desktop_in_files:.desktop.in=.desktop)
@INTLTOOL_DESKTOP_RULE@

EXTRA_DIST = $(gq_desktop_in_files)
CLEANFILES = $(gq_desktop_DATA)
