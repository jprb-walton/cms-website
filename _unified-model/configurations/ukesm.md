---
title: Introduction to UKESM
teaser: The UK Earth System Model (UKESM) has been built as a joint venture between the Met Office Hadley Centre and the Natural Environment Research Council (NERC).  It consists of the HadGEM3 coupled physical climate model plus additional components that model key biogeochemical, chemistry, aerosol and vegetation processes.   
---

More information about the contents and development of UKESM is available on the [UKESM website](https://ukesm.ac.uk/).  The latest release is UKESM1.1 (see [here](https://ukesm.ac.uk/portfolio-item/introducing-ukesm1-1-a-new-configuration-of-the-ukesm-model-with-an-improved-historical-temperature-record/) for information about its development), whilst the first release was UKESM1 (see [here](https://ukesm.ac.uk/portfolio-item/release-and-support-of-ukesm1/) and [here](https://ukesm.ac.uk/portfolio-item/the-release-of-ukesm1-update/) for more on its release and support).

### Background and prerequisites

UKESM makes use of several scientific components, including the [Unified Model](https://www.metoffice.gov.uk/research/modelling-systems/unified-model) (UM) weather and climate modelling application.  See [here]({{site.baseurl}}/pages/unified-model) for more on the UM.

UKESM is distributed and run as a [Rose](https://www.metoffice.gov.uk/research/modelling-systems/rose) suite; Rose is a framework for developing and running meteorological applications.  Some details about Rose are available [here]({{site.baseurl}}/pages/rose-cylc).

The UKESM suites incorporate switches to choose the machine on which it is run; full details of how to do this are in the release notes - see [below](#ukesm-release-notes).  Available resources include [ARCHER2](http://www.archer2.ac.uk/), the UKRI platform, and [Monsoon2](http://www.jwcrp.org.uk/infrastructure/monsoon.asp), the Met Office / NERC collaborative platform.  Both are accessible from the [PUMA service]({{site.baseurl}}/pages/puma).  See [here]({{site.baseurl}}/pages/archer2) for more on ARCHER2, and [here]({{site.baseurl}}/pages/monsoon2) for more about Monsoon2 (including how to get registered on these machines).

The UKESM1 suites are available from the [Met Office Science Repository Service](https://code.metoffice.gov.uk/trac/home/) (MOSRS).  Note that you must have a registered account to access this service.  If you are a NERC user, please [contact us]({{site.baseurl}}/pages/contact) to get one, otherwise please contact **Scientific_Partnerships AT metoffice.gov.uk** for advice about gaining access.

### UKESM release notes

The [UKESM release notes](relnotes-1.1) describe the different types of experiment which can be run using the model, how to access the suites, options for running the model (including selecting the target machine) and further configuration of the suites.  Note that these pages contain links to the MOSRS, which is only accessible to registered users (see [above](#background-and-prerequisites)).

Release notes for UKESM1.1 are [here](relnotes-1.1), while those for UKESM1 are [here](relnotes-1.0).



