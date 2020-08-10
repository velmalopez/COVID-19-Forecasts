## Models

- [Auquan Data Science](#Auquan)
- [Center for Disease Dynamics, Economics & Policy](#CDDEP)
- [Columbia University](#Columbia)
- [Columbia University and University of North Carolina](#Columbia-UNC)
- [Covid-19 Simulator Consortium](#Covid19Sim)
- [Covid Act Now](#CAN)
- [Discrete Dynamical Systems](#DDS-NBDS)
- [Georgia Institute of Technology, College of Computing](#Ga_DeepCOVID)
- [Imperial College, London](#Imperial)
- [Institute of Health Metrics and Evaluation](#IHME)
- [Iowa State University](#ISU)
- [Johns Hopkins University, Infectious Disease Dynamics Lab](#JHU)
- [Karlen Working Group](#Karlen)
- [LockNQuay](#LNQ-ens1)
- [Los Alamos National Laboratory](#LANL)
- [Massachusetts Institute of Technology, COVID-19 Policy Alliance](#MIT-CovAlliance)
- [Massachusetts Institute of Technology, Operations Research Center](#MIT-ORC)
- [Northeastern](#MOBS)
- [Notre Dame University](#NotreDame)
- [Oliver Wyman](#OliverWyman)
- [Qi-Jun Hong](#QJHong)
- [Robert Walraven](#ESG)
- [University of California, Los Angeles](#UCLA)
- [University of Chicago](#UChicago)
- [University of Geneva / Swiss Data Science Center](#Geneva)
- [University of Massachusetts, Amherst](#UMass)
- [University of Michigan](#UM)
- [University of Southern California](#USC)
- [University of Texas, Austin](#UT)
- [University of Virinia, Los Angeles](#UCLA)
- [US Army Engineering Research and Development Center](#ERDC)
- [Youyang Gu (COVID-Projections)](#YYG)

## Model Descriptions

### [Auquan Data Science](https://covid19-infection-model.auquan.com/) <a name="Auquan"/>

**Model name:** Auquan

**Intervention assumptions:** These projections do not make specific assumptions about which interventions have been implemented or will remain in place.  

**Methods:** Fitted SEIR model

### [Center for Disease Dynamics, Economics & Policy](https://cddep.org/) <a name="CDDEP">

**Model name:**  CDDEP

**Intervention Assumptions:**  This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:**  Bayesian SEIR model.

**Forecasts submitted:** Cases

### [Columbia University](https://columbia.maps.arcgis.com/apps/webappviewer/index.html?id=ade6ba85450c4325a12a5b9c09ba796c) <a name="Columbia"/>

**Model name:** Columbia

**Intervention assumptions:** 
- This model assumes that contact rates will increase 5% per week over the next two weeks. The reproductive number is then set to 1 for the remainder of the projection period.
_ The model uses state-specific hospitalization data, when available. In states without hospitalization data, the model uses the national average value for hospitalization da

**Methods:** Metapopulation SEIR model

**Forecasts submitted:** Cases, deaths, and hospitalizations

### [Columbia University and University of North Carolina](https://github.com/COVID19BIOSTAT/covid19_prediction) <a name="Columbia-UNC"/>
**Model name:** Columbia-UNC

**Intervention assumptions:** This model assumes that transmission intensity will peak in early July and then gradually decline.

**Methods:** Statistical survival-convolutional model.

**Forecasts submitted:** Cases and deaths

### [Covid-19 Simulator Constorium](https://www.covid19sim.org/) <a name="Covid19Sim"/>
**Model name:** Covid19Sim

**Intervention assumptions:** 
- This model is based on assumptions about how levels of social distancing will change in the future.
- The number of new hospitalizations per day are estimated from the number of infections, using state-specific hospitalization rates.

**Methods:** SEIR model

**Forecasts submitted:** Cases, deaths, and hospitalizations

### [Covid Act Now](https://covidactnow.org/) <a name="CAN"/>
**Model name:** CAN

**Intervention assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Fitted SEIR model

**Forecasts submitted:** Deaths

### [Discrete Dynamical Systems] (https://dds-covid19.github.io/index.html) <a name="DDS-NBDS"/> 

**Model name:** DDS-NBDS

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Bayesian hierarchical model.

**Forecasts submitted:** Cases

### [Georgia Institute of Technology](https://deepcovid.github.io/) <a name="GA-DeepCOVID"/>

**Model name:** GA-DeepCOVID (formerly: GA_Tech)

**Intervention Assumptions:** 
- This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.
- Daily hospitalizations are predicted from publicly available, state-level data sources.

**Methods:** Deep learning

**Forecasts submitted:** Deaths, and hospitalizations

### [Imperial College, London](https://mrc-ide.github.io/covid19-short-term-forecasts/index.html) <a name="Imperial"/>

**Model name:** Imperial

**Intervention Assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Ensembles of mechanistic transmission models, fit to different parameter assumptions.

### [Institute of Health Metrics and Evaluation](https://covid19.healthdata.org/united-states-of-america) <a name="IHME"/>

**Model name**: IHME

**Intervention Assumptions:** 
- Projections are adjusted to reflect differences in aggregate population mobility and community mitigation policies.
- Daily hospitalizations are estimated from predictions of daily deaths, using state hospitalization rates, where available.

**Methods:** Combination of a mechanistic disease transmission model and a curve-fitting approach.

**Forecasts submitted:** Cases, deaths, and hospitalizations

### [Iowa State University](https://covid19.stat.iastate.edu/) <a name="ISU"/>

**Model name:** ISU

**Intervention Assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Nonparametric spatiotemporal model

**Forecasts submitted:** Cases, deaths, and hospitalizations

### [Johns Hopkins University](https:/github.com/HopkinsIDD/COVIDScenarioPipeline) <a name="JHU"/>

**Model name:** JHU

**Intervention Assumptions:** 
- This model assumes that the effectiveness of interventions is reduced after shelter-in-place orders are lifted.
- Daily hospitalizations are estimated from predictions of daily cases. A standard proportion is applied to all states.

**Methods:** Metapopulation SEIR model

**Forecasts submitted:** Cases, deaths, and hospitalizations

### [Karlen Working Group](https://pypm.github.io/home/) <a name="Karlen"/>

**Model name:*** Karlen

***Intervention assumptions:***
- This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.
- The model uses state-specific hospitalization data. New hospitalizations are estimated from these data, or from the estimated number of new infections that will occur in each location.

***Methods:*** Discrete time difference equations.

**Forecasts submitted:** Cases, deaths, and hospitalizations

### [LockNQuay](https://www.kaggle.com/sasrdw/locknquay)<a name="Karlen"/>
**Model name:** LNQ-ens1

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Machine learning.

**Forecasts submitted:** Cases and deaths

### [Los Alamos National Laboratory](https://covid-19.bsvgateway.org/) <a name="LANL"/>

**Model name:** LANL

**Intervention assumptions:** 
- This model assumes interventions in place on the first day of the forecast will remain in place for the next four weeks.
- State demographics and age-group symptomatic case hospitalization rates are used to estimate the daily number of hospitalizations, based on estimates of the total number of infections.

**Methods:** Statistical dynamical growth model accounting for population susceptibility

**Forecasts submitted:** Cases, deaths, and hospitalizations

### [Massachusetts Institute of Technology](https://www.covidalliance.com/) <a name="MIT-CovAlliance"/>

**Model name:** MIT-CovAlliance

**Intervention Assumptions:** The projections assume that current interventions will remain in place indefinitely.

**Methods:** SIR model 

**Forecasts submitted:** Cases 

### [Massachusetts Institute of Technology](https://www.covidanalytics.io/projections) <a name="MIT-ORC"/>

**Model name:** MIT-ORC

**Intervention Assumptions:** The projections assume that current interventions will remain in place indefinitely.

**Methods:** SEIR model 

**Forecasts submitted:** Cases and deaths

### [Northeastern](https://covid19.gleamproject.org/) <a name="MOBS"/>

**Model name:** MOBS (Laboratory for the Modeling of Biological + Socio-technical Systems)

**Intervention assumptions:** The projections assume that social distancing policies in place at the date of calibration are extended for the future weeks.

**Methods:** Metapopulation, age-structured SLIR model

### [Notre Dame University](https://github.com/confunguido/covid19_ND_forecasting) <a name="NotreDame"/>

**Model name:** NotreDame

**Intervention assumptions:** The model accounts for each  state's school-closure and stay-at-home policies.

**Methods:** Agent-based model

### [Oliver Wyman](https://pandemicnavigator.oliverwyman.com/) <a name="Oliver Wyman">
**Model name:** Oliver Wyman

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Time-dependent SIR model for detected and undetected cases.

**Forecasts submitted:** Cases and deaths

### [Qi-Jun Hong](https://qjhong.github.io/) <a name="QJHong">
**Model name:** QJHong

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Machine learning using case data and mobility data.

**Forecasts submitted:** Cases and deaths

### [Robert Walraven](http://rwalraven.com/COVID19/) <a name="ESG">
**Model name:** ESG

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Fitting reported data to multiple skewed gaussian distributions.

**Forecasts submitted:** Cases and deaths

### [University of California, Los Angeles](https://covid19.uclaml.org/) <a name="UCLA"/>

**Model name:** UCLA

**Intervention assumptions:** 
- This model assumes that contact rates will increase as states reopen. The increase in contact rates is calculated for each state.
- The number of new hospitalizations per day are estimated from the number of infections, using state-specific hospitalization rates.

**Methods:** Modified SEIR model

**Forecasts submitted:** Cases and deaths

### [University of Chicago](https://github.com/cobeylab/covid_IL) (forecasts for Illinois only) <a name="UChicago"/>

**Model name:** UChicago

**Intervention assumptions:** These forecasts assume that transmission rate will increase by 10% when stay-at-home policies are lifted.

### [University of Geneva / Swiss Data Science Center](https://renkulab.shinyapps.io/COVID-19-Epidemic-Forecasting/) (one-week ahead forecasts only) <a name="Geneva"/>

**Model name:** Geneva

**Intervention assumptions:** The projections assume that social distancing policies in place at the date of calibration are extended for the future weeks.

**Methods:** Exponential and linear statistical models fit to the recent growth rate of cumulative deaths.

**Forecasts submitted:** Cases and deaths

### [University of Massachusetts, Amherst](https://reichlab.io/) <a name="UMass"/>

**Model names:** UMass-MB, Ensemble

**Intervention assumptions:**
-	UMass-MB: These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.
-	Ensemble: The ensemble forecasts include all submitted forecasts, derived from models that assume certain social distancing measures will continue and models that assume those measures will not continue. 

**Methods:**
-	UMass-MB: Mechanistic Bayesian compartment model
-	Ensemble: The ensemble is a combination of 4 to 20 models, depending on the availability of forecasts for each location. To ensure consistency, the ensemble includes only models with 4 week-ahead forecasts.

**Forecasts submitted:** Cases and deaths

### [University of Michigan](https://gitlab.com/sabcorse/covid-19-collaboration) <a name="UM">
**Model name:** UM

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Ridge regression.

**Forecasts submitted:** Cases and deaths

### [University of Southern California](https://scc-usc.github.io/ReCOVER-COVID-19/#/) <a name="USC">
**Model name:** USC

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** SIR model.

**Forecasts submitted:** Cases and deaths

### [University of Texas, Austin](https://covid-19.tacc.utexas.edu/projections/) <a name="UT"/>

**Model name:** UT

**Intervention assumptions:** This model estimates the extent of social distancing using geolocation data from mobile phones and assumes that the extent of social distancing does not change during the period of forecasting. The model is designed to predict confirmed COVID-19 deaths resulting from only a single wave of transmission.

**Methods:** Nonlinear Bayesian hierarchical regression with a negative-binomial model for daily variation in death rates.

### [University of Virginia](https://biocomplexity.virginia.edu/)<a name="UVA">

**Model name:** UVA

**Intervention assumptions:** There are two different assumptions influencing this ensemble model. Two of the three models assume that the effects of interventions are reflected in the observed data and will continue going forward, while the third model assumes that interventions will change in the future.

**Methods:** This forecast is an ensemble of three different models: An auto-regressive model, a machine learning (long short-memory) model, and a SEIR model.

**Forecasts submitted:** Cases and deaths

### [US Army Engineering Research and Development Center](https://github.com/erdc-cv19/covid19-forecast-hub) <a name="ERDC"/>

**Model name:** ERDC

**Intervention assumptions:** 
- These projections assume that current interventions will not change during the forecasted period.
- The number of new hospitalizations per day are estimated from the number of infections, using state-specific hospitalization rates.

**Methods:** SEIR model

**Forecasts submitted:** Cases, deaths, and hospitalizations

### [Youyang Gu (COVID-Projections)](https://covid19-projections.com/about/) <a name="YYG"/>

**Model name:** YYG

**Intervention assumptions:** The projections assume that strong social distancing policies will remain in place through the projected period.

**Methods:** SEIS mechanistic model.

