# Created by: Alexander Botero-Lowry <alex@foxybanana.com>
# $FreeBSD$

PORTNAME=	libofa
PORTVERSION=	0.9.3
PORTREVISION=	10
CATEGORIES=	audio

MAINTAINER=	jhale@FreeBSD.org
COMMENT=	Open Fingerprint Architecture Library

LICENSE=		APL1 GPLv2
LICENSE_COMB=		dual
LICENSE_GROUPS_APL1=	OSI
LICENSE_NAME_APL1=	Adaptive Public License version 1.0
LICENSE_FILE_APL1=	${WRKSRC}/COPYING
LICENSE_PERMS_APL1=	dist-mirror dist-sell pkg-mirror pkg-sell auto-accept

LIB_DEPENDS=	libfftw3.so:math/fftw3 \
		libexpat.so:textproc/expat2 \
		libcurl.so:ftp/curl

DEPRECATED=	MusicDNS service has been discontinued
EXPIRATION_DATE=	2017-03-01

USE_GITHUB=	yes
GH_ACCOUNT=	tanob
GH_TAGNAME=	b75e45e

USES=		dos2unix libtool localbase pathfix
GNU_CONFIGURE=	yes
USE_LDCONFIG=	yes
INSTALL_TARGET=	install-strip

.include <bsd.port.mk>
