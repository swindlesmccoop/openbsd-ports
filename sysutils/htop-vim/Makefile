COMMENT =			Interactive process viewer with vim-like keybindings
V =					3.2.1
DISTNAME =			htop-vim-${V}
CATEGORIES =		sysutils
REVISION =			8

HOMEPAGE =			https://github.com/KoffeinFlummi/htop-vim
MAINTAINER =		Swindles McCoop <swindlesmccoop@waifu.club>

# GPLv2
PERMIT_PACKAGE = 	Yes

GH_ACCOUNT =		KoffeinFlummi
GH_PROJECT =		htop-vim
GH_COMMIT =			830ef7144940875d9d9716e33aff8651d164026e

WANTLIB =			c curses execinfo kvm m

CONFIGURE_STYLE =	autoreconf
AUTOCONF_VERSION =	2.71
AUTOMAKE_VERSION =	1.16
AUTORECONF =		./autogen.sh
CONFIGURE_ARGS +=	--disable-unicode --disable-taskstats

.include			<bsd.port.mk>