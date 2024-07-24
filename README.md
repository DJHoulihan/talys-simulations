# Talys Simulations
Used the talys program to simulate neutron capture in tin and other nuclei to investigate how the gamma strength function (GSF), level density, and optical model potential (OMP) models impact reaction cross sections and astrophysical rates. I used non-linear least squares mehtod to fit the GSF with SciPy packages such as opt.curve_fit: https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html. I also used Bayesian approaches (metropolis) using packages from emcee: https://emcee.readthedocs.io/en/stable/tutorials/line/. 

## Highlights:

### $$^{119}$$Sn(n,$$\gamma$$)$$^{120}$$Sn
![GSFcurvefit](https://github.com/user-attachments/assets/c7300b0a-27a4-4cee-850b-5b3fed8b9ff0)
