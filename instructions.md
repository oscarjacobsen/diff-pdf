

1. Instasll MSYS2


2. Input log with MSYS2


oscjac@NOHGS13RBX64 UCRT64 ~
$ cd pdf-diff
-bash: cd: pdf-diff: No such file or directory

oscjac@NOHGS13RBX64 UCRT64 ~
$ cd diff-pdf
-bash: cd: diff-pdf: No such file or directory

oscjac@NOHGS13RBX64 UCRT64 ~
$ dir

oscjac@NOHGS13RBX64 UCRT64 ~
$ cd

oscjac@NOHGS13RBX64 UCRT64 ~
$ dir()
> q
-bash: syntax error near unexpected token `q'

oscjac@NOHGS13RBX64 UCRT64 ~
$

oscjac@NOHGS13RBX64 UCRT64 ~
$ cd C:/Users/oscjac/diff-pdf

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ ./bootstrap
Setting up build system for diff-pdf:
 - aclocal
./bootstrap: line 50: aclocal: command not found
Automatic build files setup failed!

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ ^C

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ pacman -S autotools
# or more specifically:
pacman -S automake autoconf
resolving dependencies...
looking for conflicting packages...

Packages (21) autoconf-wrapper-20250528-1  autoconf2.13-2.13-6  autoconf2.69-2.69-4
              autoconf2.71-2.71-4  autoconf2.72-2.72-3  automake-wrapper-20250528-1
              automake1.11-1.11.6-6  automake1.12-1.12.6-6  automake1.13-1.13.4-7
              automake1.14-1.14.1-6  automake1.15-1.15.1-4  automake1.16-1.16.5-1
              automake1.17-1.17-1  automake1.18-1.18-1  diffutils-3.12-1  libltdl-2.5.4-3
              libtool-2.5.4-3  m4-1.4.19-2  make-4.4.1-2  pkgconf-2.5.1-1  autotools-2022.01.16-2

Total Download Size:    7.08 MiB
Total Installed Size:  24.76 MiB

:: Proceed with installation? [Y/n] y
:: Retrieving packages...
 automake1.18-1.18-1-any         544.0 KiB  1122 KiB/s 00:00 [###############################] 100%
 automake1.16-1.16.5-1-any       526.3 KiB  1028 KiB/s 00:01 [###############################] 100%
 autoconf2.72-2.72-3-any         725.2 KiB  1307 KiB/s 00:01 [###############################] 100%
 automake1.15-1.15.1-4-any       513.4 KiB   733 KiB/s 00:01 [###############################] 100%
 automake1.17-1.17-1-any         535.0 KiB   686 KiB/s 00:01 [###############################] 100%
 automake1.14-1.14.1-6-any       503.1 KiB  2.11 MiB/s 00:00 [###############################] 100%
 make-4.4.1-2-x86_64             507.6 KiB  1459 KiB/s 00:00 [###############################] 100%
 automake1.12-1.12.6-6-any       503.1 KiB  1409 KiB/s 00:00 [###############################] 100%
 automake1.11-1.11.6-6-any       490.2 KiB  2.36 MiB/s 00:00 [###############################] 100%
 libtool-2.5.4-3-x86_64          405.7 KiB  2.39 MiB/s 00:00 [###############################] 100%
 diffutils-3.12-1-x86_64         385.3 KiB  2.07 MiB/s 00:00 [###############################] 100%
 automake1.13-1.13.4-7-any       501.5 KiB  1235 KiB/s 00:00 [###############################] 100%
 autoconf2.71-2.71-4-any         327.3 KiB  1597 KiB/s 00:00 [###############################] 100%
 autoconf2.13-2.13-6-any         137.4 KiB   554 KiB/s 00:00 [###############################] 100%
 pkgconf-2.5.1-1-x86_64           74.6 KiB   320 KiB/s 00:00 [###############################] 100%
 libltdl-2.5.4-3-x86_64           40.7 KiB   275 KiB/s 00:00 [###############################] 100%
 autoconf2.69-2.69-4-any         284.6 KiB   830 KiB/s 00:00 [###############################] 100%
 autoconf-wrapper-20250528-...     4.9 KiB  51.3 KiB/s 00:00 [###############################] 100%
 automake-wrapper-20250528-...     4.4 KiB  50.1 KiB/s 00:00 [###############################] 100%
 autotools-2022.01.16-2-any        2.5 KiB  12.2 KiB/s 00:00 [###############################] 100%
 m4-1.4.19-2-x86_64              238.1 KiB   354 KiB/s 00:01 [###############################] 100%
 Total (21/21)                     7.1 MiB  3.50 MiB/s 00:02 [###############################] 100%
(21/21) checking keys in keyring                             [###############################] 100%
(21/21) checking package integrity                           [###############################] 100%
(21/21) loading package files                                [###############################] 100%
(21/21) checking for file conflicts                          [###############################] 100%
(21/21) checking available disk space                        [###############################] 100%
:: Processing package changes...
( 1/21) installing m4                                        [###############################] 100%
( 2/21) installing diffutils                                 [###############################] 100%
( 3/21) installing autoconf2.72                              [###############################] 100%
( 4/21) installing autoconf2.71                              [###############################] 100%
( 5/21) installing autoconf2.69                              [###############################] 100%
( 6/21) installing autoconf2.13                              [###############################] 100%
( 7/21) installing autoconf-wrapper                          [###############################] 100%
( 8/21) installing automake1.11                              [###############################] 100%
( 9/21) installing automake1.12                              [###############################] 100%
(10/21) installing automake1.13                              [###############################] 100%
(11/21) installing automake1.14                              [###############################] 100%
(12/21) installing automake1.15                              [###############################] 100%
(13/21) installing automake1.16                              [###############################] 100%
(14/21) installing automake1.17                              [###############################] 100%
(15/21) installing automake1.18                              [###############################] 100%
(16/21) installing automake-wrapper                          [###############################] 100%
(17/21) installing libltdl                                   [###############################] 100%
(18/21) installing libtool                                   [###############################] 100%
(19/21) installing make                                      [###############################] 100%
(20/21) installing pkgconf                                   [###############################] 100%
(21/21) installing autotools                                 [###############################] 100%
:: Running post-transaction hooks...
(1/1) Updating the info directory file...
warning: automake-wrapper-20250528-1 is up to date -- reinstalling
warning: autoconf-wrapper-20250528-1 is up to date -- reinstalling
resolving dependencies...
looking for conflicting packages...

Packages (2) autoconf-wrapper-20250528-1  automake-wrapper-20250528-1

Total Installed Size:  0.05 MiB
Net Upgrade Size:      0.00 MiB

:: Proceed with installation? [Y/n] y
(2/2) checking keys in keyring                               [###############################] 100%
(2/2) checking package integrity                             [###############################] 100%
(2/2) loading package files                                  [###############################] 100%
(2/2) checking for file conflicts                            [###############################] 100%
(2/2) checking available disk space                          [###############################] 100%
:: Processing package changes...
(1/2) reinstalling automake-wrapper                          [###############################] 100%
(2/2) reinstalling autoconf-wrapper                          [###############################] 100%

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$  ./bootstrap
Setting up build system for diff-pdf:
 - aclocal
 - autoconf
 - automake
configure.ac:33: installing 'admin/config.guess'
configure.ac:33: installing 'admin/config.sub'
configure.ac:26: installing 'admin/install-sh'
configure.ac:26: installing 'admin/missing'
Makefile.am: installing 'admin/depcomp'
Build setup successful, type "./configure" to configure diff-pdf now.

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ ./configure
configure: loading site script /etc/config.site
checking for a BSD-compatible install... /usr/bin/install -c
checking whether sleep supports fractional seconds... yes
checking filesystem timestamp resolution... 0.01
checking whether build environment is sane... yes
checking for a race-free mkdir -p... /usr/bin/mkdir -p
checking for gawk... gawk
checking whether make sets $(MAKE)... yes
checking whether make supports nested variables... yes
checking xargs -n works... yes
checking whether UID '1281418' is supported by ustar format... yes
checking whether GID '1049089' is supported by ustar format... yes
checking how to create a ustar tar archive... gnutar
checking whether to enable maintainer-specific portions of Makefiles... no
checking build system type... x86_64-w64-mingw32
checking host system type... x86_64-w64-mingw32
checking for g++... no
checking for c++... no
checking for gpp... no
checking for aCC... no
checking for CC... no
checking for cxx... no
checking for cc++... no
checking for cl.exe... no
checking for FCC... no
checking for KCC... no
checking for RCC... no
checking for xlC_r... no
checking for xlC... no
checking for clang++... no
checking whether the C++ compiler works... no
configure: error: in '/c/Users/oscjac/diff-pdf':
configure: error: C++ compiler cannot create executables
See 'config.log' for more details

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ # Install C++ compiler for UCRT64
pacman -S mingw-w64-ucrt-x86_64-gcc

# Or install the complete toolchain
pacman -S mingw-w64-ucrt-x86_64-toolchain
resolving dependencies...
looking for conflicting packages...

Packages (16) mingw-w64-ucrt-x86_64-binutils-2.44-4
              mingw-w64-ucrt-x86_64-crt-git-13.0.0.r57.gc1a7f831b-1
              mingw-w64-ucrt-x86_64-gcc-libs-15.1.0-6  mingw-w64-ucrt-x86_64-gettext-runtime-0.25-1
              mingw-w64-ucrt-x86_64-gmp-6.3.0-2
              mingw-w64-ucrt-x86_64-headers-git-13.0.0.r57.gc1a7f831b-1
              mingw-w64-ucrt-x86_64-isl-0.27-1  mingw-w64-ucrt-x86_64-libiconv-1.18-1
              mingw-w64-ucrt-x86_64-libwinpthread-13.0.0.r57.gc1a7f831b-1
              mingw-w64-ucrt-x86_64-mpc-1.3.1-2  mingw-w64-ucrt-x86_64-mpfr-4.2.2-1
              mingw-w64-ucrt-x86_64-windows-default-manifest-6.4-4
              mingw-w64-ucrt-x86_64-winpthreads-13.0.0.r57.gc1a7f831b-1
              mingw-w64-ucrt-x86_64-zlib-1.3.1-1  mingw-w64-ucrt-x86_64-zstd-1.5.7-1
              mingw-w64-ucrt-x86_64-gcc-15.1.0-6

Total Download Size:    69.02 MiB
Total Installed Size:  540.75 MiB

:: Proceed with installation? [Y/n] y
:: Retrieving packages...
 mingw-w64-ucrt-x86_64-isl-...  1453.5 KiB  3.17 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-binu...     6.0 MiB  6.51 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-gcc-...  1043.4 KiB  2.17 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-head...     6.4 MiB  6.26 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-libi...   725.4 KiB  1612 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-gcc-...    46.5 MiB  29.8 MiB/s 00:02 [###############################] 100%
 mingw-w64-ucrt-x86_64-gmp-...   578.5 KiB   854 KiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-zstd...   642.3 KiB   918 KiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-mpfr...   541.9 KiB  1622 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-mpc-...   128.3 KiB  1296 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-zlib...    92.1 KiB   509 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-winp...    41.9 KiB   349 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-libw...    29.5 KiB   268 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-gett...   333.5 KiB   531 KiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-wind...     3.0 KiB  19.1 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-crt-...     4.6 MiB  1992 KiB/s 00:02 [###############################] 100%
 Total (16/16)                    69.0 MiB  27.3 MiB/s 00:03 [###############################] 100%
(16/16) checking keys in keyring                             [###############################] 100%
(16/16) checking package integrity                           [###############################] 100%
(16/16) loading package files                                [###############################] 100%
(16/16) checking for file conflicts                          [###############################] 100%
(16/16) checking available disk space                        [###############################] 100%
:: Processing package changes...
( 1/16) installing mingw-w64-ucrt-x86_64-libwinpthread       [###############################] 100%
( 2/16) installing mingw-w64-ucrt-x86_64-gcc-libs            [###############################] 100%
( 3/16) installing mingw-w64-ucrt-x86_64-libiconv            [###############################] 100%
( 4/16) installing mingw-w64-ucrt-x86_64-gettext-runtime     [###############################] 100%
( 5/16) installing mingw-w64-ucrt-x86_64-zlib                [###############################] 100%
( 6/16) installing mingw-w64-ucrt-x86_64-zstd                [###############################] 100%
( 7/16) installing mingw-w64-ucrt-x86_64-binutils            [###############################] 100%
( 8/16) installing mingw-w64-ucrt-x86_64-headers-git         [###############################] 100%
( 9/16) installing mingw-w64-ucrt-x86_64-crt-git             [###############################] 100%
(10/16) installing mingw-w64-ucrt-x86_64-gmp                 [###############################] 100%
(11/16) installing mingw-w64-ucrt-x86_64-isl                 [###############################] 100%
(12/16) installing mingw-w64-ucrt-x86_64-mpfr                [###############################] 100%
(13/16) installing mingw-w64-ucrt-x86_64-mpc                 [###############################] 100%
(14/16) installing mingw-w64-ucrt-x86_64-windows-default...  [###############################] 100%
(15/16) installing mingw-w64-ucrt-x86_64-winpthreads         [###############################] 100%
(16/16) installing mingw-w64-ucrt-x86_64-gcc                 [###############################] 100%
:: There are 13 members in group mingw-w64-ucrt-x86_64-toolchain:
:: Repository ucrt64
   1) mingw-w64-ucrt-x86_64-binutils  2) mingw-w64-ucrt-x86_64-crt-git
   3) mingw-w64-ucrt-x86_64-gcc  4) mingw-w64-ucrt-x86_64-gdb
   5) mingw-w64-ucrt-x86_64-gdb-multiarch  6) mingw-w64-ucrt-x86_64-headers-git
   7) mingw-w64-ucrt-x86_64-libmangle-git  8) mingw-w64-ucrt-x86_64-libwinpthread
   9) mingw-w64-ucrt-x86_64-make  10) mingw-w64-ucrt-x86_64-pkgconf
   11) mingw-w64-ucrt-x86_64-tools-git  12) mingw-w64-ucrt-x86_64-winpthreads
   13) mingw-w64-ucrt-x86_64-winstorecompat-git

Enter a selection (default=all):
warning: mingw-w64-ucrt-x86_64-binutils-2.44-4 is up to date -- reinstalling
warning: mingw-w64-ucrt-x86_64-crt-git-13.0.0.r57.gc1a7f831b-1 is up to date -- reinstalling
warning: mingw-w64-ucrt-x86_64-gcc-15.1.0-6 is up to date -- reinstalling
warning: mingw-w64-ucrt-x86_64-headers-git-13.0.0.r57.gc1a7f831b-1 is up to date -- reinstalling
warning: mingw-w64-ucrt-x86_64-libwinpthread-13.0.0.r57.gc1a7f831b-1 is up to date -- reinstalling
warning: mingw-w64-ucrt-x86_64-winpthreads-13.0.0.r57.gc1a7f831b-1 is up to date -- reinstalling
resolving dependencies...
looking for conflicting packages...

Packages (30) mingw-w64-ucrt-x86_64-bzip2-1.0.8-3  mingw-w64-ucrt-x86_64-expat-2.7.1-2
              mingw-w64-ucrt-x86_64-libffi-3.5.1-1  mingw-w64-ucrt-x86_64-libsystre-1.0.2-1
              mingw-w64-ucrt-x86_64-libtre-0.9.0-1  mingw-w64-ucrt-x86_64-mpdecimal-4.0.1-1
              mingw-w64-ucrt-x86_64-ncurses-6.5.20241228-3  mingw-w64-ucrt-x86_64-openssl-3.5.1-1
              mingw-w64-ucrt-x86_64-python-3.12.11-1  mingw-w64-ucrt-x86_64-readline-8.2.013-1
              mingw-w64-ucrt-x86_64-sqlite3-3.50.2-1  mingw-w64-ucrt-x86_64-tcl-8.6.16-1
              mingw-w64-ucrt-x86_64-termcap-1.3.1-7  mingw-w64-ucrt-x86_64-tk-8.6.16-1
              mingw-w64-ucrt-x86_64-tzdata-2025b-1  mingw-w64-ucrt-x86_64-xxhash-0.8.3-1
              mingw-w64-ucrt-x86_64-xz-5.8.1-2  mingw-w64-ucrt-x86_64-binutils-2.44-4
              mingw-w64-ucrt-x86_64-crt-git-13.0.0.r57.gc1a7f831b-1
              mingw-w64-ucrt-x86_64-gcc-15.1.0-6  mingw-w64-ucrt-x86_64-gdb-16.3-1
              mingw-w64-ucrt-x86_64-gdb-multiarch-16.3-1
              mingw-w64-ucrt-x86_64-headers-git-13.0.0.r57.gc1a7f831b-1
              mingw-w64-ucrt-x86_64-libmangle-git-13.0.0.r57.gc1a7f831b-1
              mingw-w64-ucrt-x86_64-libwinpthread-13.0.0.r57.gc1a7f831b-1
              mingw-w64-ucrt-x86_64-make-4.4.1-3  mingw-w64-ucrt-x86_64-pkgconf-1~2.5.1-1
              mingw-w64-ucrt-x86_64-tools-git-13.0.0.r57.gc1a7f831b-1
              mingw-w64-ucrt-x86_64-winpthreads-13.0.0.r57.gc1a7f831b-1
              mingw-w64-ucrt-x86_64-winstorecompat-git-13.0.0.r57.gc1a7f831b-1

Total Download Size:    53.36 MiB
Total Installed Size:  862.65 MiB
Net Upgrade Size:      351.71 MiB

:: Proceed with installation? [Y/n] y
:: Retrieving packages...
 mingw-w64-ucrt-x86_64-gdb-...     4.6 MiB  8.00 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-tcl-...     2.7 MiB  2.88 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-open...     7.8 MiB  6.23 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-gdb-...     6.3 MiB  4.85 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-sqli...     2.3 MiB  3.18 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-tk-8...     2.0 MiB  4.96 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-pyth...    23.2 MiB  13.9 MiB/s 00:02 [###############################] 100%
 mingw-w64-ucrt-x86_64-read...   412.4 KiB  1370 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-ncur...  1747.6 KiB  3.73 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-xz-5...   866.4 KiB  1824 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-expa...   164.9 KiB  1472 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-make...   138.8 KiB  1051 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-mpde...   154.9 KiB   422 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-pkgc...    99.6 KiB  1200 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-tool...   323.1 KiB   464 KiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-tzda...   197.0 KiB   301 KiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-libt...    79.0 KiB   523 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-bzip...    76.5 KiB   517 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-xxha...   118.7 KiB   198 KiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-libf...    43.1 KiB   263 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-term...    27.3 KiB   165 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-wins...    25.0 KiB   162 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-libm...    22.9 KiB   169 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-libs...     9.7 KiB  47.8 KiB/s 00:00 [###############################] 100%
 Total (24/24)                    53.4 MiB  17.1 MiB/s 00:03 [###############################] 100%
(30/30) checking keys in keyring                             [###############################] 100%
(30/30) checking package integrity                           [###############################] 100%
(30/30) loading package files                                [###############################] 100%
(30/30) checking for file conflicts                          [###############################] 100%
(30/30) checking available disk space                        [###############################] 100%
:: Processing package changes...
( 1/30) reinstalling mingw-w64-ucrt-x86_64-libwinpthread     [###############################] 100%
( 2/30) reinstalling mingw-w64-ucrt-x86_64-binutils          [###############################] 100%
( 3/30) reinstalling mingw-w64-ucrt-x86_64-headers-git       [###############################] 100%
( 4/30) reinstalling mingw-w64-ucrt-x86_64-crt-git           [###############################] 100%
( 5/30) reinstalling mingw-w64-ucrt-x86_64-winpthreads       [###############################] 100%
( 6/30) reinstalling mingw-w64-ucrt-x86_64-gcc               [###############################] 100%
( 7/30) installing mingw-w64-ucrt-x86_64-expat               [###############################] 100%
( 8/30) installing mingw-w64-ucrt-x86_64-libtre              [###############################] 100%
( 9/30) installing mingw-w64-ucrt-x86_64-libsystre           [###############################] 100%
(10/30) installing mingw-w64-ucrt-x86_64-ncurses             [###############################] 100%
(11/30) installing mingw-w64-ucrt-x86_64-bzip2               [###############################] 100%
(12/30) installing mingw-w64-ucrt-x86_64-libffi              [###############################] 100%
(13/30) installing mingw-w64-ucrt-x86_64-mpdecimal           [###############################] 100%
(14/30) installing mingw-w64-ucrt-x86_64-openssl             [###############################] 100%
Optional dependencies for mingw-w64-ucrt-x86_64-openssl
    mingw-w64-ucrt-x86_64-ca-certificates
(15/30) installing mingw-w64-ucrt-x86_64-termcap             [###############################] 100%
(16/30) installing mingw-w64-ucrt-x86_64-readline            [###############################] 100%
(17/30) installing mingw-w64-ucrt-x86_64-sqlite3             [###############################] 100%
Optional dependencies for mingw-w64-ucrt-x86_64-sqlite3
    mingw-w64-ucrt-x86_64-tcl: for sqlite3_analyzer [pending]
(18/30) installing mingw-w64-ucrt-x86_64-tcl                 [###############################] 100%
(19/30) installing mingw-w64-ucrt-x86_64-tk                  [###############################] 100%
(20/30) installing mingw-w64-ucrt-x86_64-xz                  [###############################] 100%
(21/30) installing mingw-w64-ucrt-x86_64-tzdata              [###############################] 100%
(22/30) installing mingw-w64-ucrt-x86_64-python              [###############################] 100%
(23/30) installing mingw-w64-ucrt-x86_64-xxhash              [###############################] 100%
(24/30) installing mingw-w64-ucrt-x86_64-gdb                 [###############################] 100%
Optional dependencies for mingw-w64-ucrt-x86_64-gdb
    mingw-w64-ucrt-x86_64-python-pygments: for syntax highlighting
(25/30) installing mingw-w64-ucrt-x86_64-gdb-multiarch       [###############################] 100%
Optional dependencies for mingw-w64-ucrt-x86_64-gdb-multiarch
    mingw-w64-ucrt-x86_64-python-pygments: for syntax highlighting
(26/30) installing mingw-w64-ucrt-x86_64-libmangle-git       [###############################] 100%
(27/30) installing mingw-w64-ucrt-x86_64-make                [###############################] 100%
(28/30) installing mingw-w64-ucrt-x86_64-pkgconf             [###############################] 100%
(29/30) installing mingw-w64-ucrt-x86_64-tools-git           [###############################] 100%
(30/30) installing mingw-w64-ucrt-x86_64-winstorecompat-git  [###############################] 100%

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ # Install build tools
pacman -S make automake autoconf pkg-config

# Install diff-pdf dependencies for UCRT64
pacman -S mingw-w64-ucrt-x86_64-wxwidgets3.2-msw
pacman -S mingw-w64-ucrt-x86_64-poppler
pacman -S mingw-w64-ucrt-x86_64-cairo
pacman -S mingw-w64-ucrt-x86_64-pkg-config
warning: make-4.4.1-2 is up to date -- reinstalling
warning: automake-wrapper-20250528-1 is up to date -- reinstalling
warning: autoconf-wrapper-20250528-1 is up to date -- reinstalling
warning: pkgconf-2.5.1-1 is up to date -- reinstalling
resolving dependencies...
looking for conflicting packages...

Packages (4) autoconf-wrapper-20250528-1  automake-wrapper-20250528-1  make-4.4.1-2
             pkgconf-2.5.1-1

Total Installed Size:  2.00 MiB
Net Upgrade Size:      0.00 MiB

:: Proceed with installation? [Y/n] y
(4/4) checking keys in keyring                               [###############################] 100%
(4/4) checking package integrity                             [###############################] 100%
(4/4) loading package files                                  [###############################] 100%
(4/4) checking for file conflicts                            [###############################] 100%
(4/4) checking available disk space                          [###############################] 100%
:: Processing package changes...
(1/4) reinstalling make                                      [###############################] 100%
(2/4) reinstalling automake-wrapper                          [###############################] 100%
(3/4) reinstalling autoconf-wrapper                          [###############################] 100%
(4/4) reinstalling pkgconf                                   [###############################] 100%
:: Running post-transaction hooks...
(1/1) Updating the info directory file...
resolving dependencies...
looking for conflicting packages...
warning: dependency cycle detected:
warning: mingw-w64-ucrt-x86_64-libwebp will be installed before its mingw-w64-ucrt-x86_64-libtiff dependency

Packages (29) mingw-w64-ucrt-x86_64-brotli-1.1.0-5  mingw-w64-ucrt-x86_64-c-ares-1.34.5-1
              mingw-w64-ucrt-x86_64-ca-certificates-20241223-1  mingw-w64-ucrt-x86_64-curl-8.14.1-1
              mingw-w64-ucrt-x86_64-giflib-5.2.2-1  mingw-w64-ucrt-x86_64-gnutls-3.8.9-4
              mingw-w64-ucrt-x86_64-jbigkit-2.1-5  mingw-w64-ucrt-x86_64-lerc-4.0.0-1
              mingw-w64-ucrt-x86_64-libdeflate-1.24-1  mingw-w64-ucrt-x86_64-libidn2-2.3.8-2
              mingw-w64-ucrt-x86_64-libjpeg-turbo-3.1.1-1  mingw-w64-ucrt-x86_64-libpng-1.6.49-1
              mingw-w64-ucrt-x86_64-libpsl-0.21.5-3  mingw-w64-ucrt-x86_64-libssh2-1.11.1-1
              mingw-w64-ucrt-x86_64-libtasn1-4.20.0-1  mingw-w64-ucrt-x86_64-libtiff-4.7.0-1
              mingw-w64-ucrt-x86_64-libunistring-1.3-1  mingw-w64-ucrt-x86_64-libwebp-1.5.0-1
              mingw-w64-ucrt-x86_64-nettle-3.10.2-1  mingw-w64-ucrt-x86_64-nghttp2-1.66.0-1
              mingw-w64-ucrt-x86_64-nghttp3-1.10.1-1  mingw-w64-ucrt-x86_64-ngtcp2-1.13.0-2
              mingw-w64-ucrt-x86_64-p11-kit-0.25.5-1  mingw-w64-ucrt-x86_64-pcre2-10.45-1
              mingw-w64-ucrt-x86_64-wineditline-2.208-1
              mingw-w64-ucrt-x86_64-wxwidgets3.2-common-3.2.8.1-4
              mingw-w64-ucrt-x86_64-wxwidgets3.2-common-libs-3.2.8.1-4
              mingw-w64-ucrt-x86_64-wxwidgets3.2-msw-libs-3.2.8.1-4
              mingw-w64-ucrt-x86_64-wxwidgets3.2-msw-3.2.8.1-4

Total Download Size:    38.06 MiB
Total Installed Size:  272.63 MiB

:: Proceed with installation? [Y/n] y
:: Retrieving packages...
 mingw-w64-ucrt-x86_64-pcre...  1353.7 KiB  2.35 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-curl...  1552.2 KiB  2.45 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-wxwi...  1122.1 KiB  7.16 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-gnut...     2.2 MiB  2.51 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-libt...   668.5 KiB  6.80 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-wxwi...     5.1 MiB  4.97 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-libu...   833.5 KiB  2.05 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-libw...   603.7 KiB  5.31 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-p11-...   423.3 KiB  2.58 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-brot...   419.5 KiB  2.54 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-ca-c...   395.1 KiB  4.49 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-wxwi...    19.7 MiB  12.3 MiB/s 00:02 [###############################] 100%
 mingw-w64-ucrt-x86_64-c-ar...   308.7 KiB  1600 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-libj...   644.5 KiB   861 KiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-nett...   563.5 KiB   808 KiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-libs...   308.2 KiB  1684 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-ngtc...   268.8 KiB  2.19 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-lerc...   284.6 KiB  1259 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-nght...   193.9 KiB  1657 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-libt...   195.6 KiB   869 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-libp...   392.0 KiB   578 KiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-libi...   169.7 KiB  1402 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-libp...    93.5 KiB   725 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-nght...   123.8 KiB   378 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-gifl...   118.7 KiB   594 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-jbig...    73.2 KiB   391 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-libd...    91.0 KiB   351 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-wine...    59.7 KiB   355 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-wxwi...    29.5 KiB   107 KiB/s 00:00 [###############################] 100%
 Total (29/29)                    38.1 MiB  13.4 MiB/s 00:03 [###############################] 100%
(29/29) checking keys in keyring                             [###############################] 100%
(29/29) checking package integrity                           [###############################] 100%
(29/29) loading package files                                [###############################] 100%
(29/29) checking for file conflicts                          [###############################] 100%
(29/29) checking available disk space                        [###############################] 100%
:: Processing package changes...
( 1/29) installing mingw-w64-ucrt-x86_64-libjpeg-turbo       [###############################] 100%
( 2/29) installing mingw-w64-ucrt-x86_64-libpng              [###############################] 100%
( 3/29) installing mingw-w64-ucrt-x86_64-jbigkit             [###############################] 100%
( 4/29) installing mingw-w64-ucrt-x86_64-lerc                [###############################] 100%
( 5/29) installing mingw-w64-ucrt-x86_64-libdeflate          [###############################] 100%
( 6/29) installing mingw-w64-ucrt-x86_64-giflib              [###############################] 100%
( 7/29) installing mingw-w64-ucrt-x86_64-libwebp             [###############################] 100%
( 8/29) installing mingw-w64-ucrt-x86_64-libtiff             [###############################] 100%
( 9/29) installing mingw-w64-ucrt-x86_64-c-ares              [###############################] 100%
(10/29) installing mingw-w64-ucrt-x86_64-brotli              [###############################] 100%
(11/29) installing mingw-w64-ucrt-x86_64-libunistring        [###############################] 100%
(12/29) installing mingw-w64-ucrt-x86_64-libidn2             [###############################] 100%
(13/29) installing mingw-w64-ucrt-x86_64-libpsl              [###############################] 100%
(14/29) installing mingw-w64-ucrt-x86_64-libtasn1            [###############################] 100%
(15/29) installing mingw-w64-ucrt-x86_64-p11-kit             [###############################] 100%
(16/29) installing mingw-w64-ucrt-x86_64-ca-certificates     [###############################] 100%
(17/29) installing mingw-w64-ucrt-x86_64-libssh2             [###############################] 100%
(18/29) installing mingw-w64-ucrt-x86_64-nghttp2             [###############################] 100%
(19/29) installing mingw-w64-ucrt-x86_64-nettle              [###############################] 100%
(20/29) installing mingw-w64-ucrt-x86_64-gnutls              [###############################] 100%
(21/29) installing mingw-w64-ucrt-x86_64-ngtcp2              [###############################] 100%
(22/29) installing mingw-w64-ucrt-x86_64-nghttp3             [###############################] 100%
(23/29) installing mingw-w64-ucrt-x86_64-curl                [###############################] 100%
(24/29) installing mingw-w64-ucrt-x86_64-wineditline         [###############################] 100%
(25/29) installing mingw-w64-ucrt-x86_64-pcre2               [###############################] 100%
(26/29) installing mingw-w64-ucrt-x86_64-wxwidgets3.2-co...  [###############################] 100%
(27/29) installing mingw-w64-ucrt-x86_64-wxwidgets3.2-ms...  [###############################] 100%
(28/29) installing mingw-w64-ucrt-x86_64-wxwidgets3.2-common [###############################] 100%
(29/29) installing mingw-w64-ucrt-x86_64-wxwidgets3.2-msw    [###############################] 100%
resolving dependencies...
looking for conflicting packages...
warning: dependency cycle detected:
warning: mingw-w64-ucrt-x86_64-harfbuzz will be installed before its mingw-w64-ucrt-x86_64-freetype dependency

Packages (15) mingw-w64-ucrt-x86_64-cairo-1.18.4-2  mingw-w64-ucrt-x86_64-fontconfig-2.17.0-1
              mingw-w64-ucrt-x86_64-freetype-2.13.3-1  mingw-w64-ucrt-x86_64-glib2-2.84.3-1
              mingw-w64-ucrt-x86_64-graphite2-1.3.14-3  mingw-w64-ucrt-x86_64-harfbuzz-11.2.1-1
              mingw-w64-ucrt-x86_64-lcms2-2.17-1  mingw-w64-ucrt-x86_64-lzo2-2.10-2
              mingw-w64-ucrt-x86_64-nspr-4.35-2  mingw-w64-ucrt-x86_64-nss-3.113-1
              mingw-w64-ucrt-x86_64-openjpeg2-2.5.3-1  mingw-w64-ucrt-x86_64-pixman-0.46.2-1
              mingw-w64-ucrt-x86_64-poppler-data-0.4.12-1
              mingw-w64-ucrt-x86_64-python-packaging-25.0-1
              mingw-w64-ucrt-x86_64-poppler-25.05.0-1

Total Download Size:    16.21 MiB
Total Installed Size:  103.13 MiB

:: Proceed with installation? [Y/n]
:: Retrieving packages...
 mingw-w64-ucrt-x86_64-harf...  1760.3 KiB  3.76 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-popp...  2002.0 KiB  4.03 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-popp...  1827.3 KiB  3.31 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-cair...   867.9 KiB  6.42 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-glib...     5.1 MiB  7.34 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-free...   613.5 KiB  3.33 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-lcms...   374.3 KiB  3.21 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-pixm...   347.9 KiB  3.36 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-nss-...     2.2 MiB  2.29 MiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-nspr...   333.8 KiB  1567 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-font...   272.4 KiB  2.15 MiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-grap...   141.4 KiB   786 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-lzo2...    95.3 KiB  1095 KiB/s 00:00 [###############################] 100%
 mingw-w64-ucrt-x86_64-open...   438.6 KiB   570 KiB/s 00:01 [###############################] 100%
 mingw-w64-ucrt-x86_64-pyth...   126.7 KiB   331 KiB/s 00:00 [###############################] 100%
 Total (15/15)                    16.2 MiB  9.63 MiB/s 00:02 [###############################] 100%
(15/15) checking keys in keyring                             [###############################] 100%
(15/15) checking package integrity                           [###############################] 100%
(15/15) loading package files                                [###############################] 100%
(15/15) checking for file conflicts                          [###############################] 100%
(15/15) checking available disk space                        [###############################] 100%
:: Processing package changes...
( 1/15) installing mingw-w64-ucrt-x86_64-python-packaging    [###############################] 100%
( 2/15) installing mingw-w64-ucrt-x86_64-glib2               [###############################] 100%
( 3/15) installing mingw-w64-ucrt-x86_64-graphite2           [###############################] 100%
( 4/15) installing mingw-w64-ucrt-x86_64-harfbuzz            [###############################] 100%
( 5/15) installing mingw-w64-ucrt-x86_64-freetype            [###############################] 100%
( 6/15) installing mingw-w64-ucrt-x86_64-fontconfig          [###############################] 100%
updating font cache... done.
( 7/15) installing mingw-w64-ucrt-x86_64-lzo2                [###############################] 100%
( 8/15) installing mingw-w64-ucrt-x86_64-pixman              [###############################] 100%
( 9/15) installing mingw-w64-ucrt-x86_64-cairo               [###############################] 100%
(10/15) installing mingw-w64-ucrt-x86_64-lcms2               [###############################] 100%
(11/15) installing mingw-w64-ucrt-x86_64-nspr                [###############################] 100%
(12/15) installing mingw-w64-ucrt-x86_64-nss                 [###############################] 100%
(13/15) installing mingw-w64-ucrt-x86_64-openjpeg2           [###############################] 100%
(14/15) installing mingw-w64-ucrt-x86_64-poppler-data        [###############################] 100%
(15/15) installing mingw-w64-ucrt-x86_64-poppler             [###############################] 100%
Optional dependencies for mingw-w64-ucrt-x86_64-poppler
    mingw-w64-ucrt-x86_64-glib2: libpoppler-glib [installed]
:: Running post-transaction hooks...
(1/1) Updating fontconfig cache...
warning: mingw-w64-ucrt-x86_64-cairo-1.18.4-2 is up to date -- reinstalling
resolving dependencies...
looking for conflicting packages...

Packages (1) mingw-w64-ucrt-x86_64-cairo-1.18.4-2

Total Installed Size:  3.93 MiB
Net Upgrade Size:      0.00 MiB

:: Proceed with installation? [Y/n]
(1/1) checking keys in keyring                               [###############################] 100%
(1/1) checking package integrity                             [###############################] 100%
(1/1) loading package files                                  [###############################] 100%
(1/1) checking for file conflicts                            [###############################] 100%
(1/1) checking available disk space                          [###############################] 100%
:: Processing package changes...
(1/1) reinstalling mingw-w64-ucrt-x86_64-cairo               [###############################] 100%
resolving dependencies...
looking for conflicting packages...
:: mingw-w64-ucrt-x86_64-pkg-config-0.29.2-6 and mingw-w64-ucrt-x86_64-pkgconf-1~2.5.1-1 are in conflict. Remove mingw-w64-ucrt-x86_64-pkgconf? [Y/n]

Packages (2) mingw-w64-ucrt-x86_64-pkgconf-1~2.5.1-1 [removal]
             mingw-w64-ucrt-x86_64-pkg-config-0.29.2-6

Total Download Size:   0.25 MiB
Total Installed Size:  0.68 MiB
Net Upgrade Size:      0.08 MiB

:: Proceed with installation? [Y/n]
:: Retrieving packages...
 mingw-w64-ucrt-x86_64-pkg-...   254.6 KiB   665 KiB/s 00:00 [###############################] 100%
(1/1) checking keys in keyring                               [###############################] 100%
(1/1) checking package integrity                             [###############################] 100%
(1/1) loading package files                                  [###############################] 100%
(1/1) checking for file conflicts                            [###############################] 100%
(2/2) checking available disk space                          [###############################] 100%
:: Processing package changes...
(1/1) removing mingw-w64-ucrt-x86_64-pkgconf                 [###############################] 100%
(1/1) installing mingw-w64-ucrt-x86_64-pkg-config            [###############################] 100%

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ ./configure
configure: loading site script /etc/config.site
checking for a BSD-compatible install... /usr/bin/install -c
checking whether sleep supports fractional seconds... yes
checking filesystem timestamp resolution... 0.01
checking whether build environment is sane... yes
checking for a race-free mkdir -p... /usr/bin/mkdir -p
checking for gawk... gawk
checking whether make sets $(MAKE)... yes
checking whether make supports nested variables... yes
checking xargs -n works... yes
checking whether UID '1281418' is supported by ustar format... yes
checking whether GID '1049089' is supported by ustar format... yes
checking how to create a ustar tar archive... gnutar
checking whether to enable maintainer-specific portions of Makefiles... no
checking build system type... x86_64-w64-mingw32
checking host system type... x86_64-w64-mingw32
checking for g++... g++
checking whether the C++ compiler works... yes
checking for C++ compiler default output file name... a.exe
checking for suffix of executables... .exe
checking whether we are cross compiling... no
checking for suffix of object files... o
checking whether the compiler supports GNU C++... yes
checking whether g++ accepts -g... yes
checking for g++ option to enable C++11 features... none needed
checking whether make supports the include directive... yes (GNU style)
checking dependency style of g++... gcc3
checking for pkg-config... /ucrt64/bin/pkg-config
checking pkg-config is at least version 0.9.0... yes
checking for glib-2.0 >= 2.36 poppler-glib >= 0.10 cairo-pdf... yes
checking for wx-config... /ucrt64/bin/wx-config
checking for wxWidgets version >= 3.0.0... yes (version 3.2.8)
checking for wxWidgets static library... yes
checking that generated files are newer than configure... done
configure: creating ./config.status
config.status: creating Makefile
config.status: executing depfiles commands

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ make
  CXX      diff_pdf-diff-pdf.o
  CXX      diff_pdf-bmpviewer.o
  CXX      diff_pdf-gutter.o
  CXXLD    diff-pdf.exe

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ make install
make[1]: Entering directory '/c/Users/oscjac/diff-pdf'
 /usr/bin/mkdir -p '/ucrt64/bin'
  /usr/bin/install -c diff-pdf.exe '/ucrt64/bin'
make[1]: Nothing to be done for 'install-data-am'.
make[1]: Leaving directory '/c/Users/oscjac/diff-pdf'

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ which diff-pdf
/ucrt64/bin/diff-pdf

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ diff-pdf --version

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ ^C

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$ make windows-dist
rm -rf diff-pdf-win-0.5.2.zip windist
./win32/collect-dlls.sh windist diff-pdf.exe
'diff-pdf.exe' -> 'windist/diff-pdf.exe'
count=1
'/ucrt64/bin/libcairo-2.dll' -> 'windist/libcairo-2.dll'
'/ucrt64/bin/libgcc_s_seh-1.dll' -> 'windist/libgcc_s_seh-1.dll'
'/ucrt64/bin/libglib-2.0-0.dll' -> 'windist/libglib-2.0-0.dll'
'/ucrt64/bin/libgobject-2.0-0.dll' -> 'windist/libgobject-2.0-0.dll'
'/ucrt64/bin/libpoppler-glib-8.dll' -> 'windist/libpoppler-glib-8.dll'
'/ucrt64/bin/libstdc++-6.dll' -> 'windist/libstdc++-6.dll'
'/ucrt64/bin/wxbase32u_gcc_custom.dll' -> 'windist/wxbase32u_gcc_custom.dll'
'/ucrt64/bin/wxmsw32u_core_gcc_custom.dll' -> 'windist/wxmsw32u_core_gcc_custom.dll'
count=9
'/ucrt64/bin/libffi-8.dll' -> 'windist/libffi-8.dll'
'/ucrt64/bin/libfontconfig-1.dll' -> 'windist/libfontconfig-1.dll'
'/ucrt64/bin/libfreetype-6.dll' -> 'windist/libfreetype-6.dll'
'/ucrt64/bin/libgio-2.0-0.dll' -> 'windist/libgio-2.0-0.dll'
'/ucrt64/bin/libintl-8.dll' -> 'windist/libintl-8.dll'
'/ucrt64/bin/libjpeg-8.dll' -> 'windist/libjpeg-8.dll'
'/ucrt64/bin/liblzma-5.dll' -> 'windist/liblzma-5.dll'
'/ucrt64/bin/libpcre2-16-0.dll' -> 'windist/libpcre2-16-0.dll'
'/ucrt64/bin/libpcre2-8-0.dll' -> 'windist/libpcre2-8-0.dll'
'/ucrt64/bin/libpixman-1-0.dll' -> 'windist/libpixman-1-0.dll'
'/ucrt64/bin/libpng16-16.dll' -> 'windist/libpng16-16.dll'
'/ucrt64/bin/libpoppler-149.dll' -> 'windist/libpoppler-149.dll'
'/ucrt64/bin/libtiff-6.dll' -> 'windist/libtiff-6.dll'
'/ucrt64/bin/libwinpthread-1.dll' -> 'windist/libwinpthread-1.dll'
'/ucrt64/bin/zlib1.dll' -> 'windist/zlib1.dll'
count=24
'/ucrt64/bin/libLerc.dll' -> 'windist/libLerc.dll'
'/ucrt64/bin/libbrotlidec.dll' -> 'windist/libbrotlidec.dll'
'/ucrt64/bin/libbz2-1.dll' -> 'windist/libbz2-1.dll'
'/ucrt64/bin/libcurl-4.dll' -> 'windist/libcurl-4.dll'
'/ucrt64/bin/libdeflate.dll' -> 'windist/libdeflate.dll'
'/ucrt64/bin/libexpat-1.dll' -> 'windist/libexpat-1.dll'
'/ucrt64/bin/libgmodule-2.0-0.dll' -> 'windist/libgmodule-2.0-0.dll'
'/ucrt64/bin/libharfbuzz-0.dll' -> 'windist/libharfbuzz-0.dll'
'/ucrt64/bin/libiconv-2.dll' -> 'windist/libiconv-2.dll'
'/ucrt64/bin/libjbig-0.dll' -> 'windist/libjbig-0.dll'
'/ucrt64/bin/liblcms2-2.dll' -> 'windist/liblcms2-2.dll'
'/ucrt64/bin/libnspr4.dll' -> 'windist/libnspr4.dll'
'/ucrt64/bin/libopenjp2-7.dll' -> 'windist/libopenjp2-7.dll'
'/ucrt64/bin/libplc4.dll' -> 'windist/libplc4.dll'
'/ucrt64/bin/libwebp-7.dll' -> 'windist/libwebp-7.dll'
'/ucrt64/bin/libzstd.dll' -> 'windist/libzstd.dll'
'/ucrt64/bin/nss3.dll' -> 'windist/nss3.dll'
'/ucrt64/bin/smime3.dll' -> 'windist/smime3.dll'
count=42
'/ucrt64/bin/libbrotlicommon.dll' -> 'windist/libbrotlicommon.dll'
'/ucrt64/bin/libcrypto-3-x64.dll' -> 'windist/libcrypto-3-x64.dll'
'/ucrt64/bin/libgraphite2.dll' -> 'windist/libgraphite2.dll'
'/ucrt64/bin/libidn2-0.dll' -> 'windist/libidn2-0.dll'
'/ucrt64/bin/libnghttp2-14.dll' -> 'windist/libnghttp2-14.dll'
'/ucrt64/bin/libnghttp3-9.dll' -> 'windist/libnghttp3-9.dll'
'/ucrt64/bin/libngtcp2-16.dll' -> 'windist/libngtcp2-16.dll'
'/ucrt64/bin/libngtcp2_crypto_ossl.dll' -> 'windist/libngtcp2_crypto_ossl.dll'
'/ucrt64/bin/libplds4.dll' -> 'windist/libplds4.dll'
'/ucrt64/bin/libpsl-5.dll' -> 'windist/libpsl-5.dll'
'/ucrt64/bin/libsharpyuv-0.dll' -> 'windist/libsharpyuv-0.dll'
'/ucrt64/bin/libssh2-1.dll' -> 'windist/libssh2-1.dll'
'/ucrt64/bin/libssl-3-x64.dll' -> 'windist/libssl-3-x64.dll'
'/ucrt64/bin/nssutil3.dll' -> 'windist/nssutil3.dll'
count=56
'/ucrt64/bin/libunistring-5.dll' -> 'windist/libunistring-5.dll'
count=57
count=57
mkdir -p windist/fonts && cp -a ./win32/fonts.conf windist/fonts/
(cd windist && zip -9r ../diff-pdf-win-0.5.2.zip .)
/bin/sh: line 1: zip: command not found
make: *** [Makefile:877: diff-pdf-win-0.5.2.zip] Error 127

oscjac@NOHGS13RBX64 UCRT64 /c/Users/oscjac/diff-pdf
$
