# $FreeBSD$

CATEGORIES=	math lang
PKGNAMESUFFIX=	-fftw

COMMENT=	Free Pascal interface to the FFTW3 library

USES=		fpc

MASTERDIR=	${.CURDIR}/../../lang/fpc
WRKUNITDIR=	${FPCSRCDIR}/packages/${PKGNAMESUFFIX:S/-//}
EXTRACTUNITDIR=	${WRKUNITDIR}

OPTIONS_DEFINE=	FFTW3
FFTW3_DESC=	Install FFTW3 library
OPTIONS_DEFAULT=	FFTW3

FFTW3_LIB_DEPENDS=	libfftw3.so:math/fftw3

.include "${MASTERDIR}/Makefile"
