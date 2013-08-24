Sample upstart init scripts

# Using

Put scripts to `/etc/init` and change based on you environment.

# Disable

If you need to disable service to bootup, see `whoopsie.override`, and copy
to service, like:

    cp whoopsie.override /etc/init/mongodb.override
