bin_PROGRAMS = \
	iwpan

iwpan_SOURCES = \
	iwpan.c \
	iwpan.h \
	sections.c \
	info.c \
	interface.c \
	phy.c \
	mac.c \
	nl_extras.h \
	nl802154.h

iwpan_CFLAGS = $(AM_CFLAGS) $(LIBNL3_CFLAGS)
iwpan_LDADD = $(LIBNL3_LIBS)
