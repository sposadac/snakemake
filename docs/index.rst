.. _manual-main:

=========
Snakemake
=========

.. image:: https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod
    :target: https://gitpod.io/#https://github.com/snakemake/snakemake

.. image:: https://img.shields.io/conda/dn/bioconda/snakemake.svg?label=Bioconda
    :target: https://bioconda.github.io/recipes/snakemake/README.html

.. image:: https://img.shields.io/pypi/pyversions/snakemake.svg
    :target: https://www.python.org

.. image:: https://img.shields.io/pypi/v/snakemake.svg
    :target: https://pypi.python.org/pypi/snakemake

.. image:: https://img.shields.io/github/workflow/status/snakemake/snakemake/Publish%20to%20Docker%20Hub?color=blue&label=docker%20container&branch=main
    :target: https://hub.docker.com/r/snakemake/snakemake

.. image:: https://github.com/snakemake/snakemake/workflows/CI/badge.svg?branch=main&label=tests
    :target: https://github.com/snakemake/snakemake/actions?query=branch%3Amain+workflow%3ACI

.. image:: https://img.shields.io/badge/stack-overflow-orange.svg
    :target: https://stackoverflow.com/questions/tagged/snakemake

.. image:: https://img.shields.io/twitter/follow/johanneskoester.svg?style=social&label=Follow
    :target: https://twitter.com/search?l=&q=%23snakemake%20from%3Ajohanneskoester

.. image:: https://img.shields.io/discord/753690260830945390?label=discord%20chat   
    :alt: Discord
    :target: https://discord.gg/NUdMtmr

.. image:: https://img.shields.io/github/stars/snakemake/snakemake?style=social
    :alt: GitHub stars
    :target: https://github.com/snakemake/snakemake/stargazers

.. .. raw:: html
          <span class="__dimensions_badge_embed__" data-doi="https://doi.org/10.1093/bioinformatics/bts480" data-legend="always" data-style="large_rectangle"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

The Snakemake workflow management system is a tool to create **reproducible and scalable** data analyses.
Workflows are described via a human readable, Python based language.
They can be seamlessly scaled to server, cluster, grid and cloud environments, without the need to modify the workflow definition.
Finally, Snakemake workflows can entail a description of required software, which will be automatically deployed to any execution environment.

Snakemake is **highly popular** with, `>5 new citations per week <https://badge.dimensions.ai/details/id/pub.1018944052>`_.
For an introduction, please visit https://snakemake.github.io.


.. _main-getting-started:

---------------
Getting started
---------------

* To get a first impression, please visit https://snakemake.github.io.
* To properly understand what Snakemake can do for you please read our `"rolling" paper <https://doi.org/10.12688/f1000research.29032.1>`_.
* News about Snakemake are published via `Twitter <https://twitter.com/search?l=&q=%23snakemake%20from%3Ajohanneskoester>`_.
* To learn Snakemake, please do the :ref:`tutorial`, and see the :ref:`FAQ <project_info-faq>`.
* **Best practices** for writing Snakemake workflows can be found :ref:`here <snakefiles-best_practices>`.
* For more advanced usage on various platforms, see the :ref:`executor_tutorial`.

.. _main-support:

-------
Support
-------

* For releases, see :ref:`Changelog <changelog>`.
* Check :ref:`frequently asked questions (FAQ) <project_info-faq>`.
* In case of **questions**, please post on `stack overflow <https://stackoverflow.com/questions/tagged/snakemake>`_.
* To **discuss** with other Snakemake users, use the `discord server <https://discord.gg/kHvtG6N>`_. **Please do not post questions there. Use stack overflow for questions.**
* For **bugs and feature requests**, please use the `issue tracker <https://github.com/snakemake/snakemake/issues>`_.
* For **contributions**, visit Snakemake on `Github <https://github.com/snakemake/snakemake>`_ and read the :ref:`guidelines <project_info-contributing>`.

--------
Citation
--------
When using Snakemake, please cite our "rolling" paper

`Mölder, F., Jablonski, K.P., Letcher, B., Hall, M.B., Tomkins-Tinch, C.H., Sochat, V., Forster, J., Lee, S., Twardziok, S.O., Kanitz, A., Wilm, A., Holtgrewe, M., Rahmann, S., Nahnsen, S., Köster, J., 2021. Sustainable data analysis with Snakemake. F1000Res 10, 33. <https://doi.org/10.12688/f1000research.29032.1>`_

This paper will also be regularly updated when Snakemake receives new features.
See :doc:`Citations <project_info/citations>` for more information.

---------
Resources
---------

`Snakemake Wrappers Repository <https://snakemake-wrappers.readthedocs.org>`_
    The Snakemake Wrapper Repository is a collection of reusable wrappers that allow to quickly use popular tools from Snakemake rules and workflows.

`Snakemake Workflow Catalog <https://snakemake.github.io/snakemake-workflow-catalog>`_
    An automatically scraped catalog of publicly available Snakemake workflows for any kind of data analysis.

`Snakemake Workflows Project <https://github.com/snakemake-workflows/docs>`_
    This project provides a collection of high quality modularized and re-usable workflows.
    The provided code should also serve as a best-practices of how to build production ready workflows with Snakemake.
    Everybody is invited to contribute.

`Snakemake Profiles Project <https://github.com/snakemake-profiles/doc>`_
    This project provides Snakemake configuration profiles for various execution environments.
    Please consider contributing your own if it is still missing.

`Conda-Forge <https://conda-forge.org>`_
    Conda-Forge is a community driven distribution of Conda packages that can be used from Snakemake for creating completely reproducible workflows by defining the used software versions and providing binaries.

`Bioconda <https://bioconda.github.io/>`_
    Bioconda, a partner project of conda-forge, is a community driven distribution of bioinformatics-related Conda packages that can be used from Snakemake for creating completely reproducible workflows by defining the used software versions and providing binaries.


.. toctree::
   :caption: Getting started
   :name: getting_started
   :hidden:
   :maxdepth: 1

   getting_started/installation
   tutorial/tutorial
   tutorial/short
   executor_tutorial/tutorial

.. toctree::
  :caption: Executing workflows
  :name: execution
  :hidden:
  :maxdepth: 1

  executing/cli
  executing/cluster
  executing/cloud
  executing/grouping
  executing/caching
  executing/interoperability
  executing/monitoring

.. toctree::
    :caption: Defining workflows
    :name: snakefiles
    :hidden:
    :maxdepth: 1

    snakefiles/writing_snakefiles
    snakefiles/rules
    snakefiles/configuration
    snakefiles/modularization
    snakefiles/remote_files
    snakefiles/utils
    snakefiles/deployment
    snakefiles/reporting
    snakefiles/testing
    snakefiles/foreign_wms


.. toctree::
    :caption: API Reference
    :name: api-reference
    :hidden:
    :maxdepth: 1

    api_reference/snakemake
    api_reference/snakemake_utils
    api_reference/internal/modules


.. toctree::
    :caption: Project Info
    :name: project-info
    :hidden:
    :maxdepth: 1

    project_info/citations
    project_info/more_resources
    project_info/faq
    project_info/contributing
    project_info/authors
    project_info/history
    project_info/license
