export MakeInc_cmd=${SRCROOT}/makedefs/MakeInc.cmd
export MakeInc_def=${SRCROOT}/makedefs/MakeInc.def
export MakeInc_rule=${SRCROOT}/makedefs/MakeInc.rule
export MakeInc_dir=${SRCROOT}/makedefs/MakeInc.dir


include $(MakeInc_cmd)
include $(MakeInc_def)

INSTINC_SUBDIRS = \
	_types

EXPINC_SUBDIRS = \
	_types

# Installs header file for user level -  
#	  $(DSTROOT)/System/Library/Frameworks/System.framework/PrivateHeaders
#	  $(DSTROOT)/usr/include/
DATAFILES = \
	appleapiopts.h 	acct.h aio.h attr.h \
	buf.h cdefs.h conf.h \
	dir.h dirent.h disk.h dkstat.h dtrace.h dtrace_glue.h dtrace_impl.h \
	errno.h ev.h event.h fasttrap.h fasttrap_isa.h fcntl.h file.h filedesc.h filio.h gmon.h \
	ioccom.h ioctl.h \
	ioctl_compat.h ipc.h kernel.h kernel_types.h kern_event.h lctx.h loadable_fs.h lock.h lockf.h \
	kauth.h kdebug.h kern_control.h lockstat.h malloc.h \
	mbuf.h mman.h mount.h msg.h msgbuf.h netport.h param.h paths.h pipe.h poll.h \
	proc.h  proc_info.h ptrace.h queue.h quota.h random.h reboot.h resource.h resourcevar.h \
	sbuf.h posix_sem.h posix_shm.h sdt.h \
	select.h sem.h semaphore.h shm.h signal.h signalvar.h socket.h socketvar.h sockio.h stat.h stdio.h \
	sysctl.h syslimits.h syslog.h sys_domain.h termios.h  time.h \
	timeb.h times.h tprintf.h trace.h tty.h  ttychars.h ttycom.h \
	ttydefaults.h ttydev.h  types.h ubc.h ucontext.h ucred.h uio.h un.h unistd.h unpcb.h \
	user.h utfconv.h utsname.h vadvise.h vcmd.h \
	vm.h vmmeter.h vmparam.h vnioctl.h vnode.h vnode_if.h vstat.h wait.h xattr.h \
	_select.h _structs.h _types.h _endian.h domain.h protosw.h \
	spawn.h

# Installs header file for Apple internal use in user level - 
#	  $(DSTROOT)/System/Library/Frameworks/System.framework/PrivateHeaders
PRIVATE_DATAFILES = \
	attr.h \
	cdefs.h \
	coalition.h \
	codesign.h \
	content_protection.h \
	csr.h \
	decmpfs.h \
	disk.h \
	disklabel.h \
	domain.h \
	event.h \
	fcntl.h \
	fileport.h \
	fsctl.h \
	fsevents.h \
	fsgetpath.h \
	fslog.h \
	guarded.h \
	imgsrc.h \
	ipcs.h \
	kas_info.h \
	kdebug.h \
	kern_control.h \
	kern_event.h \
	kern_memorystatus.h \
	kern_overrides.h \
	mbuf.h \
	mman.h \
	persona.h \
	priv.h \
	proc.h \
	proc_info.h \
	proc_uuid_policy.h \
	process_policy.h \
	resource.h \
	sfi.h \
	shm_internal.h \
	socket.h \
	socketvar.h \
	sockio.h \
	spawn.h \
	spawn_internal.h \
	stackshot.h \
	sys_domain.h \
	tree.h \
	unpcb.h \
	ux_exception.h \
	work_interval.h \
	process_policy.h \
	proc_uuid_policy.h \
	priv.h \
	pgo.h \
	memory_maintenance.h

# Installs header file for kernel extensions - 
#	  $(DSTROOT)/System/Library/Frameworks/Kernel.framework/Headers
#	  $(DSTROOT)/System/Library/Frameworks/Kernel.framework/PrivateHeaders
KERNELFILES = \
	appleapiopts.h 	 attr.h \
	buf.h cdefs.h conf.h \
	dir.h dirent.h disk.h disklabel.h dkstat.h  \
	errno.h ev.h event.h fcntl.h file.h filio.h \
	ioccom.h ioctl.h ipc.h \
	ioctl_compat.h  kernel.h kernel_types.h kern_event.h lock.h lockf.h \
	kauth.h kdebug.h  md5.h kern_control.h imgact.h malloc.h namei.h \
	mman.h mbuf.h mount.h netport.h param.h paths.h \
	proc.h  queue.h random.h resource.h \
	sbuf.h posix_sem.h posix_shm.h sem.h shm.h \
	select.h signal.h socket.h socketvar.h sockio.h stat.h stdio.h \
	sysctl.h syslimits.h syslog.h systm.h sys_domain.h  time.h \
	types.h ubc.h ucontext.h ucred.h uio.h un.h unistd.h unpcb.h \
	utfconv.h vm.h vmparam.h vnode.h vnode_if.h xattr.h \
	_select.h _structs.h _types.h _endian.h protosw.h domain.h \
	kpi_mbuf.h kpi_socket.h kpi_socketfilter.h \
	ttycom.h termios.h msg.h \
	wait.h \
	spawn.h
