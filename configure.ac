AC_INIT([libavahicore], [0.1], [luz@plan44.ch], [libavahicore], [http://www.plan44.ch/])
AC_PREREQ([2.59])

AC_CONFIG_AUX_DIR(configure_aux)
AC_CONFIG_MACRO_DIR([m4])

AM_INIT_AUTOMAKE([1.10 no-define foreign subdir-objects])
AC_CONFIG_HEADERS([config.h])

AC_PROG_CC
AC_PROG_CXX

AC_CONFIG_FILES([Makefile])

# AC_CHECK_LIB(m, atan2, [], [AC_MSG_ERROR([Could not find math lib (m)])])
# #AC_CHECK_LIB(sqlite3, sqlite3_open, [], [AC_MSG_ERROR([Could not find sqlite3])])
# AC_CHECK_LIB(crypto, SHA1_Init, [], [AC_MSG_ERROR([Could not find libcrypto])])
# #AC_CHECK_LIB(ssl, SSLv2_client_method, [], [AC_MSG_ERROR([Could not find libssl])])
# AC_CHECK_LIB(rt, clock_gettime, [], [AC_MSG_ERROR([Could not find rt lib for clock_gettime])])
#
# AC_CHECK_LIB(dl, dlopen, [], [AC_MSG_ERROR([Could not find libdl])])
#
# #AC_CHECK_LIB(protobuf-c, protobuf_c_enum_descriptor_get_value_by_name, [], [AC_MSG_ERROR([Could not find libprotobuf-c])])

PKG_PROG_PKG_CONFIG

# Checks for header files.
AC_CHECK_HEADERS([arpa/inet.h fcntl.h inttypes.h limits.h netdb.h netinet/in.h stddef.h stdint.h stdlib.h string.h sys/ioctl.h sys/socket.h sys/time.h unistd.h sys/resource.h], [], [AC_MSG_ERROR([required system header not found])])

CHECK_NETLINK

LT_INIT

AC_OUTPUT
