COMMENT =		console application for gcode generation

VERSION  =		4.5.0
DISTNAME =		CuraEngine-${VERSION}
PKGNAME =		curaengine-${VERSION}
CATEGORIES =		print

GH_ACCOUNT =		Ultimaker
GH_PROJECT =		CuraEngine
GH_TAGNAME =		${VERSION}

HOMEPAGE =		https://github.com/Ultimaker/CuraEngine

MAINTAINER =		Michael Killough <michaeljkillough@gmail.com>

# AGPL v3
PERMIT_PACKAGE =	Yes

MODULES =		devel/cmake

WANTLIB =		${COMPILER_LIBCXX} c m protobuf
BUILD_DEPENDS =		devel/stb
LIB_DEPENDS =		devel/libarcus devel/protobuf

COMPILER =		base-clang ports-gcc

.include <bsd.port.mk>
