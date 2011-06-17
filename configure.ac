dnl Process this file with autoconf to produce a configure script.
AC_INIT(sjconf-sysctl, 0.1.1~dev)

dnl 2.59 is needed for AS_HELP_STRING
AC_PREREQ(2.59)

AM_INIT_AUTOMAKE([foreign])

AC_PROG_SJCONF
AC_PATH_PROG(TXT2TAGS, txt2tags)

AC_CONFIG_FILES([Makefile \
                 doc/Makefile \
                 confs/Makefile \
                 plugins/sysctl.py \
                 ])

AC_OUTPUT
