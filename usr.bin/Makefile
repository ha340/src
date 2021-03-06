#	From: @(#)Makefile	8.3 (Berkeley) 1/7/94
# $FreeBSD$

.include <src.opts.mk>

# XXX MISSING:		deroff diction graph learn plot
#			spell spline struct xsend
# XXX Use GNU versions: diff ld patch
# Moved to secure: bdes
#

SUBDIR=	alias \
	apply \
	asa \
	awk \
	banner \
	basename \
	brandelf \
	bsdcat \
	bsdiff \
	bzip2 \
	bzip2recover \
	cap_mkdb \
	chat \
	chpass \
	cksum \
	cmp \
	col \
	colldef \
	colrm \
	column \
	comm \
	compress \
	cpuset \
	csplit \
	ctlstat \
	cut \
	dirname \
	du \
	elf2aout \
	elfdump \
	enigma \
	env \
	etdump \
	expand \
	false \
	fetch \
	find \
	fmt \
	fold \
	fstat \
	fsync \
	gcore \
	gencat \
	getaddrinfo \
	getconf \
	getent \
	getopt \
	grep \
	gzip \
	head \
	hexdump \
	id \
	ident \
	ipcrm \
	ipcs \
	join \
	jot \
	keylogin \
	keylogout \
	killall \
	ktrace \
	ktrdump \
	lam \
	lastcomm \
	ldd \
	leave \
	less \
	lessecho \
	lesskey \
	limits \
	locale \
	localedef \
	lock \
	lockf \
	logger \
	login \
	logins \
	logname \
	look \
	lorder \
	lsvfs \
	lzmainfo \
	m4 \
	mandoc \
	mesg \
	minigzip \
	ministat \
	mkdep \
	mkfifo \
	mkimg \
	mklocale \
	mktemp \
	mkuzip \
	mt \
	ncal \
	netstat \
	newgrp \
	nfsstat \
	nice \
	nl \
	numactl \
	nohup \
	opieinfo \
	opiekey \
	opiepasswd \
	pagesize \
	passwd \
	paste \
	patch \
	pathchk \
	perror \
	pr \
	printenv \
	printf \
	proccontrol \
	procstat \
	protect \
	rctl \
	renice \
	resizewin \
	rev \
	revoke \
	rpcinfo \
	rs \
	rup \
	ruptime \
	rusers \
	rwall \
	rwho \
	script \
	sdiff \
	sed \
	send-pr \
	seq \
	shar \
	showmount \
	sockstat \
	soelim \
	sort \
	split \
	stat \
	stdbuf \
	strings \
	su \
	systat \
	tabs \
	tail \
	tar \
	tcopy \
	tee \
	time \
	timeout \
	tip \
	top \
	touch \
	tput \
	tr \
	true \
	truncate \
	tset \
	tsort \
	tty \
	uname \
	unexpand \
	uniq \
	unzip \
	units \
	unvis \
	uudecode \
	uuencode \
	vis \
	vmstat \
	w \
	wall \
	wc \
	what \
	whereis \
	which \
	whois \
	write \
	xargs \
	xinstall \
	xo \
	xz \
	xzdec \
	yes

# NB: keep these sorted by MK_* knobs

