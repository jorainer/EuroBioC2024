# Title:

An Open Software Development-based Ecosystem of R Packages for Metabolomics Data Analysis

# Authors

- Johannes Rainer, Institute for Biomedicine, Eurac Research, Bolzano, Italy
- RforMassSpectrometry contributors

# Abstract:

A frequent problem with scientific research software is the lack of support,
maintenance and further development. In particular, development by a single
researcher can easily result in orphaned and dysfunctional software packages,
especially if combined with poor documentation, missing unit tests or lack of
adherence to open software development standards.

The RforMassSpectrometry initiative aims to develop an efficient, scalable, and
stable infrastructure for mass spectrometry (MS) data analysis. As part of this
initiative, a growing ecosystem of R software packages is being developed
covering different aspects of metabolomics and proteomics data analysis. To
avoid the aforementioned problems, community contributions are fostered, and
open development, documentation and long-term support emphasized.

At the heart of the package ecosystem is the *Spectra* package that provides the
core infrastructure to handle and analyze MS data. Its design allows easy
expansion to support additional file or data formats including data
representations with minimal memory footprint or also remote data access. For
metabolomics data analysis, *xcms* is one of the core software packages for the
required preprocessing of LC-MS data. This Bioconductor package was recently
updated to reuse the RforMassSpectrometry infrastructure, enabling now also the
analysis of very large, or remote, data. This integration simplifies in addition
complete analysis workflows which can include functionality from the
*MsFeatures* package for compounding, and from the *MetaboAnnotation* package
facilitating annotation of untargeted metabolomics experiments. Public
annotation resources can be easily accessed through packages such as
*MsBackendMassbank*, *MsBackendMsp* or *CompoundDb*, the latter also allowing to
create and manage lab-specific compound databases. Finally, the *MsCoreUtils*
and *MetaboCoreUtils* packages provide efficient implementations of commonly
used algorithms, designed to be re-used in other R packages. Ultimately, and in
contrast to a monolithic software design, the package ecosystem enables to build
customized, modular, and reproducible analysis workflows.

Future metabolomics-related development will focus on improved data structures
and analysis methods for chromatographic data, and better interoperability with
other open source software including a direct integration with Python MS
libraries.


