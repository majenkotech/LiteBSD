#	@(#)Makefile	8.1 (Berkeley) 6/2/93

PROG=	ls
SRCS=	cmp.c stat_flags.c ls.c print.c util.c

CFLAGS+=-ffunction-sections -fdata-sections
LDFLAGS+=-Wl,--gc-sections

.include <bsd.prog.mk>
