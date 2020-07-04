COMMENT =		3d printing and slicing application

VERSION =		4.5.0

DISTNAME =		Cura-${VERSION}
PKGNAME =		cura-${VERSION}
CATEGORIES =		print

GH_ACCOUNT =		Ultimaker
GH_PROJECT =		Cura
GH_TAGNAME =		${VERSION}

HOMEPAGE =		https://github.com/Ultimaker/Cura

MAINTAINER =		Michael Killough <michaeljkillough@gmail.com>

# LGPL v3
PERMIT_PACKAGE =	Yes

# "make port-lib-depends-check" can help
#WANTLIB =		???

MODULES =		devel/cmake lang/python textproc/intltool

MODPY_VERSION =		${MODPY_DEFAULT_VERSION_3}

RUN_DEPENDS =   	devel/desktop-file-utils \
			misc/shared-mime-info \
			x11/gtk+3,-guic \
			x11/py-qt5${MODPY_FLAVOR} \
			x11/qt5/qtquickcontrols \
			x11/qt5/qtquickcontrols2 \
			x11/qt5/qtgraphicaleffects \
			math/py-numpy${MODPY_FLAVOR} \
			math/py-scipy${MODPY_FLAVOR} \
			geo/py-shapely${MODPY_FLAVOR} \
			security/py-cryptography${MODPY_FLAVOR} \
			www/py-requests${MODPY_FLAVOR} \
			devel/libarcus

.include <bsd.port.mk>
