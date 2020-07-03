COMMENT =		python package for building 3D printing applications

MODPY_EGG_VERSION =	4.5.0

DISTNAME =		Uranium-${MODPY_EGG_VERSION}
PKGNAME =		py-uranium-${MODPY_EGG_VERSION}
CATEGORIES =		x11

GH_ACCOUNT =		Ultimaker
GH_PROJECT =		Uranium
GH_TAGNAME =		${VERSION}

HOMEPAGE =		https://github.com/Ultimaker/Uranium

MAINTAINER =		Michael Killough <michaeljkillough@gmail.com>

# LGPL v3
PERMIT_PACKAGE =	Yes

MODULES =		devel/cmake lang/python textproc/intltool

MODPY_VERSION =		${MODPY_DEFAULT_VERSION_3}

FLAVORS =		python3
FLAVOR ?=

RUN_DEPENDS =		x11/py-qt5${MODPY_FLAVOR} \
			x11/qt5/qtquickcontrols \
			x11/qt5/qtquickcontrols2 \
			x11/qt5/qtgraphicaleffects \
			math/py-numpy${MODPY_FLAVOR} \
			math/py-scipy${MODPY_FLAVOR} \
			geo/py-shapely${MODPY_FLAVOR} \
			security/py-cryptography${MODPY_FLAVOR} \
			devel/libarcus

.include <bsd.port.mk>
