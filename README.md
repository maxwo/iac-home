# Playbook to provision home machines

On Mac OS machines, make sure to unset password prompt for sudo:

    sudo visudo

And then:

    admin          ALL = (ALL) NOPASSWD: ALL
