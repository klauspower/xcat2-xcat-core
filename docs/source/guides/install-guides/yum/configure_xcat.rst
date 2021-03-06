Configure xCAT Software Repository
==================================

xCAT software and repo files can be obtained from: `<http://xcat.org/download.html>`_

Internet Repository
-------------------

**[xcat-core]**

For the xCAT version you want to install, download the ``xcat-core.repo`` file and copy it to ``/etc/yum.repos.d``

**[xcat-dep]**

From the `xCAT-dep Online Repository <http://xcat.org/files/xcat/repos/yum/xcat-dep/>`_, navigate to the correct subdirectory for the target machine and download the ``xcat-dep.repo`` file and copy it to ``/etc/yum.repos.d``.

Continue to the next section to install xCAT.

Local Repository
----------------

.. xcat-core
.. include:: ../common_sections.rst
   :start-after: BEGIN_configure_xcat_local_repo_xcat-core_RPM
   :end-before: END_configure_xcat_local_repo_xcat-core_RPM

.. xcat-dep
.. include:: ../common_sections.rst
   :start-after: BEGIN_configure_xcat_local_repo_xcat-dep_RPM
   :end-before: END_configure_xcat_local_repo_xcat-dep_RPM

