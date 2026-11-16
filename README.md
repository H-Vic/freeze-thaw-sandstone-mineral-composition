# freeze-thaw-sandstone-mineral-composition
A literature-based dataset of sandstone mineral compositions and source references for freeze-thaw cycling research

---

This repository provides a literature-based dataset of sandstone mineral compositions for research on strength deterioration under freeze–thaw cycling. The dataset accompanies Table 5 of the associated study and compiles mineral composition information from 16 published studies. Each entry retains its source-study information so that users can trace the data to the original publication.

Mineral compositions are organized into five categories, comprising quartz (`qt`), feldspar (`fs`), carbonate minerals (`carb`), clay minerals (`cl`), and other components (`other`). Values are expressed as dimensionless mass fractions between 0 and 1. The five fractions sum approximately to 1 after rounding. This consistent representation facilitates comparison and integration of mineralogical information across studies.

Users can import the data into Python, R, MATLAB, or spreadsheet software. For freeze–thaw strength modelling, each composition entry can be matched to the corresponding sandstone observations in the cited publication. The mineral fractions can then be combined with experimental variables such as porosity, freeze–thaw cycle number, temperature range, cycle duration, loading rate, and measured strength. These combined records can support regression analysis, machine learning, and comparisons of models that incorporate material composition.

Potential applications include comparing mineral composition across sandstone datasets, examining associations between mineral fractions and strength retention, assessing the contribution of mineral features to predictive models, and harmonizing material information for multi-source data analysis.

Some fractions were estimated through mass balance during data harmonization. Users should retain the associated estimation notes and consult the original publications when interpreting individual entries. Zero entries indicate that no quantified fraction was assigned to a category, and their interpretation should follow the source mineralogical descriptions. When reusing the dataset, please cite the associated study and acknowledge the original publications from which the mineral composition data were compiled.
