MAKEFLAGS=-s --no-print-directory
am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/amule
pkgincludedir = $(includedir)/amule
pkglibdir = $(libdir)/amule
pkglibexecdir = $(libexecdir)/amule
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-unknown-linux-gnu
host_triplet = x86_64-unknown-linux-gnu
subdir = unittests/muleunit
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/GeoIP.m4 \
	$(top_srcdir)/m4/bfd.m4 $(top_srcdir)/m4/boost.m4 \
	$(top_srcdir)/m4/build-tools.m4 $(top_srcdir)/m4/codeset.m4 \
	$(top_srcdir)/m4/cryptopp.m4 $(top_srcdir)/m4/fallocate.m4 \
	$(top_srcdir)/m4/gdlib.m4 $(top_srcdir)/m4/gettext.m4 \
	$(top_srcdir)/m4/glibc21.m4 $(top_srcdir)/m4/iconv.m4 \
	$(top_srcdir)/m4/intdiv0.m4 $(top_srcdir)/m4/inttypes-pri.m4 \
	$(top_srcdir)/m4/inttypes.m4 $(top_srcdir)/m4/inttypes_h.m4 \
	$(top_srcdir)/m4/isc-posix.m4 $(top_srcdir)/m4/kde.m4 \
	$(top_srcdir)/m4/lcmessage.m4 $(top_srcdir)/m4/lib-ld.m4 \
	$(top_srcdir)/m4/lib-link.m4 $(top_srcdir)/m4/lib-prefix.m4 \
	$(top_srcdir)/m4/libpng.m4 $(top_srcdir)/m4/libupnp.m4 \
	$(top_srcdir)/m4/mmap.m4 $(top_srcdir)/m4/muleboost.m4 \
	$(top_srcdir)/m4/nls.m4 $(top_srcdir)/m4/pkg.m4 \
	$(top_srcdir)/m4/plasmamule.m4 $(top_srcdir)/m4/progtest.m4 \
	$(top_srcdir)/m4/qt.m4 $(top_srcdir)/m4/readline.m4 \
	$(top_srcdir)/m4/stdint_h.m4 $(top_srcdir)/m4/uintmax_t.m4 \
	$(top_srcdir)/m4/ulonglong.m4 $(top_srcdir)/m4/wxwin.m4 \
	$(top_srcdir)/m4/zlib.m4 $(top_srcdir)/acinclude.m4 \
	$(top_srcdir)/configure.in
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(am__DIST_COMMON)
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
LIBRARIES = $(noinst_LIBRARIES)
ARFLAGS = cru
am__v_AR_1 = 
libmuleunit_a_AR = $(AR) $(ARFLAGS)
libmuleunit_a_LIBADD =
am_libmuleunit_a_OBJECTS = libmuleunit_a-test.$(OBJEXT) \
	libmuleunit_a-main.$(OBJEXT) libmuleunit_a-testcase.$(OBJEXT) \
	libmuleunit_a-testregistry.$(OBJEXT) \
	libmuleunit_a-MuleDebug.$(OBJEXT) \
	libmuleunit_a-StringFunctions.$(OBJEXT)
libmuleunit_a_OBJECTS = $(am_libmuleunit_a_OBJECTS)
am__v_P_1 = :
am__v_GEN_1 = 
am__v_at_1 = 
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
am__v_lt_1 = 
CXXCOMPILE = $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
am__v_CXX_1 = 
CXXLD = $(CXX)
CXXLINK = $(CXXLD) $(AM_CXXFLAGS) $(CXXFLAGS) $(AM_LDFLAGS) $(LDFLAGS) \
	-o $@
