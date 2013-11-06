PJSIP (OpenSSL)
=====

PJSIP 2.1

This is a fork of the 2.1 release of PJSIP.  This fork pulls in the libsrtp code from the feature-openssl branch,
which provides support for AES-NI.  This fork also adds support for AES 192/256 and AES-GCM mode.

When building this code, the build host requires the OpenSSL 1.0.1 devel package to be installed.  Other than this
new dependency, the build procedure has not changed:

./configure
make dep
make