# The last line was added to export needed headers for the MAC calls
# whose source is outside of the xnu/bsd tree.


# Installs header file for Apple internal use for kernel extensions - 
#	  $(DSTROOT)/System/Library/Frameworks/Kernel.framework/PrivateHeaders
PRIVATE_KERNELFILES = \
	codesign.h \
	cprotect.h \
	content_protection.h \
	csr.h \
	decmpfs.h \
	disktab.h \
	fbt.h \
	fileport.h \
	fsctl.h \
	fslog.h \
	kasl.h \
	kern_memorystatus.h \
	kpi_private.h \
	mach_swapon.h \
	msgbuf.h \
	eventvar.h \
	persona.h \
	proc_info.h \
	pthread_shims.h \
	quota.h \
	sem_internal.h \
	shm_internal.h \
	signalvar.h \
	stackshot.h \
	tty.h  ttychars.h \
	ttydefaults.h ttydev.h \
	user.h \
	vfs_context.h \
	vmmeter.h \
	spawn_internal.h \
	priv.h \
	pgo.h \
	memory_maintenance.h


# /usr/include
INSTALL_MI_LIST	= ${DATAFILES}

INSTALL_MI_GEN_LIST = syscall.h _posix_availability.h _symbol_aliasing.h

INSTALL_MI_DIR = sys

EXPORT_MI_LIST	= ${KERNELFILES} ${PRIVATE_KERNELFILES} linker_set.h bsdtask_info.h pthread_internal.h filedesc.h pipe.h resourcevar.h semaphore.h \
								vnode_internal.h proc_internal.h file_internal.h mount_internal.h \
								uio_internal.h tree.h munge.h

EXPORT_MI_GEN_LIST = syscall.h sysproto.h kdebugevents.h

EXPORT_MI_DIR = sys

# /System/Library/Frameworks/System.framework/PrivateHeaders
INSTALL_MI_LCL_LIST = ${PRIVATE_DATAFILES}

# /System/Library/Frameworks/Kernel.framework/PrivateHeaders
INSTALL_KF_MI_LCL_LIST =  ${KERNELFILES} ${PRIVATE_KERNELFILES}

INSTALL_KF_MI_LCL_GEN_LIST = sysproto.h

# /System/Library/Frameworks/Kernel.framework/Headers
INSTALL_KF_MI_LIST = ${KERNELFILES}

INSTALL_KF_MI_GEN_LIST =

MAKESYSCALLS = $(SRCROOT)/bsd/kern/makesyscalls.sh
MAKEKDEBUGEVENTS = $(SRCROOT)/bsd/kern/makekdebugevents.py

$(OBJROOT)/cscope.genhdrs:
	$(_v)mkdir -p $(OBJROOT)/cscope.genhdrs

syscall.h: $(SRCROOT)/bsd/kern/syscalls.master $(MAKESYSCALLS) $(OBJROOT)/cscope.genhdrs
	@echo "Generating bsd/sys/$@ from $<";
	@echo "$(OBJPATH)/bsd/sys/$@" > $(OBJROOT)/cscope.genhdrs/$@.path
	$(_v)$(MAKESYSCALLS) $< header > /dev/null

sysproto.h: $(SRCROOT)/bsd/kern/syscalls.master $(MAKESYSCALLS) $(OBJROOT)/cscope.genhdrs
	@echo "Generating bsd/sys/$@ from $<";
	@echo "$(OBJPATH)/bsd/sys/$@" > $(OBJROOT)/cscope.genhdrs/$@.path
	$(_v)$(MAKESYSCALLS) $< proto > /dev/null

kdebugevents.h:  $(SRCROOT)/bsd/kern/trace.codes $(MAKEKDEBUGEVENTS) $(OBJROOT)/cscope.genhdrs
	@echo "Generating bsd/sys/$@ from $<";
	@echo "$(OBJPATH)/bsd/sys/$@" > $(OBJROOT)/cscope.genhdrs/$@.path
	$(_v)$(MAKEKDEBUGEVENTS) $< > "$(OBJPATH)/bsd/sys/$@"

MAKE_POSIX_AVAILABILITY = $(SRCROOT)/bsd/sys/make_posix_availability.sh
_posix_availability.h: $(MAKE_POSIX_AVAILABILITY)
	@echo "Generating bsd/sys/$@"
	$(_v)$(MAKE_POSIX_AVAILABILITY) "$@"

MAKE_SYMBOL_ALIASING = $(SRCROOT)/bsd/sys/make_symbol_aliasing.sh
_symbol_aliasing.h: $(MAKE_SYMBOL_ALIASING)
	@echo "Generating bsd/sys/$@"
	$(_v)$(MAKE_SYMBOL_ALIASING) "$(SDKROOT)" "$@"

include $(MakeInc_rule)
include $(MakeInc_dir)


