.. image:: https://img.shields.io/badge/rtn--066-lsst.io-brightgreen.svg
   :target: https://rtn-066.lsst.io
.. image:: https://github.com/lsst/rtn-066/workflows/CI/badge.svg
   :target: https://github.com/lsst/rtn-066/actions/

############################################
On JIRA workflows for ovservatory operations
############################################

RTN-066
=======

Rubin has extensive and in some cases sophisticated workflows based on JIRA for anything from managing planned work, to reporting bugs,  to defining validation campaigns,  to managing staff travel. There are 12 highly active JIRA projects supporting this diverse collection of workflows and they are central to the working day of project staff. 

With nightly telescope operations becoming a central focus, the question arises of how and to what extent to integrate night-time operations to the well developed workflows staff are already using. This document discusses some of the issues raised and proposes a workflow as a basis of further discussion. 

**Links:**

- Publication URL: https://rtn-066.lsst.io
- Alternative editions: https://rtn-066.lsst.io/v
- GitHub repository: https://github.com/lsst/rtn-066
- Build system: https://github.com/lsst/rtn-066/actions/


Build this technical note
=========================

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

.. code-block:: bash

   git clone https://github.com/lsst/rtn-066
   cd rtn-066
   make init
   make html

Repeat the ``make html`` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run ``make clean``.

The built technote is located at ``_build/html/index.html``.

Publishing changes to the web
=============================

This technote is published to https://rtn-066.lsst.io whenever you push changes to the ``main`` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://rtn-066.lsst.io/v.

Editing this technical note
===========================

The main content of this technote is in ``index.rst`` (a reStructuredText file).
Metadata and configuration is in the ``technote.toml`` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
