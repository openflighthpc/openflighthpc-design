.. openFlightHPC-clusters documentation master file, created by
   sphinx-quickstart on Mon Sep  2 13:08:50 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to the openFlightHPC Design Knowledgebase!
==================================================

This site contains documentation on general cluster considerations and best practices. It contains concept descriptions, implementation considerations and guidelines for developing a HPC stack. 

Documentation Goal
------------------

The purpose of this documentation is to provide a list of considerations and guidelines for the development of a High Performance Computing (HPC) environment. This documentation should be followed through in order to properly understand the structure of the environment and that certain considerations are not missed out along the way.

To generalise the entire process, it goes as follows::

    Cluster Architecture Design -> Platform Deployment/Management -> Environment Delivery

*Cluster Architecture Design* consists of many considerations regarding the platform, configuration and purpose of the cluster. Creating a suitable architecture design will maximise the ease of cluster management and workflow efficiency.

*Platform Deployment/Management* involves the creation of the cluster resources and configuring the base systems of the node in preparation for environment customisation.

*Environment Delivery* is the installation of software for the user experience on the cluster. This usually involves some sort of resource management/queuing system and application installation.

.. note:: It is recommended to read through all of the documentation before starting to design the HPC platform to understand the scope and considerations.

Acknowledgements
----------------

We recognise the respect the trademarks of all third-party providers referenced in this documentation. Please see the respective EULAs for software packages used in configuring your own environment based on this knowledgebase.

License
^^^^^^^

This documentation is released under the `Creative-Commons: Attribution-ShareAlike 4.0 International <http://creativecommons.org/licenses/by-sa/4.0/>`_ license.

Table of Contents
=================

.. Navigation/TOC

.. toctree::
   :maxdepth: 1
   :caption: Architecture
   :name: architecture

   architecture/considerations
   architecture/considerations-network-design
   architecture/considerations-infrastructure-design
   architecture/considerations-storage-design

.. toctree::
   :maxdepth: 1
   :caption: Platform
   :name: platform

   platform/considerations

.. toctree::
   :maxdepth: 1
   :caption: Environment
   :name: environment

   environment/considerations

