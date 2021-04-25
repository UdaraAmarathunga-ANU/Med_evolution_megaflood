# Zanclean-flooding-Mediterranean-evolution-
Mediterranean evolution during and after the Zanclean megaflood, which refilled the desiccated Mediterranean during Messinian Salinity Crisis (MSC).

## Two main phases
1. Flooding Phase - Computes Western and Eastern Mediterranean (wMed and eMed) evolution during the Zanclean flood

2. Evolving Phase - Computes salt removal and basin evolution of eMed in the flood aftermath

In a sensitivity test, we address a rival hypothesis - Refilling of an almost-filled Mediterranean.

There are 14 scripts in total (10 for basin refilling & evolution, 1 for post-flood evolution, 3 for the sensitivity test)

These files have been named as Script 1, Script 2,.... Script 14.
Follow this order to completely run the model.

All the data files required to run the scripts (in text format) are provided.
Apart from hypsometry files, all other data files can be produced while running the scripts.
Use numpy.savetxt function given towards the end of each script to save the files if necessary.

Flooding phase is divided into 3 main stages.
Basin evolution during refilling event is calculated separately for these stages.
In order to produce complete figures, combine outputs from each flood stage.

## Reproducing manuscript figures

### Figure 2b
For wMed and eMed levels, use Script 1 and 8, respectively.
For wMed mixing depth evolution, combine outputs from Script 5,6 and 7. For eMed mixing depth evolution, use Script 10.
Change mixing efficiency (ME) value to obtain curves at different ME values.
### Figure 2c
For wMed salinity profiles, combine outputs from Script 5,6 and 7. For eMed salinity profiles, use Script 10.
### Figure 3b,c
Use Script 11
### Extended Data Fig.5 a,c & d
For wMed, use Script 1, for eMed, use Script 8.
### Extended Data Fig.5 c
Use Script 6 to obtain eMed inflow water density.
### Extended Data Fig.6 a
Use Script 7 to obtain wMed final salinity profiles. Change ME to obtain different graphs accordingly.
### Extended Data Fig.6 b
Use Script 10 to obtain eMed final salinity profiles. Change ME to obtain different graphs accordingly.
### Extended Data Fig.7 b
Use Script 14 to produce mixing depth curves. Change ME accordingly.
Use Script 12 to produce velocity and flow energy curves for the sensitivity test.
### Extended Data Fig.7 c
Use Script 12 to produce curves corresponding to a reconnection of a more-filled Mediterranean.
Use Script 1 to produce curves for a catastrophic termination (Update initial sill depth and sill width to similar values as in Script 12)