am__v_CXXLD_1 = 
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
am__v_CC_1 = 
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
am__v_CCLD_1 = 
SOURCES = $(libmuleunit_a_SOURCES)
DIST_SOURCES = $(libmuleunit_a_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
am__DIST_COMMON = $(srcdir)/Makefile.in $(top_srcdir)/depcomp \
	$(top_srcdir)/mkinstalldirs
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/hlechner/git/hl-test/amule/missing aclocal-1.15
ALCC_MANPAGES = 
ALC_MANPAGES = 
ALLOCA = 
AMTAR = $${TAR-tar}
AMULECMD_MANPAGES = 
AMULEWEB_DEFS = 
AMULE_DAEMON_MANPAGES = 
AMULE_GUI_MANPAGES = 
AR = ar
AUTOCONF = ${SHELL} /home/hlechner/git/hl-test/amule/missing autoconf
AUTOHEADER = ${SHELL} /home/hlechner/git/hl-test/amule/missing autoheader
AUTOMAKE = ${SHELL} /home/hlechner/git/hl-test/amule/missing automake-1.15
AWK = gawk
BFD_CPPFLAGS = -DHAVE_BFD
BFD_LIBS = -lbfd -liberty -ldl -lz
BOOST_CPPFLAGS = 
BOOST_LDPATH = 
BOOST_ROOT = 
BOOST_SYSTEM_LDFLAGS = 
BOOST_SYSTEM_LDPATH = 
BOOST_SYSTEM_LIBS = 
BUILD_CC = gcc
BUILD_CFLAGS = 
BUILD_CPPFLAGS = 
BUILD_EXEEXT = 
BUILD_INCLUDED_LIBINTL = no
BUILD_LDFLAGS = 
CAS_DEFS = 
CAS_MANPAGES = 
CATOBJEXT = .gmo
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = 
CPP = gcc -E
CPPFLAGS = 
CRYPTOPP_CPPFLAGS = -I/usr/include -D__WEAK_CRYPTO__
CRYPTOPP_LDFLAGS = -L/usr/lib
CRYPTOPP_LIBS = -lcryptopp
CXX = g++
CXXCPP = g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = 
CYGPATH_W = echo
DATADIRNAME = share
DEBUGFLAG = 
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DISTCHECK_CONFIGURE_FLAGS = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
ED2K_MANPAGES = ed2k.1 ed2k.de.1 ed2k.es.1 ed2k.fr.1 ed2k.hu.1 ed2k.it.1 ed2k.ro.1 ed2k.ru.1 ed2k.tr.1 ed2k.zh_TW.1
EGREP = /usr/bin/grep -E
EXEEXT = 
GDLIB_CFLAGS = 
GDLIB_CONFIG_PATH = 
GDLIB_LDFLAGS = 
GDLIB_LIBS = 
GENCAT = gencat
GEOIP_CPPFLAGS = 
GEOIP_LDFLAGS = 
GEOIP_LIBS = 
GLIBC21 = yes
GMSGFMT = /usr/bin/msgfmt
GREP = /usr/bin/grep
INCINTL = 
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
INSTOBJEXT = .mo
INTLBISON = bison
INTLLIBS = 
INTLOBJS = 
INTL_LIBTOOL_SUFFIX_PREFIX = 
KDE4_CONFIG = 
KDE_APPLNK_PATH = 
KDE_HEADER_DIR = 
KDE_ICON_PATH = 
KDE_MIME_PATH = 
KDE_MODULE_PATH = 
KDE_SERVICE_PATH = 
LD = ld
LDFLAGS = 
LEX = flex
LEXLIB = -lfl
LEX_OUTPUT_ROOT = lex.yy
LIBICONV = 
LIBINTL = 
LIBOBJS = 
LIBPNG_CFLAGS = 
LIBPNG_CONFIG_PATH = 
LIBPNG_LDFLAGS = 
LIBPNG_LIBS = 
LIBS = 
LIBUPNP_CFLAGS = -pthread
LIBUPNP_CPPFLAGS = -I/usr/include/upnp -DENABLE_UPNP=1
LIBUPNP_LDFLAGS = 
LIBUPNP_LIBS = -pthread -lupnp -lthreadutil -lixml
LTLIBICONV = 
LTLIBINTL = 
LTLIBOBJS = 
MAINT = #
MAKEINFO = ${SHELL} /home/hlechner/git/hl-test/amule/missing makeinfo
MKDIR_P = /usr/bin/mkdir -p
MKINSTALLDIRS = ./mkinstalldirs
MONOLITHIC_MANPAGES = amule.1 amule.de.1 amule.es.1 amule.fr.1 amule.hu.1 amule.it.1 amule.ro.1 amule.ru.1 amule.tr.1 amule.zh_TW.1
MSGFMT = /usr/bin/msgfmt
MSGMERGE = /usr/bin/msgmerge
MULECFLAGS = -w  -g -ggdb -fno-inline -fmessage-length=0
MULECPPFLAGS =  -D__DEBUG__ -DUSE_WX_EXTENSIONS
MULECXXFLAGS = -w  -g -ggdb -fno-inline -fmessage-length=0
MULELDFLAGS =  -lpthread
MULERCFLAGS = -I/usr/lib/wx/include/gtk2-unicode-3.0 -I/usr/include/wx-3.0 -D_FILE_OFFSET_BITS=64 -DWXUSINGDLL -D__WXGTK__ 
OBJEXT = o
PACKAGE = amule
PACKAGE_BUGREPORT = admin@amule.org
PACKAGE_NAME = aMule
PACKAGE_STRING = aMule SVN
PACKAGE_TARNAME = amule
PACKAGE_URL = 
PACKAGE_VERSION = SVN
PATH_SEPARATOR = :
PKG_CONFIG = /usr/bin/pkg-config
POSUB = po
POW_LIB = 
QT_CORE_CXXFLAGS = 
QT_CORE_LIBS = 
QT_DBUS_LDFLAGS = 
QT_GUI_CXXFLAGS = 
QT_GUI_LIBS = 
QT_MOC = 
RANLIB = ranlib
RC = 
RCFLAGS = 
READLINE_LIBS = 
RESOLV_LIB = 
SED = /usr/bin/sed
SET_MAKE = 
SHELL = /bin/sh
STRIP = strip
SVNDATE = 
USE_INCLUDED_LIBINTL = no
USE_NLS = yes
VERSION = SVN
WEBSERVER_MANPAGES = 
WXBASE_CPPFLAGS = -I/usr/lib/wx/include/gtk2-unicode-3.0 -I/usr/include/wx-3.0 -D_FILE_OFFSET_BITS=64 -DWXUSINGDLL -D__WXGTK__ -DwxUSE_GUI=0
WXBASE_LIBS = -pthread   -lwx_baseu_net-3.0 -lwx_baseu-3.0 
WXCAS_MANPAGES = 
WX_CFLAGS = -I/usr/lib/wx/include/gtk2-unicode-3.0 -I/usr/include/wx-3.0 -D_FILE_OFFSET_BITS=64 -DWXUSINGDLL -D__WXGTK__ -pthread
WX_CFLAGS_ONLY = -pthread
WX_CONFIG_PATH = /usr/bin/wx-config
WX_CPPFLAGS = -I/usr/lib/wx/include/gtk2-unicode-3.0 -I/usr/include/wx-3.0 -D_FILE_OFFSET_BITS=64 -DWXUSINGDLL -D__WXGTK__
WX_CXXFLAGS = -I/usr/lib/wx/include/gtk2-unicode-3.0 -I/usr/include/wx-3.0 -D_FILE_OFFSET_BITS=64 -DWXUSINGDLL -D__WXGTK__ -pthread
WX_CXXFLAGS_ONLY = 
WX_DEBUG = 0
WX_LIBS = -pthread   -lwx_gtk2u_adv-3.0 -lwx_gtk2u_core-3.0 -lwx_baseu_net-3.0 -lwx_baseu-3.0 
WX_PORT = gtk2
WX_RESCOMP = 
WX_SHARED = 1
WX_UNICODE = 
WX_VERSION_FULL = 3.0.2
WX_VERSION_MAJOR = 3
WX_VERSION_MINOR = 0
XGETTEXT = /usr/bin/xgettext
YACC = bison -y
YFLAGS = 
ZLIB_CPPFLAGS = 
ZLIB_LDFLAGS = 
ZLIB_LIBS = -lz
abs_builddir = /home/hlechner/git/hl-test/amule/unittests/muleunit
abs_srcdir = /home/hlechner/git/hl-test/amule/unittests/muleunit
abs_top_builddir = /home/hlechner/git/hl-test/amule
abs_top_srcdir = /home/hlechner/git/hl-test/amule
ac_ct_BUILD_CC = 
ac_ct_CC = gcc
ac_ct_CXX = g++
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = x86_64-unknown-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = unknown
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-unknown-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = unknown
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/hlechner/git/hl-test/amule/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = ../..
noinst_LIBRARIES = libmuleunit.a
libmuleunit_a_SOURCES = \
	test.cpp \
	test.h \
	main.cpp \
	testcase.cpp \
	testcase.h \
	testregistry.cpp \
	testregistry.h \
	$(top_srcdir)/src/libs/common/MuleDebug.cpp \
	$(top_srcdir)/src/libs/common/StringFunctions.cpp
libmuleunit_a_CPPFLAGS = $(MULECPPFLAGS) $(WXBASE_CPPFLAGS) -I$(top_srcdir)/src/libs -DMULEUNIT
libmuleunit_a_CXXFLAGS = $(MULECXXFLAGS) $(WX_CFLAGS_ONLY) $(WX_CXXFLAGS_ONLY)
EXTRA_DIST = license.txt
MAINTAINERCLEANFILES = Makefile.in
all: all-am
.SUFFIXES:
.SUFFIXES: .cpp .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign unittests/muleunit/Makefile'>/dev/null; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign unittests/muleunit/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'>/dev/null; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe) denoiser;; \
	esac;
