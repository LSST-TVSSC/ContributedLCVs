# ContributedLCVs
This repository collects ligtcurves of variables (geometric and intrinsic) and transients to generate a complete variable sky catalog for the planned Transients Classification Challenge. 

We want to collect lightcurves and context data (multi-band light curves are highly desired) as well as what other
contextual information is useful for characterization). 

At this time we accept transients in (nearly) any format. 

    Please create a directory in this repository with the name of the kind of transient (example SN, Microlensing, CV...) and your username (e.g. SNFedhere). If the lightcurves are models rather than observed events add Model (e.g. SLSNModelFedhere)
    
    Include in the directory a README.md that describes the content of the directory ()
    
    Inculde context information. This can be in any format, and it can be included in the README.md.
    

## Suggested format:
### The minimum number of fields for a light-curve would be: time, flux, flux-error, filter
 - time of observation (MJD with fraction to the second)  OR time to beginning of transient OR (less favourable) time from transient peak [please specify peak in which band]
 - flux (mags) [some non-optical may use numbers expressed in terms of J or eV]
 - error (mags) [same units as for the previous one, please use 'nan' or '-' if possible for missing errors, instead of mock values.
   Upper limits should be clearly tagged as such.]
 - fliter [how is the waveband to be conveyed?]
