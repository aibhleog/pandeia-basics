
## PANDEIA BASICS FOR SPECTRA

The files in this repo are meant to help build familiarity with the python version of the JWST Exposure Time Calculator, [`pandeia`](https://jwst-docs.stsci.edu/jwst-exposure-time-calculator-overview/jwst-etc-pandeia-engine-tutorial#gsc.tab=0).  Relevant resources are linked in the notebooks.  The files should be explored in this order:

1. `basics-pandeia.ipynb`  
   --> creates setup.json & result.pkl files  
2. `jwst-sim-corrected.ipynb`  
   --> uses setup.json & result.pkl files  
   --> creates simulated_....noise.txt ETC spectrum file


---------------------

### TIPS TO SPEED UP YOUR WORK / FIGURE THINGS OUT

Sometimes when I'm not sure which defaults I want to use just yet, I'll set up a single ETC sim using the online JWST ETC version. Then I download that calculation and use the "input.json" file it comes with as the starting point for my pandeia ETC sims.

This makes it easier to adjust a single thing and hit the ground running faster.  This also applies to anyone doing photometry-based JWST ETC sims, as the examples in this folder only show it for spectra.  Doing it this way, you have all of your basics set and you only need to update the pieces you care about via pandeia.



-------------------------

If there are any questions or if there is a bug in the code, feel free to reach out!

Taylor Hutchison  
Research Fellow, UT Austin  
astro.hutchison@gmail.com
