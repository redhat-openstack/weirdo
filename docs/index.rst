Welcome to the WeIRDO's documentation!
======================================
**W**\e [ **I**\nstall | **I**\ntegrate | **I**\mprove ] **RDO**: An open
initiative to improve RDO_ with it's community for it's community.

.. _RDO: https://www.rdoproject.org/

Testing OpenStack_ is hard:

* There is *currently* almost 50 official `OpenStack projects`_
* There is over 1000 source and binary packages built and provided by the
  official RDO repositories
* These packages are bundled, integrated or provided by many different
  installers and vendors
* There are countless deployment use cases ranging from simple private clouds
  to large scale complex and highly available public clouds

Providing test coverage to make sure that each and every project and use case
works well is a hard problem to solve.

WeIRDO is an idea that is about leveraging the effort the community puts
towards their own CI initiative to improve the coverage that upstream RDO
provides.
This is about testing as many ways of installing, configuring and integrating
OpenStack as possible without re-inventing the wheel.

WeIRDO takes the gate jobs outside of the gate to test what RDO ships before
it’s packages even make it to the upstream OpenStack CI.

Let's work together to make RDO better.

.. _OpenStack: http://www.openstack.org/
.. _OpenStack projects: http://governance.openstack.org/reference/projects/index.html

Where can I find the WeIRDO CI Jobs ?
-------------------------------------
All RDO CI jobs are publicly available and the ones from WeIRDO are no
exception.

WeIRDO is currently used in two different implementations:

* `ci.centos.org`_: Periodic jobs to test and promote RDO trunk packages
* `review.rdoproject.org`_: Gate jobs for WeIRDO itself (and it's roles) and for other projects

For more details on those implementations, see the `jenkins job configuration`_
documentation.

.. _ci.centos.org: https://ci.centos.org/view/rdo/view/promotion-pipeline/
.. _review.rdoproject.org: https://review.rdoproject.org
.. _jenkins job configuration: http://weirdo.readthedocs.io/en/latest/jenkins-job-configuration.html

Table of Contents
=================

.. toctree::
    :maxdepth: 2

    Contributing <contributing>
    How it works <how>
    Ansible playbooks <playbooks>
    Ansible roles <roles>
    Jenkins Job Configuration <jenkins-job-configuration>
