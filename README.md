# Assessment of fine-scale surface fuel load predictions using TLS metrics

This is an R based processing script used to build predictive models of surface fuel load, then evaluate thier performance using 10-repeate 5-fold cross-validation.

Modeling stratagies include:
 * Random Forest
 * Elastic Net
 * Multiple linear regression via leaps and bounds variable selection

Surface fuel components include:
  * Fine dead surface fuels
  * Large-diameter downed dead woody fuels
  * Herbaceous fuels
  * Live woody fuels
  * Total surface fuels

