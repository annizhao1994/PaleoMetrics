


Figure 2 polar amplification
Information:

Top row: spatial maps\
Bottom row: lat.averaged \
(1) MH\
     Ensemble mean spatial map: Computed via using the files in data_netcdf in pmip_p2fvar_analyzer\
     lat averaged plot: calculated from the files in data_netcdf in pmip_p2fvar_analyzer\
     Proxy data: Bartlein et al (2014)\
Problems: Need to confirm Temp12k data uncertainties.\
(2) LGM\
 Ensemble mean spatial map: Computed via using the PMIP4 LGM files given by Masa\
     lat averaged plot: calculated from Masa's files\
     Proxy data:  Cleator et al (2019) Tierney et al (2020) \
Problems: Only found gridded proxy data for Cleator 2019. Need to find site level dataset\
\
(3) LIG\
     Ensemble mean spatial map: output from the LIG paper\
     lat averaged plot: from the LIG paper\
    Proxy data: all annual anomaly used in the LIG paper\
Problems: In pmip_p2fvar_analyzer,  tas_spatialmean_ann MPI lig127k is upside down. Have fixed that in this figure\
\
(4)mPWP\
    Map and lines are adopted from Figure 1a and 1c of Haywood et al. (2021)\
   Proxy data: 
Foley and Dowsett (2019)  Same as in Haywood et al. (2021)\
\
(5) EECO\
   Simulations are downloaded from Lunt et al. (2021) DeepMIP paper.\
   Proxy data: EECO temperature uses Hollis et al. (2019). PI uses regireeded MMM of piControl simulations in Lunt et al. (2021) Supplement. See the cell pi1_model in notebook.
Problems: Need to confirm which model to include. According to the email on 26 Nov 2020, the ensemble should include 2 CESM 1.2 (6xCO2, 9x), 2 GFDL (4x, 6x), INMN (6x), COSMOS (4x), CCSM4_K and NorESM1-F (4x)\
