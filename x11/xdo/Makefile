# $OpenBSD$

COMMENT =	utility to perform elementary actions on X windows

GH_ACCOUNT =	baskerville
GH_PROJECT =	xdo
GH_TAGNAME =	0.5.7

CATEGORIES =	x11

MAINTAINER =	Morten Gade Liebach <m@lieba.ch>

# BSD
PERMIT_PACKAGE = Yes

WANTLIB += c xcb xcb-ewmh xcb-icccm xcb-xtest xcb-util

USE_GMAKE =	Yes

CFLAGS +=	-I${X11BASE}/include
MAKE_ENV +=	LDFLAGS=-L${X11BASE}/lib \
		CC=${CC}

FAKE_FLAGS =	PREFIX=${TRUEPREFIX} \
		MANPREFIX=${TRUEPREFIX}/man

NO_TEST =	Yes

.include <bsd.port.mk>
