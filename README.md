# settings_package

This repository holds individual settings aka options files for pychron.  The settings are stored in a `json` and an associated `md` is used to provide a human-readable description. 

# manifest.txt
In order to be used by pychron's settings manager this repo must have a `manifest.txt` file.  

```
spectrum.multigraph.json
spectrum.test.json
```

This file lists all the valid settings files in this `package`

# settings filename format
The settings filename must follow a specific format  
```
<group>.<name>.json
```

Where `<group>` is one of the following
```
air_report_series
air_series
arar_calculations
blank_air_series
blank_cocktail_series
blank_unknown_series
blanks
bu_report_series
cluster
cocktail_report_ideogram
cocktail_report_series
cocktail_series
composite
define_equilibration
flux
flux_visualization
gis
icfactor
ideogram
inverse_isochron
iso_evo
mdd
radial
ratio_series
regression
regression_series
series
spectrum
unknowns_report_ideogram
unknowns_report_series
vertical_flux
xy_scatter
```
and `name` is a human readable label for the settings file. 
