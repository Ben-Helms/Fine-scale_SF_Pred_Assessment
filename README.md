# Assessment of fine-scale surface fuel load predictions using TLS metrics

This is an R based processing script used to build predictive models of surface fuel load (kg m^-2) and evaluate thier performance. Fuel loads and TLS metrics from 128 0.25 m^2 clip plots collected in dry conifer forests along the Colorado Front Range are used to develop each model. Performance is evacluated using a 10-repeate 5-fold cross-validation scheme with 80% of the data used for training and 20% for testing. 

Performance metrics include: 
 * R^2
 * Root mean squared error
 * Normalized root mean squared error
 * Bias

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

