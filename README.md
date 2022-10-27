# inla-sandbox

A collection of notebooks written by [Jeff Eaton](https://www.imperial.ac.uk/people/jeffrey.eaton) on spatio-temporal modelling with `R-INLA` and `TMB`.
I've rendered and uploaded these for my own reference.
Perhaps they might be useful to you too:

* [arima110-inla-rgeneric](arima110-inla-rgeneric.html): demonstration of the AR1 and ARIMA(1, 1, 0) models using `R-INLA`'s `rgeneric` framework
* [inla-internals](inla-internals.html): understanding internal details of `R-INLA` via experimentation, such as constants added to the diagonal for numerical stability, scaling of precision matrices, and implementation of Kronecker products via the `group` option
* [inla-tmb-constraints](inla-tmb-constraints.html): fitting a sequence of models (intercept, ICAR, RW1, ICAR + RW1, ICAR x IID, ICAR x IID with constraints, ICAR x RW1, ICAR x RW1 with constraints, ICAR + RW1 + ICAR x RW1, AR1, IID x AR1 and ICAR x AR1) to the `brainNM` dataset
* [tmb-bym2](tmb-bym2.html): efficient implementation of the BYM2 model in `TMB`
