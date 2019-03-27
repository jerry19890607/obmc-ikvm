AM_CPPFLAGS = -I$(top_srcdir) -I$(top_srcdir)/common
obmc_ikvm_chen=obmc-ikvm-chen
obmc_ikvm_chen_LDADD=-L../libvncserver/ -lvncserver -ldl -lresolv -lm

obmc_ikvm_chen_SOURCES= obmc-ikvm.c
#noinst_HEADERS= vncserver.h

noinst_PROGRAMS=$(obmc_ikvm_chen)
