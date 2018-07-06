Fully Working Tempest Suite.

To Generate tempest.conf file you can run below command:

# tox -e genconfig

For detailed instructions follow below URL:

https://blogs.rdoproject.org/2016/11/how-to-install-and-run-tempest/


------------------------------------------------------------------
To execute test cases, use below commands:

# python -m testtools.run tempest.api.volume.test_volumes_list

# python -m testtools.run tempest/api/identity/v3/test_tokens.py

# nosetests -sv tempest.api.volume.test_volumes_list
