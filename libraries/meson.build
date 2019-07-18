
cpu_family = host_machine.cpu_family()
if cpu_family == 'x86_64'
    install_data('Linux 64-bit/libokFrontPanel.so', install_dir: 'lib/intan')
elif cpu_family == 'x86'
    install_data('Linux 32-bit/libokFrontPanel.so', install_dir: 'lib/intan')
else
    error('No FrontPanel libraries exist for architecture: ' + cpu_family)
endif
