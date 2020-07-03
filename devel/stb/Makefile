COMMENT =		single-file public domain libraries

SHA1 =			f54acd4e13430c5122cab4ca657705c84aa61b08
DISTNAME =		stb-0.0.20200703

GH_ACCOUNT =		nothings
GH_PROJECT =		stb
GH_COMMIT =		${SHA1}

CATEGORIES =		devel

HOMEPAGE =		https://github.com/nothings/stb

MAINTAINER =		Michael Killough <michaeljkillough@gmail.com>

# Public Domain & MIT
PERMIT_PACKAGE =	Yes

# Header-only library
NO_BUILD =		Yes
NO_TEST =		Yes

do-install:
	${INSTALL_DATA_DIR} ${PREFIX}/include/stb
	${INSTALL_DATA} ${WRKSRC}/*.h ${PREFIX}/include/stb

.include <bsd.port.mk>