$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
clean-noinstLIBRARIES:
	-test -z "$(noinst_LIBRARIES)" || rm -f $(noinst_LIBRARIES)
libmuleunit.a: $(libmuleunit_a_OBJECTS) $(libmuleunit_a_DEPENDENCIES) $(EXTRA_libmuleunit_a_DEPENDENCIES) 
	echo "Building $(@F)"
	-rm -f libmuleunit.a
	$(libmuleunit_a_AR) libmuleunit.a $(libmuleunit_a_OBJECTS) $(libmuleunit_a_LIBADD)
	$(RANLIB) libmuleunit.a
mostlyclean-compile:
	-rm -f *.$(OBJEXT)
distclean-compile:
	-rm -f *.tab.c
include ./$(DEPDIR)/libmuleunit_a-MuleDebug.Po
include ./$(DEPDIR)/libmuleunit_a-StringFunctions.Po
include ./$(DEPDIR)/libmuleunit_a-main.Po
include ./$(DEPDIR)/libmuleunit_a-test.Po
include ./$(DEPDIR)/libmuleunit_a-testcase.Po
include ./$(DEPDIR)/libmuleunit_a-testregistry.Po
.cpp.o:
	echo "Compiling $(<F)"
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
.cpp.obj:
	echo "Compiling $(<F)"
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
libmuleunit_a-test.o: test.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-test.o -MD -MP -MF $(DEPDIR)/libmuleunit_a-test.Tpo -c -o libmuleunit_a-test.o `test -f 'test.cpp' || echo '$(srcdir)/'`test.cpp
	$(am__mv) $(DEPDIR)/libmuleunit_a-test.Tpo $(DEPDIR)/libmuleunit_a-test.Po
