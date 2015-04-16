# Open Hydrology launches open-source flood estimation software


## Background [100 W]

The Flood Estimation Handbook (FEH) (Reed et al., 1999) together with subsequent updates (e.g. Kjeldsen et al., 2008; Kjeldsen & Jones, 2009; Kjeldsen et al., 2014) represent best practice for flood estimation in the UK (e.g. Environment Agency, 2012).
The FEH provides a range of methods for estimating the magnitude of flood events of a given exceedance probability.
Hydrologists often rely on a mix of ad-hoc spreadsheets and commercial software which struggle to keep pace with current scientific literature.
This mix of tools typically results in an inefficient work-flow using out of date methods.
The recently founded Open Hydrology (OH) project provides an open source hydrological software framework.
By adopting an open source model, OH encourages the sharing of ideas, a test bed for the latest scientific methods and the continued improvement of the user experience.


## What? [200 W]

The OH project's vision is a thriving community of collaborating academics and consultants developing open source hydrological software.
One of the goals is to develop a suite of applications and software libraries fulfilling the needs of the hydrological community, for example for hydrological modelling or statistical analysis of both flood and low flows.
To date, a flood estimation statistical software library has been created for OH.
This library provides a Python programming language implementation of the recent updates (eg Kjeldsen et al, 2014) to the FEH statistical flood estimation methods.
This library can be used for example in nationwide R&D studies or integrated in end-user software or web-based platforms.
The OH Auto Statistical application was developed to demonstrate the capabilities of the flood estimation library.
The software provides a single-click experience to generate FEH compliant flood estimation reports for any catchment in the UK.
Behind the scenes, OH Auto Statistical automatically downloads National River Flow Archive (NRFA) data (CEH, 2015) and selects the most appropriate methodology including "enhanced single site" and "pooling group" analyses.


## Ethos [100 W]

Why do OH contributors choose to freely work on this project?
Well, for the same reason as those behind other very successful open source software like Mozilla Firefox, OpenOffice, Linux, GIMP and QGIS; to get a tool that works in the way they want.
OH is software for hydrologists, developed by the hydrological community.
This software development model provides a sustainable framework for the continued development of tools in conjunction with knowledge and access.
In return, developers are able to promote their technical capabilities, provide commercial training and software technical support services, provide additional services to their clients and perhaps, most importantly, get the hydrological tool they really want.


## What next? [100 W]

OH contributors are currently working on a graphical user interface for the floodestimation library, for use in more complex analysis than OH Auto Statistical allows.
OH contributors have a broad range of development plans covering rainfall-runoff, low flow analysis and tools to support hydraulic modelling, however the beauty of OH is that it provides a means for hydrologists to become developers and create the software they need to solve the challenges they face.

OH is already a success; it has a two click package to undertake an FEH statistical analysis.
What OH needs are more hydrologists testing and using the software and requests for additional features and tools.
The Auto Statistical package is already in use on commercial projects, we are keen for the hydrological community to become involved in OH; to make it better for all of us.
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
