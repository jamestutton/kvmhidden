EXTRA_DIST = before_vm_start.py

install-data-local:
    $(MKDIR_P) $(DESTDIR)$(vdsmhooksdir)/before_vm_start
    $(INSTALL_SCRIPT) $(srcdir)/before_vm_start.py $(DESTDIR)$(vdsmhooksdir)/before_vm_start/50_kvmhidden

uninstall-local:
    $(RM) $(DESTDIR)$(vdsmhooksdir)/before_vm_start/50_kvmhidden
