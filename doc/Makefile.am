man8_MANS = sjconf-sysctl.man
DISTCLEANFILES = sjconf-sysctl.man
EXTRA_DIST = sjconf-sysctl.t2t

SUFFIXES = .t2t

.t2t.man:
	$(TXT2TAGS) -o $@ $<
