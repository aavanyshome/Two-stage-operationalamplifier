I designed a schematic and layout of two stage operation amplifier in cadence virtuoso using SCL 180nm PDK.
the schematic consist of one resistor where current can be tracked , NMOS tail current (current mirror), Diffrential pair, PMOS current mirror and common source amplifier.
i calculated W/L values, fingers and multiplier to get desired gain,phase margin and ugb
As diffrential pair and PMOS current mirror are crucial in opamp, i used matching techniques like interdigitization for current mirror and common centroid for diffrential pair. I also placed both NMOS and PMOS well ring around both of them to avoid noise.
using calibre i checked the drc and lvs and cleared all the errors.
did the parasitic extraction.
