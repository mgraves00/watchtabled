# $OpenBSD: Makefile.template,v 1.91 2021/11/09 13:43:15 kn Exp $
#
# Replace ??? with appropriate values
# Remove extraneous comments before commit
# Use /usr/ports/infrastructure/bin/portcheck

COMMENT =	watch pftable and update bgp rib with changes

VERSION = 0.1

DISTNAME =	watchtabled

CATEGORIES =	sysutils

HOMEPAGE =	https://github.com/mgraves00/misc-scripts/tree/master/watch-table

MAINTAINER =	Michael Graves <michael@obtusenet.com>

# MIT
PERMIT_PACKAGE =	Yes
PERMIT_DISTFILES =	Yes

GH_ACCOUNT = mgraves00
GH_PROJECT = misc-scripts/watch-table
GH_TAGNAME = v${VERSION}

MASTER_SITES =		${MASTER_SITE_GITHUB:=mgraves00/misc-scripts/watch-table/}

NO_BUILD =		Yes
NO_TEST =		Yes

do-install:
	${INSTALL_SCRIPT} ${WRKSRC}/watchtabled ${PREFIX}/sbin


.include <bsd.port.mk>
