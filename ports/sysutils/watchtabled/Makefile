# $OpenBSD$
#
# Replace ??? with appropriate values
# Remove extraneous comments before commit
# Use /usr/ports/infrastructure/bin/portcheck

COMMENT =	watch pftable and update bgp rib with changes

VERSION =	0.0

DISTNAME =	watchtabled-${VERSION}

CATEGORIES =	sysutils

HOMEPAGE =	https://github.com/mgraves00/watchtabled

MAINTAINER =	Michael Graves <michael@obtusenet.com>

# MIT
PERMIT_PACKAGE =	Yes

GH_ACCOUNT = mgraves00
GH_PROJECT = watchtabled
GH_TAGNAME = v${VERSION}

NO_BUILD =		Yes
NO_TEST =		Yes

do-install:
	${INSTALL_SCRIPT} ${WRKSRC}/watchtabled ${PREFIX}/sbin


.include <bsd.port.mk>
