This Repository is intended to accompany the paper 'Modeling the Historical Evolution of the Karakoram's Largest Glaciers' from Minallah et al.. It is in a preliminary condition and will be updated throughout the review-process.

The fundament of the code is a copy of OGGM v1.5.3. On top of this other special functions only relevant for this study were added. In particular the additional added functions are:

- added the dynamic mu star calibration, which was also added later to the base of OGGM (https://github.com/pat-schmitt/hist_evol_largest_Karakorams_glaciers/blob/main/oggm/core/flowline.py#L5024)
- added function to calculate Glens A parameter out of Temperature (https://github.com/pat-schmitt/hist_evol_largest_Karakorams_glaciers/blob/main/oggm/workflow.py#L808)
- added adapted version of calibrate_inversion_from_consensus which calibrates fs instead of A to match the consensus volume at inversion (https://github.com/pat-schmitt/hist_evol_largest_Karakorams_glaciers/blob/main/oggm/workflow.py#L866)
- added adapted plotting functions (https://github.com/pat-schmitt/hist_evol_largest_Karakorams_glaciers/blob/main/oggm/graphics.py#L692)


Here is the original OGGM repository for more information about the model: https://github.com/OGGM/oggm
