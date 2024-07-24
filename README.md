# Talys Simulations
Used the talys program to simulate neutron capture in tin and other nuclei to investigate how the gamma strength function (GSF), level density, and optical model potential (OMP) models impact reaction cross sections and astrophysical rates. I used non-linear least squares mehtod to fit the GSF with SciPy packages such as opt.curve_fit: https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html. I also used Bayesian approaches (metropolis) using packages from emcee: https://emcee.readthedocs.io/en/stable/tutorials/line/. 

# Highlights:

## 119Sn(n,gamma)120Sn
### Using Opt.curve_fit (nonlinear least squares fitting)
<img src="https://github.com/user-attachments/assets/c7300b0a-27a4-4cee-850b-5b3fed8b9ff0" alt="GSFcurvefit" width="300" height="200"/>
<img src="https://github.com/user-attachments/assets/916ebc2e-15af-4152-b395-239d7676bd6d" alt="logGSFcurvefit" width="300" height="200"/>
<img src="https://github.com/user-attachments/assets/f25cb7bb-ada3-43b5-baa9-dbc80b58d955" alt="GSFPDRcomp" width="300" height="200"/>
<img src="https://github.com/user-attachments/assets/70604594-8d8e-402a-9bf4-86473b5b7792" alt="xsPDRcomp" width="300" height="200"/>
<img src="https://github.com/user-attachments/assets/d47c13fb-34b9-431a-a015-d9cc29e7bc84" alt="reactionratecomp" width="300" height="200"/>

### Using emcee (bayesian approach)
