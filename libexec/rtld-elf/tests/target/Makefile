# $FreeBSD$

.include <bsd.own.mk>

PACKAGE=	tests
FILESGROUPS=	TESTS
TESTSPACKAGE=	${PACKAGE}

PROG=		target
BINDIR=		${TESTSBASE}/libexec/rtld-elf

CFLAGS+=	-I${.CURDIR}/../libpythagoras

LDFLAGS+=	-L${.OBJDIR}/../libpythagoras
DPADD+=		${.OBJDIR}/../libpythagoras/libpythagoras.a
LDADD=		-lpythagoras

MAN=

.include <bsd.prog.mk>
