Image standards
=================

Hints and notes for people who are going to be building images from the CentOS Distribution. The project home page is at http://wiki.centos.org/Projects/ImageStandards.

### General requirements

* No udev rules from the image build node should be present.
* `.bash_history` should be empty in all accounts.
* Setup `.authorized_keys` for all accounts on the fly or provide via metadata service.
* Images should be based on the minimal distribution.