libmuleunit_a-test.obj: test.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-test.obj -MD -MP -MF $(DEPDIR)/libmuleunit_a-test.Tpo -c -o libmuleunit_a-test.obj `if test -f 'test.cpp'; then $(CYGPATH_W) 'test.cpp'; else $(CYGPATH_W) '$(srcdir)/test.cpp'; fi`
	$(am__mv) $(DEPDIR)/libmuleunit_a-test.Tpo $(DEPDIR)/libmuleunit_a-test.Po
libmuleunit_a-main.o: main.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-main.o -MD -MP -MF $(DEPDIR)/libmuleunit_a-main.Tpo -c -o libmuleunit_a-main.o `test -f 'main.cpp' || echo '$(srcdir)/'`main.cpp
	$(am__mv) $(DEPDIR)/libmuleunit_a-main.Tpo $(DEPDIR)/libmuleunit_a-main.Po
libmuleunit_a-main.obj: main.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-main.obj -MD -MP -MF $(DEPDIR)/libmuleunit_a-main.Tpo -c -o libmuleunit_a-main.obj `if test -f 'main.cpp'; then $(CYGPATH_W) 'main.cpp'; else $(CYGPATH_W) '$(srcdir)/main.cpp'; fi`
	$(am__mv) $(DEPDIR)/libmuleunit_a-main.Tpo $(DEPDIR)/libmuleunit_a-main.Po
