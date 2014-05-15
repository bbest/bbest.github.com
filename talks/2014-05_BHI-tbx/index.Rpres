OHI Toolbox for the Baltic
========================================================
author: Ben Best (bbest@nceas.ucsb.eduas)
date: 2014-05-14

http://bbest.github.io/talks/2014-05_BHI-tbx


Overview
====

- Goals
    +  
- Demo
    + install
    + Global
    + Baltic
    
Spatial Reporting Units
====
- Spatial reporting units
    * eez x basin = eez_basin
    * vs: 
        + ICES (FIS)
        + 0.5 deg AquaMaps/IUCN (SPP)
        + SAUP (FIS)
        + HELCOM (CW, pressures...)
        + global region
    * aggregation / disaggregation
        + eg fraction of shoreline
    * thiessen polys out, diff't buffer regions
- Architecture
- R packages

Install
====
```
devtools::install_github('ohi-science/ohigui')
devtools::install_github('bbest/ohicore')
ohigui::launchApp('')
```


Technical Extras
====
- Github
    * setup accounts
    * cycle keywords
    * 
- CSVs
    * OpenOffice / Libre vs Excel
        - Unicode support. screen of file open and characters. can save as xls and use `gdata::read.xls`
        - file locking. reload
    

- tbx overview
    + ohi-science.org: papers, data (eg Nature, Brazil), code: ohicore, ohiprep, ohibaltic (bbest -> ohi-science), install, create regions
    + Malaysia ex w/ gadm
    + keeping up w/ the Jones's
    + s/w arch: shiny (bootstrap ui), glimmer,
    + arcgis cum impacts screen
- redo rgns w/out squiggles
- show buffers
    + suggest water marine directive 1 km from offshore islands
    + terminology: assessment, scenario (simulation), regions, goals, subgoals (supra goals)
    + code to install and simulate (Jasper: simulate last 30 yrs, see blip in recovery. Henn's figure. sHM to simulate policy diff in eutrophication (runoff and plume modeling) on CW into future, capture chg in context of all other health goals. See tradeoffs.)
    + file inspection, R help documentation (PDF)
    + open source, cross platform, repro big science, issues and code, discussion online, rollback versions (code -> products), facilitates quantitative discussion
    +
- aggregate up to EEZ or basin
- map_linewidth and map_polytransparency
- raster sampling. Plus HELCOM layers. CW, Jasper, eutrophication (the N word)
- next: Chesapeake Bay
- other data besides goal by goal
    + resilience: governance factors. treaties, agreements, actual realization?  in context of SRC
    + pressures: easy w/ existing Halpern plus HELCOM
- next steps
    + get rgn weightings by popn, area, coastal strip, revenue etc and disaggregate global layers more appropriately
    + tbx improvements: fold ohigui into ohicore, make available as online mapper (free w/ glimmer), comparison report of scenarios (ie simulations), description page per output / layer, doc process using data layer packages, viz integrating hist w/ map (JS doc on improvements)
    + uncertainty
