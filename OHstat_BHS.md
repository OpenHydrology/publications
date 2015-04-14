# Open Hydrology launches open-source flood estimation software


## Background [100 W]

The Flood Estimation Handbook (Reed et al., 1999) together with subsequent updates (e.g. Kjeldsen et al., 2008; Kjeldsen & Jones, 2009; Kjeldsen et al., 2014) represent best practice for flood estimation in the UK (e.g. Environment Agency, 2012).
The guidance within these documents, provide a broad range of methods for estimating the magnitude of flood events of a given magnitude.
These methods fall into two groups; rainfall-runoff modelling and statistical assessments.
Hydrologists often rely on a mix of ad-hoc spreadsheets and commercial software which struggle to keep pace with current scientific literature and generate output in varied formats, causing problems for calculation checks.
This awkward mix of tools largely results in an inefficient work-flow working with out of date methods.
The recently founded Open Hydrology (OH) project provides a framework for developers and academics to distribute new methods to practitioners.
By adopting an open source model OH encourages the sharing of ideas, a test bed for the latest scientific methods and the continued improvement of the user experience.


## What? [200 W]

The OH project consists of collaborating academics and consultants who are developing open source software for hydrologists.
Our goal is to develop a suite of packages that fulfil the needs of the hydrological community enabling us to use the latest published hydrological methods for modelling and statistics for both flood and low flow analysis.
OH developers have already released the floodestimation library.
The library provides a python implementation of the latest statistical **(ref)** flood estimation methods including pooled analysis, enhanced single site and transferring local gauged data.
The floodestimation library is used in the OH Auto Statistical package to automatically create flood frequency reports by right clicking on a catchment descriptor file and choosing to run a report, making the process of generating a default flood frequency curve a matter of seconds rather than minutes.
The floodestimation library downloads the latest Peak Flow Data (CEH, 2015) and allows the manual editing or addition of flow records.


## What next? [100 W]

We're currently working on a graphical user interface for the floodestimation library, for use in more complex analysis than OH Auto Statistical allows.
OH contributors have a broad range of development plans covering rainfall-runoff, low flow analysis and tools to support hydraulic modelling, however the beauty of OH is that it provides a means for hydrologists to become developers and create the software they need to solve the challenges they face.

OH is already a success; it has a two click package to undertake an FEH statistical analysis.
What OH needs are more hydrologists testing and using the software and requests for additional features and tools.
The Auto Statistical package is already in use on commercial projects, we want the wider hydrological community to become involved in OH; to make it better for all of us.
If you also have time and skill to spare please dip into the source code and help out with writing.
The best way to find out more and try it out is by going to the the OH website [open-hydrology.org](open-hydrology.org) where you can find links to the latest software release, the project's LinkedIn, Wiki and GitHub (source code) repository.


## References

CEH, 2015, *Peak Flow Data Overview*, http://www.ceh.ac.uk/data/nrfa/peakflow_overview.html, accessed 2015-04-12.

Environment Agency, 2012, *Flood Estimation Guidelines*, Operational instruction 197_08.

Institute of Hydrology, 1975, *Flood Studies Report*, Natural Environment Research Council.

Kjeldsen, T., Jones, D., Bayliss, A., Spencer, P., Surendran, S., Stefan, L., Webster, P., & McDonald, D., 2008, *Improving the FEH statistical method*, In: Flood & Coastal Management Conference 2008, University of Manchester, 1-3 July 2008. Environment Agency/Defra.

Kjeldsen, T. R., & Jones, D. A., 2009, *An exploratory analysis of error components in hydrological regression modeling*, Water Resources Research, 45(2).

Kjeldsen, T. R., Jones, D.A., & Morris, D.G., 2014, *Using multiple donor sites for enhanced flood estimation in ungauged catchments*, Water Resources Research, 50(8): 6646-6657.

Reed, D., Faulkner, D., Robson, A., Houghton-Carr, H., & Bayliss, A., 1999, *Flood Estimation Handbook*, Wallingford: Institute of Hydrology.