libmuleunit_a-testcase.o: testcase.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-testcase.o -MD -MP -MF $(DEPDIR)/libmuleunit_a-testcase.Tpo -c -o libmuleunit_a-testcase.o `test -f 'testcase.cpp' || echo '$(srcdir)/'`testcase.cpp
	$(am__mv) $(DEPDIR)/libmuleunit_a-testcase.Tpo $(DEPDIR)/libmuleunit_a-testcase.Po
libmuleunit_a-testcase.obj: testcase.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-testcase.obj -MD -MP -MF $(DEPDIR)/libmuleunit_a-testcase.Tpo -c -o libmuleunit_a-testcase.obj `if test -f 'testcase.cpp'; then $(CYGPATH_W) 'testcase.cpp'; else $(CYGPATH_W) '$(srcdir)/testcase.cpp'; fi`
	$(am__mv) $(DEPDIR)/libmuleunit_a-testcase.Tpo $(DEPDIR)/libmuleunit_a-testcase.Po
libmuleunit_a-testregistry.o: testregistry.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-testregistry.o -MD -MP -MF $(DEPDIR)/libmuleunit_a-testregistry.Tpo -c -o libmuleunit_a-testregistry.o `test -f 'testregistry.cpp' || echo '$(srcdir)/'`testregistry.cpp
	$(am__mv) $(DEPDIR)/libmuleunit_a-testregistry.Tpo $(DEPDIR)/libmuleunit_a-testregistry.Po
libmuleunit_a-testregistry.obj: testregistry.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-testregistry.obj -MD -MP -MF $(DEPDIR)/libmuleunit_a-testregistry.Tpo -c -o libmuleunit_a-testregistry.obj `if test -f 'testregistry.cpp'; then $(CYGPATH_W) 'testregistry.cpp'; else $(CYGPATH_W) '$(srcdir)/testregistry.cpp'; fi`
	$(am__mv) $(DEPDIR)/libmuleunit_a-testregistry.Tpo $(DEPDIR)/libmuleunit_a-testregistry.Po
libmuleunit_a-MuleDebug.o: $(top_srcdir)/src/libs/common/MuleDebug.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-MuleDebug.o -MD -MP -MF $(DEPDIR)/libmuleunit_a-MuleDebug.Tpo -c -o libmuleunit_a-MuleDebug.o `test -f '$(top_srcdir)/src/libs/common/MuleDebug.cpp' || echo '$(srcdir)/'`$(top_srcdir)/src/libs/common/MuleDebug.cpp
	$(am__mv) $(DEPDIR)/libmuleunit_a-MuleDebug.Tpo $(DEPDIR)/libmuleunit_a-MuleDebug.Po
