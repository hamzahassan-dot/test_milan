
* **[AOCL-BLIS](#aocl-blis)**
* **[Documentation](#documentation)**
* **[Contacts](#contacts)**
* **[Acknowledgments](#Acknowlegemnts)**

AOCL-BLIS
------------------

AOCL-BLIS is the optimized BLIS implementation targeted for AMD EPYC<sup>TM</sup> CPUs. It is based on FLAME/BLIS. All the features and functionalities of FLAME/BLIS are retained and supported as it is with this library.

AOCL-BLIS has been implemented with various optimizations such as follows:

*	Reduced framework overheads
*	Vectorized kernels for AMD EPYC<sup>TM</sup> CPUs
*	Optimal selection of the algorithm/code paths

Starting from AOCL-BLIS version 3.1, AOCL-BLIS has added support for the following:

*	Automatic selection of number of threads using AOCL dynamic feature
*	Windows version of AOCL-BLIS with Microsoft Visual Studio integration

Starting from AOCL-BLIS version 3.2, AOCL-BLIS has added support for the following:

*	AOCL Progress support feature.
*	Runtime Thread Control using OpenMP API.

Starting from AOCL-BLIS version 4.0, AOCL-BLIS has added support for the following:

*      	zen4 support for AOCL-BLIS.
*       Dynamic dispatcher support for zen4 config.
*	LPGEMM support

For the general overview about BLIS and the common features, refer the BLIS readme available (https://github.com/flame/blis/blob/master/README.md).

Documentation
-------------

The AOCL user guide contains detailed information on the following:

*	Installation
*	Debugging
*	Performance optimization
*	Examples

For more information, refer AOCL user guide (https://developer.amd.com/amd-aocl/#userguide).

You can find the developer documents in the docs folder of this repo.


Contacts
--------

AOCL-BLIS is developed and maintained by AMD. For support or queries, you can email us on toolchainsupport@amd.com.

You can also raise any issue/suggestion on the GitHub repository (https://github.com/amd/amd-blis/issues).


