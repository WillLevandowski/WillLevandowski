Hello! Thanks for visiting Will Levandowski’s Github / home page.

Here you will find repositories related to several of my research interests, past projects, and ongoing studies. 
These repositories contain code (almost all for MATLAB), metadata and documentation, and some figures and publications.
You are free to use any of the code you find here for non-profit purposes. Please cite the related publication, if there is one.
Better yet, let's collaborate! I would love to help apply any of these methods to new problems, new datasets, or new regions.

Contact:  
BoulderGeophysics@gmail.com

Will.Levandowski@tetratech.com

~~~~~~~~~~~~~~~~~~~~~~~~~~
ABOUT ME (Research blurbs)
~~~~~~~~~~~~~~~~~~~~~~~~~~

My research on continental deformation mostly falls on the continuum from earthquake seismology through seismotectonics to tectonophysics. 
Intraplate seismicity—-earthquakes that occur far from tectonic plate boundaries—-is my main bag, and I study both its causes (what forces are responsible for and what processes ultimately trigger intraplate earthquakes?) and its effects (how will the ground shake in response to local and regional earthquakes?). 
A blockhead when it comes to using others’ code, I specialize in developing novel approaches and hacking together new algorithms/software for questions that cannot be answered with existing techniques. 
I have been lucky enough to have experience in nearly every tectonic setting in continental North America, while collaborators and I have applied my algorithms in Antarctica, Asia, South America, and the Caribbean. 

Current work concentrates on the central and eastern United States (CEUS). 
I maintain a high-resolution crustal stress map based on inversions of moment tensors and other focal mechanisms that documents significant differences in principal stress directions and even style of deformation (contraction vs. extension) among CEUS seismic zones. 
This heterogeneity is quite at odds with the canonical understanding that stress within tectonic plates is governed by interactions at plate boundaries: For example, areas of extension in the CEUS patently oppose the nearly universal compressive plate boundaries surrounding North America.
Features left behind by previous tectonism, such as thickened or thinned crust, buoyant or anomalously dense intrusions, or hydration by mantle-derived fluids along lithospheric-scale fracture networks, can alter lithospheric density structure and give rise to gravitational body forces that may explain some of the stress variations. 
Quantification of these body forces requires reliable 3D density models. 
Enter SAnDMAn. My Simulated Annealing Density Modeling Algorithm jointly inverts gravity, flexural topography, and 3D seismic models (themselves based on joint inversion of receiver functions, ambient noise and ballistic surface wave dispersion, and Rayleigh wave ellipticity) for suites of acceptable 3D density models.
Next, 3D finite-element forward models compute the 3D full stress tensor due to these density variations with coupled edge and basal tractions, which are then compared to the normalized tensors from stress inversions to solve for the optimal boundary conditions and an internally consistent but heterogeneous intraplate stress field.
These full stress tensor fits demonstrate that features left behind by previous tectonism -- for example, dense lower crust near New Madrid (ponded mafic intrusions?) or buoyant lower crust (hydrated by mantle-derived fluids?) beneath continental sutures in the western U.S. -- can cause stress rotations and even account for 
Aftershock sequences provide independent lines of evidence for heterogeneous strain accrual across the CEUS. 
Others have suggested that intraplate aftershock sequences last for millennia, such that many modern CEUS seismic zones are merely aftershocks of historic or unknown prehistoric events, and modern seismicity is a red herring in anticipating the locations of major future events (i.e., strain accrual and stress is broadly homogeneous, so future seismicity should be heterogeneous, too). 
Building a semi-automated aftershock sequence analysis package, however, allowed investigation of hundreds of candidate mainshocks, finding that CEUS aftershock sequences do outlast plate-boundary sequences, but aftershock rates become negligible in a little less than year (M<~3.75) to a few years (M~5) to a decade or more (M>5.5), not millennia as claimed. 
Similarly, forward models that account for the Epidemic-Type Aftershock Sequence (ETAS) behavior—the fact that an aftershock has its own aftershocks, like the spread of a disease—for several specific CEUS seismic zones do not produce the observed modern seismicity rates, requiring ongoing strain accrual focused in these seismic zones.

Other lines of earthquake research include mapping how shaking dies off, or “attenuates”, with distance from earthquakes, how the ground shakes in response to local and regional earthquakes in the CEUS (shallow, local geology produces at least 400-fold difference in ground motion between stable hard-rock sites and jiggly sedimentary basins), and precisely delineating the boundary between the old, cold, low-attenuation CEUS crust and the high-attenuation western U.S. for use in the 2023 USGS National Seismic Hazard Model. 

At my “day job” as a Senior Geophysicist with Tetra Tech’s Geohazards group, primary duties involve shallow geophysical imaging, with focus on developing new algorithms using gravity, seismic, magnetic, electrical, and other geophysical data. 
These techniques have been implemented in high-resolution mapping of karst, abandoned mines and underground abandoned coal mine fires, and large-scale geotechnical studies for critical infrastructure (e.g., dams and reservoirs). 
Microgravity—microGal-precision relative gravity measurements—field surveys have become my tool of choice, as they are non-invasive, are fast and inexpensive compared to seismic or boreholes, sense a geotechnically meaningful property (e.g., in contrast to magnetic intensity), and offer resolution of the full subsurface rather than only 2D (seismic profiles) or 1D (borehole) constraints. 
Much of my gravity/potential field work centers on new methods to use spatially scattered data, rather than strictly gridded aeromag or aerogravity, since we have found that abandoning grids can as much as triple data acquisition and allows targeted dense sampling along/across features of interest or project-critical locations such as dam alignments. 
My disappointment with wavenumber-domain (Fourier) processing of scattered data has resulted in an extensive toolbox of unique(?) spatial-domain algorithms include high-/low-/band-pass filters, bespoke depth-specific (rather than wavelength-specific) filters derived by machine learning, horizontal first-/second-/third-derivative operators, and-—in addition to the forward-model based SAnDMAn-—two different 3D density tomography inversion algorithms that actually seem to work. 


