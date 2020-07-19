
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Geostatistics in the Fast Lane Using R-TensorFlow and GPUs

## Andrew Zammit Mangion

### Event Description

R-Ladies Canberra will run a joint event with SSA Canberra in May, and
we are delighted to have Dr. Andrew Zammit Mangion presenting
Geostatistics in the fast lane using R-TensorFlow and GPUs. There will
be some hands-on exercises so attendees are encouraged to bring their
laptops. Please find below the instruction to download TensorFlow.

The talk will take place on the ground level, Hanna Neumann (MSI)
building (building 145) on the ANU campus. There will be refreshments in
foyer at 5.15 pm, and the talk will start at 6 pm. After the talk, there
will be a dinner at China Plate, Kambri precinct ANU. Please RSVP SSA
Canberra or R-Ladies Canberra by 27 May if you would like to attend the
dinner.

### Abstract

Geostatistics plays a key role in the analysis and prediction of spatial
and spatio-temporal phenomena. Spatial/spatio-temporal model fitting
generally involves multiple matrix operations that can be slow to
execute on a CPU. RStudio’s interface to TensorFlow provides an ideal
vehicle for doing spatial model fitting on a GPU in a fraction of the
time needed by a CPU.

I will first briefly talk about Google’s TensorFlow and the associated R
interface. I will then derive the maximum likelihood estimator for the
parameters in a simple spatial model and implement maximum-likelihood
estimation in R. Finally, I will show how to implement the same fitting
procedure using Google’s TensorFlow and illustrate the speed improvement
when using a GPU. Attendees are invited to bring their own laptop with R
and TensorFlow installed (see
<https://tensorflow.rstudio.com/tensorflow/articles/installation.html>).

### Biography

Andrew Zammit Mangion is Senior Lecturer and DECRA Research Fellow in
the National Institute for Applied Statistics Research Australia
(NIASRA), University of Wollongong, Australia. He is a co-author of two
books and he has published over 20 peer-reviewed articles in the field
of spatial and spatio-temporal statistics. He is also the author of a
number of related R packages available on CRAN, including EFDR, FRK, and
IDE. In 2013, Andrew was awarded a US National Academy of Sciences prize
for his work on the modelling and prediction of armed conflicts.