libmuleunit_a-MuleDebug.obj: $(top_srcdir)/src/libs/common/MuleDebug.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-MuleDebug.obj -MD -MP -MF $(DEPDIR)/libmuleunit_a-MuleDebug.Tpo -c -o libmuleunit_a-MuleDebug.obj `if test -f '$(top_srcdir)/src/libs/common/MuleDebug.cpp'; then $(CYGPATH_W) '$(top_srcdir)/src/libs/common/MuleDebug.cpp'; else $(CYGPATH_W) '$(srcdir)/$(top_srcdir)/src/libs/common/MuleDebug.cpp'; fi`
	$(am__mv) $(DEPDIR)/libmuleunit_a-MuleDebug.Tpo $(DEPDIR)/libmuleunit_a-MuleDebug.Po
libmuleunit_a-StringFunctions.o: $(top_srcdir)/src/libs/common/StringFunctions.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-StringFunctions.o -MD -MP -MF $(DEPDIR)/libmuleunit_a-StringFunctions.Tpo -c -o libmuleunit_a-StringFunctions.o `test -f '$(top_srcdir)/src/libs/common/StringFunctions.cpp' || echo '$(srcdir)/'`$(top_srcdir)/src/libs/common/StringFunctions.cpp
	$(am__mv) $(DEPDIR)/libmuleunit_a-StringFunctions.Tpo $(DEPDIR)/libmuleunit_a-StringFunctions.Po
libmuleunit_a-StringFunctions.obj: $(top_srcdir)/src/libs/common/StringFunctions.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(libmuleunit_a_CPPFLAGS) $(CPPFLAGS) $(libmuleunit_a_CXXFLAGS) $(CXXFLAGS) -MT libmuleunit_a-StringFunctions.obj -MD -MP -MF $(DEPDIR)/libmuleunit_a-StringFunctions.Tpo -c -o libmuleunit_a-StringFunctions.obj `if test -f '$(top_srcdir)/src/libs/common/StringFunctions.cpp'; then $(CYGPATH_W) '$(top_srcdir)/src/libs/common/StringFunctions.cpp'; else $(CYGPATH_W) '$(srcdir)/$(top_srcdir)/src/libs/common/StringFunctions.cpp'; fi`
	$(am__mv) $(DEPDIR)/libmuleunit_a-StringFunctions.Tpo $(DEPDIR)/libmuleunit_a-StringFunctions.Po
ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-am
TAGS: tags
tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-am
CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique
GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-am
cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i">/dev/null; \
	  else \
	    echo "$$sdir/$$i">/dev/null; \
	  fi; \
	done >> $(top_builddir)/cscope.files
distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags
distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LIBRARIES)
installdirs:
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am
install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:
clean-generic:
distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)
maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
	-test -z "$(MAINTAINERCLEANFILES)" || rm -f $(MAINTAINERCLEANFILES)
clean: clean-am
clean-am: clean-generic clean-noinstLIBRARIES mostlyclean-am
distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags
dvi: dvi-am
dvi-am:
html: html-am
html-am:
info: info-am
info-am:
install-data-am:
install-dvi: install-dvi-am
install-dvi-am:
install-exec-am:
install-html: install-html-am
install-html-am:
install-info: install-info-am
install-info-am:
install-man:
install-pdf: install-pdf-am
install-pdf-am:
install-ps: install-ps-am
install-ps-am:
installcheck-am:
maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic
mostlyclean: mostlyclean-am
mostlyclean-am: mostlyclean-compile mostlyclean-generic
pdf: pdf-am
pdf-am:
ps: ps-am
ps-am:
uninstall-am:
.MAKE: install-am install-strip
.PHONY: CTAGS GTAGS TAGS all all-am check check-am clean clean-generic \
	clean-noinstLIBRARIES cscopelist-am ctags ctags-am distclean \
	distclean-compile distclean-generic distclean-tags distdir dvi \
	dvi-am html html-am info info-am install install-am \
	install-data install-data-am install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-info install-info-am install-man install-pdf \
	install-pdf-am install-ps install-ps-am install-strip \
	installcheck installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic pdf pdf-am ps ps-am tags tags-am uninstall \
	uninstall-am
.PRECIOUS: Makefile
.NOEXPORT:
