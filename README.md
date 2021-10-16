# VISKOSITAS

### VISKOSITAS  — Predict viscosity of multicomponent chemical systems

VISKOSITAS Beta is a shallow neural network and has better efficiency when compared to neural networks in literature and other commercial software and uses the values of chemical composition and temperature to predict the viscosity value of the chemical system at the given temperature.

The database consists viscosity data with chemical composition and temperature of each sample and experimental test carried out, through 75 international scientific articles composing a database with 19 different chemical species. The experimental measurements were analyzed only by the rotational method. The database has a range up to log₁₀ η=8 (or log η≈18.42) (log = logₑ) in fully liquid chemical systems.

There is a wide range of temperature in industrial processes, such as in the production, refining and solidification of steel, refining, homogenization and molding of glass and geophysical systems, for example.

Data from Yang et al. (2021) were used as test data to evaluate the efficiency of VISKOSITAS Beta in relation to the Duchesne, ANNliq, FactSage® 8.0 and VISCOSITAS (full model) models. VISKOSITAS Beta demonstrated better efficiency than the Duchesne, ANNliq, FactSage® 8.0 models and the VISCOSITAS (full version) had fewer errors in the statistical methods used. All references, values, evaluations and data are on the link below:

https://docs.google.com/spreadsheets/d/1Vj4jJJGjt5PAQSB21vI7Gfywjm5t-Feh/edit?usp=sharing&ouid=117196539981136650965&rtpof=true&sd=true

All references used in mathematical and computational modeling, database, data analysis and computational model construction can be seen in the work of Duchesne et al. (2013) and/or Anjos undergratuate thesis (2021). The synthetic minority oversampling technique for regression with Gaussian noise (SMOGN) (SEE References below) was used as an over-sampling technique to balance the data.

#### A GUI application (VISKOSITAS — Beta) can be downloaded in VISKOSITAS_Beta_0.2.0.exe!!!

0.2.0 (October 10th, 2021)

- Fixed a bug in time (t (s)) related in high percentage/mass fraction in V₂O₅ (vanadium pentoxide).
- Decreasing the time execution.

0.3.0 (October 16th, 2021)

- Added 30 lines for calculating viscosity.
- Using Cut, Copy and Delete in the Edit menu. There is also the Paste mechanism (classic "Ctrl+C Ctrl+V") in the application.
- Button "Calculate Viscosity (log η)" in the main menu.
- Time execution (t (s) ) in the bottom of the application. Decreasing the time execution.

Contact:

- E-mail: patrick.dosanjos@outlook.com
- Linkedin: https://www.linkedin.com/in/patrick-queiroz-dos-anjos/

References:

- Anjos, Patrick Queiroz dos. Undergratuate Thesis. Ifes, Vitória, p. 51-52, 2021. https://repositorio.ifes.edu.br/handle/123456789/1195

- Ding Yang, Hanghang Zhou, Jian Wang, Zhengde Pang, Guishang Pei, Zhiming Yan, Hongxia Mao, Guibao Qiu, Xuewei Lv. Journal of Materials Research and Technology p. 1615-1622, 12, 2021. https://doi.org/10.1016/j.jmrt.2021.03.069

- Duchesne, M., Bronsch, A., Hughes, R., Masset, P. Fuel. p. 38-43, v. 114, 2013. http://dx.doi.org/10.1016/j.fuel.2012.03.010

- Nick Kunz, 2019. Licensed under the General Public License v3.0 (GPLv3). https://github.com/nickkunz/smogn

### VISKOSITAS 0.3.0 overview


![Sem título](https://user-images.githubusercontent.com/72185214/137604144-43d846c6-3eac-4b91-9446-387e6dfc431f.png)
