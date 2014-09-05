ansible-rackspace
=================

Attempt to get a fully automated, deployable, barebones rackspace cloud.

The idea is to isolate the Rackspace instantiation in `rackspace` and pass the newly created machines
to `absinth` role which just installs a few packages as a demo.

There is also a Vagrantfile that should allow local deployment and testing before pushing into rackspace cloud.

All of this with the dynamic inventory script from ansible's plugins/rax.py.

Requires a ~/.rackspace_cloud_credentials as specified in: http://docs.ansible.com/guide_rax.html

License
-------

GPLv3