SUBDIR.${MK_AT}+=	at
SUBDIR.${MK_ATM}+=	atm
SUBDIR.${MK_BLUETOOTH}+=	bluetooth
SUBDIR.${MK_BSD_CPIO}+=	cpio
SUBDIR.${MK_CALENDAR}+=	calendar
SUBDIR.${MK_CLANG}+=	clang
SUBDIR.${MK_DIALOG}+=	dpv
SUBDIR.${MK_EE}+=	ee
SUBDIR.${MK_FILE}+=	file
SUBDIR.${MK_FINGER}+=	finger
SUBDIR.${MK_FTP}+=	ftp
SUBDIR.${MK_GAMES}+=	caesar
SUBDIR.${MK_GAMES}+=	factor
SUBDIR.${MK_GAMES}+=	fortune
SUBDIR.${MK_GAMES}+=	grdc
SUBDIR.${MK_GAMES}+=	morse
SUBDIR.${MK_GAMES}+=	number
SUBDIR.${MK_GAMES}+=	pom
SUBDIR.${MK_GAMES}+=	primes
SUBDIR.${MK_GAMES}+=	random
.if ${MK_GNU_DIFF} == "no"
SUBDIR+=		diff
.endif
.if ${MK_GPL_DTC} != "yes"
.if ${COMPILER_FEATURES:Mc++11}
SUBDIR+=	dtc
.endif
.endif
SUBDIR.${MK_GROFF}+=	vgrind
SUBDIR.${MK_HESIOD}+=	hesinfo
SUBDIR.${MK_ICONV}+=	iconv
SUBDIR.${MK_ICONV}+=	mkcsmapper
SUBDIR.${MK_ICONV}+=	mkesdb
SUBDIR.${MK_ISCSI}+=	iscsictl
SUBDIR.${MK_KDUMP}+=	kdump
SUBDIR.${MK_KDUMP}+=	truss
SUBDIR.${MK_KERBEROS_SUPPORT}+=	compile_et
SUBDIR.${MK_LDNS_UTILS}+=	drill
SUBDIR.${MK_LDNS_UTILS}+=	host
SUBDIR.${MK_LOCATE}+=	locate
# XXX msgs?
SUBDIR.${MK_MAIL}+=	biff
SUBDIR.${MK_MAIL}+=	from
SUBDIR.${MK_MAIL}+=	mail
SUBDIR.${MK_MAIL}+=	msgs
SUBDIR.${MK_MAKE}+=	bmake
SUBDIR.${MK_MAN_UTILS}+=	catman
.if ${MK_MANDOCDB} == "no"	# AND
SUBDIR.${MK_MAN_UTILS}+=	makewhatis
.endif
SUBDIR.${MK_MAN_UTILS}+=	man
.if ${MK_LIBRESSL} == "no"
SUBDIR.${MK_NETCAT}+=	nc
.endif
SUBDIR.${MK_NIS}+=	ypcat
SUBDIR.${MK_NIS}+=	ypmatch
SUBDIR.${MK_NIS}+=	ypwhich
SUBDIR.${MK_OPENSSH}+=	ssh-copy-id
SUBDIR.${MK_OPENSSL}+=	bc
SUBDIR.${MK_OPENSSL}+=	chkey
SUBDIR.${MK_OPENSSL}+=	dc
SUBDIR.${MK_OPENSSL}+=	newkey
SUBDIR.${MK_QUOTAS}+=	quota
SUBDIR.${MK_RCMDS}+=	rlogin
SUBDIR.${MK_RCMDS}+=	rsh
SUBDIR.${MK_SENDMAIL}+=	vacation
SUBDIR.${MK_TALK}+=	talk
SUBDIR.${MK_TELNET}+=	telnet
SUBDIR.${MK_TESTS}+=	tests
SUBDIR.${MK_TEXTPROC}+=	checknr
SUBDIR.${MK_TEXTPROC}+=	colcrt
SUBDIR.${MK_TEXTPROC}+=	ul
SUBDIR.${MK_TFTP}+=	tftp
SUBDIR.${MK_TOOLCHAIN}+=	addr2line
SUBDIR.${MK_TOOLCHAIN}+=	ar
SUBDIR.${MK_TOOLCHAIN}+=	c89
SUBDIR.${MK_TOOLCHAIN}+=	c99
SUBDIR.${MK_TOOLCHAIN}+=	ctags
SUBDIR.${MK_TOOLCHAIN}+=	cxxfilt
SUBDIR.${MK_TOOLCHAIN}+=	elfcopy
SUBDIR.${MK_TOOLCHAIN}+=	file2c
# ARM64TODO gprof does not build
# RISCVTODO gprof does not build
.if ${MACHINE_ARCH} != "aarch64" && ${MACHINE_CPUARCH} != "riscv"
SUBDIR.${MK_TOOLCHAIN}+=	gprof
.endif
SUBDIR.${MK_TOOLCHAIN}+=	indent
SUBDIR.${MK_TOOLCHAIN}+=	lex
SUBDIR.${MK_TOOLCHAIN}+=	mkstr
SUBDIR.${MK_TOOLCHAIN}+=	nm
SUBDIR.${MK_TOOLCHAIN}+=	readelf
SUBDIR.${MK_TOOLCHAIN}+=	rpcgen
SUBDIR.${MK_TOOLCHAIN}+=	unifdef
SUBDIR.${MK_TOOLCHAIN}+=	size
.if ${MK_LINT} != "no" && ${MACHINE_ARCH} != "aarch64" # ARM64TODO xlint does not build
SUBDIR.${MK_TOOLCHAIN}+=	xlint
.endif
SUBDIR.${MK_TOOLCHAIN}+=	xstr
SUBDIR.${MK_TOOLCHAIN}+=	yacc
SUBDIR.${MK_VI}+=	vi
SUBDIR.${MK_VT}+=	vtfontcvt
SUBDIR.${MK_USB}+=	usbhidaction
SUBDIR.${MK_USB}+=	usbhidctl
SUBDIR.${MK_UTMPX}+=	last
.if ${MACHINE_CPUARCH} != "riscv" # RISCVTODO users does not build
SUBDIR.${MK_UTMPX}+=	users
.endif
SUBDIR.${MK_UTMPX}+=	who
SUBDIR.${MK_SVN}+=	svn
SUBDIR.${MK_SVNLITE}+=	svn

# These are normally only handled for build-tools.
.if make(clean*)
SUBDIR+=	mkcsmapper_static
SUBDIR+=	mkesdb_static
.endif

.include <bsd.arch.inc.mk>

SUBDIR_PARALLEL=

.include <bsd.subdir.mk>
