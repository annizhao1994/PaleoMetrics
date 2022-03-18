# PaleoMetrics

## Figure 1
### See summary,csv for information

### Files
1. Figure 1.xlsx contains all data
2. csvfiles folder contains the files used in plotting.
3. color_information.csv contains the defined colors for individual models

### Notebooks:
1. Figure1_global_mean_temperature_anomaly(Figure7.19).ipynb
2. Box TS.2, Figure 2.ipynb

### Things need to do/confirm:
For Figure 1:
1. Do we want to include Lunt et al. (2013) LIG and Lunt et al. (2012) EoMIP?
2. Do we want to mark models by different colors? If so, I need to rename models in mPWP and EECO files.
3. I need to check obervation values.
4. I need to check ECS values.

----------------------------
## Figure 2
Top row: spatial maps
Bottom row: lat.averaged 
### (1) MH
     Ensemble mean spatial map: Computed via using the files in data_netcdf in pmip_p2fvar_analyzer
     lat averaged plot: calculated from the files in data_netcdf in pmip_p2fvar_analyzer
     Proxy data: Bartlein et al (2014)
Problems: Temp12k data don’t have uncertainties, so not plot here at the moment.
### (2) LGM
     Ensemble mean spatial map: Computed via using the files in data_netcdf in pmip_p2fvar_analyzer
     lat averaged plot: calculated from the files in data_netcdf in pmip_p2fvar_analyzer
     Proxy data:  Cleator et al (2019) Tierney et al (2020) 
Problems: Need to compute more LGM simulations via CVDP
                 Only found gridded proxy data for Cleator 2019. Need to find site level dataset

### (3) LIG
     Ensemble mean spatial map: output from the LIG paper
     lat averaged plot: from the LIG paper
    Proxy data: all annual anomaly used in the LIG paper
Problems: In pmip_p2fvar_analyzer,  tas_spatialmean_ann MPI lig127k is upside down.

### (4)mPWP
    Map and lines are adopted from Figure 1a and 1c of Haywood et al. (2021)
   Proxy data: Foley and Dowsett (2019)  Same as in Haywood et al. (2021)

### (5) EECO
    Simulations are downloaded from Lunt et al. (2021) DeepMIP paper
Problems: Fail to create ensemble mean, error comes from COSMOS simulations.
Need to confirm which model to include. According to the email on 26 Nov 2020, the ensemble should include 2 CESM 1.2 (6xCO2, 9x), 2 GFDL (4x, 6x), INMN (6x), COSMOS (4x), CCSM4_K and NorESM1-F (4x)


