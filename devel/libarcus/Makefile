COMMENT =		communication library for components of Ultimaker software

VERSION =		4.5.0

DISTNAME =		libArcus-${VERSION}
PKGNAME =		libarcus-${VERSION}
CATEGORIES =		devel

GH_ACCOUNT =		Ultimaker
GH_PROJECT =		libArcus
GH_TAGNAME =		${VERSION}

HOMEPAGE =		https://github.com/Ultimaker/libArcus

MAINTAINER =		Michael Killough <michaeljkillough@gmail.com>

# LGPL v3
PERMIT_PACKAGE =	Yes

SHARED_LIBS =		arcus 0.0

COMPILER =		base-clang ports-gcc

MODULES =		devel/cmake lang/python

MODPY_VERSION =		${MODPY_DEFAULT_VERSION_3}

FLAVORS =		python3
FLAVOR ?=

WANTLIB +=		${COMPILER_LIBCXX} ${MODPY_WANTLIB} m protobuf
LIB_DEPENDS =		devel/protobuf
BUILD_DEPENDS=		devel/py-sip${MODPY_FLAVOR}

.include <bsd.port.mk>
