COMMENT =		library for loading 3D manufacturing format (3mf)

VERSION =		4.5.0

DISTNAME =		libSavitar-${VERSION}
PKGNAME =		libsavitar-${VERSION}
CATEGORIES =		devel

GH_ACCOUNT =		Ultimaker
GH_PROJECT =		libSavitar
GH_TAGNAME =		${VERSION}

HOMEPAGE =		https://github.com/Ultimaker/libSavitar

MAINTAINER =		Michael Killough <michaeljkillough@gmail.com>

# LGPL v3
PERMIT_PACKAGE =	Yes

SHARED_LIBS =		savitar 0.0

MODULES =		devel/cmake lang/python

MODPY_VERSION =		${MODPY_DEFAULT_VERSION_3}

FLAVORS =		python3
FLAVOR ?=

WANTLIB +=		${COMPILER_LIBCXX} ${MODPY_WANTLIB} m
BUILD_DEPENDS=		devel/py-sip${MODPY_FLAVOR}

.include <bsd.port.mk>
