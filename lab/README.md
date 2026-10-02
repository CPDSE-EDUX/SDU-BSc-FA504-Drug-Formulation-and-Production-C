# Lab exercises

The lab part of FA504 has four exercises. Exercises 1-3 each have a data processing guide that walks through loading the data, the calculations, and the figures and tables the report needs.

Each folder contains:

* `FA504\\\_øvelseX\\\_databehandling.qmd` / `.html`: the data processing guide (Danish)
* `øvelseX\\\_script.R`: an R script with the core analysis
* `øvelseX\\\_data\\\_skabelon.xlsx`: an empty template for entering your own lab data
* `øvelseX\\\_data\\\_eksempel.xlsx`: example data, so the guide can be run before the lab

## Exercise 1: Osmolytes, erythrocyte volume and hemolysis

Erythrocytes are exposed to NaCl, sucrose, urea and benzyl alcohol. Depending on osmolality and membrane permeability the cells shrink, stay unchanged, swell or hemolyse. The exercise shows the difference between iso-osmolarity and isotonicity.

R: hematocrit correction for dilution, degree of hemolysis relative to a saponin control, unit conversion, and an optional sigmoid fit to estimate EC<sub>50</sub>.

## Exercise 2: In vitro release of nicotinates from semisolid bases

Methyl-, butyl- and hexyl nicotinate are released from four semisolid bases (o/w cream, hydrophobic ointment, hydrophilic ointment, gel), nine preparations in total.

R: correction for sample removal (as in the Caco-2 exercise class), and linear regression of the released amount per area (Q) against √t to get the Higuchi release constant for each preparation.

## Exercise 3: Stability of acetylsalicylic acid (ASA)

Hydrolysis of ASA to salicylic acid is followed spectrophotometrically at 55, 60, 65 and 70 °C.

R: pseudo-first-order fits of ln(A<sub>∞</sub> − A<sub>t</sub>) against time, an Arrhenius plot to estimate the activation energy, and extrapolation to predict shelf life (t<sub>5%</sub>) at lower temperatures.

## Exercise 4: Sterile preparation of eye drops

Mainly practical and qualitative (bubble point test, osmolality, pH), so there is no R guide.

