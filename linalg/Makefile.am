noinst_LTLIBRARIES = libgsllinalg.la 

pkginclude_HEADERS = gsl_linalg.h

AM_CPPFLAGS = -I$(top_srcdir)

libgsllinalg_la_SOURCES = cod.c condest.c invtri.c invtri_complex.c multiply.c exponential.c tridiag.c tridiag.h lu.c luc.c hh.c qr.c qrpt.c qr_tr.c rqr.c lq.c ptlq.c svd.c householder.c householdercomplex.c hessenberg.c hesstri.c cholesky.c choleskyc.c mcholesky.c pcholesky.c cholesky_band.c ldlt.c ldlt_band.c symmtd.c hermtd.c bidiag.c balance.c balancemat.c inline.c trimult.c trimult_complex.c

noinst_HEADERS = apply_givens.c cholesky_common.c recurse.h svdstep.c tridiag.h test_cholesky.c test_choleskyc.c test_cod.c test_common.c test_ldlt.c test_lu.c test_luc.c test_lq.c test_qr.c test_tri.c

TESTS = $(check_PROGRAMS)

check_PROGRAMS = test

test_SOURCES = test.c
test_LDADD = libgsllinalg.la ../blas/libgslblas.la ../cblas/libgslcblas.la ../permutation/libgslpermutation.la ../matrix/libgslmatrix.la ../vector/libgslvector.la ../block/libgslblock.la ../complex/libgslcomplex.la ../ieee-utils/libgslieeeutils.la ../err/libgslerr.la ../test/libgsltest.la ../sys/libgslsys.la ../utils/libutils.la ../rng/libgslrng.la
