bin_PROGRAMS = udpreplay

udpreplay_SOURCES = \
	udpReplay.c \
	udpCallback.c \
	udpCallback.h

AM_CPPFLAGS = -I.
AM_CFLAGS = $(PCAP_CFLAGS) -Wall
LDADD = $(PCAP_LIBS)
