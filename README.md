# VISKOSITAS

### VISKOSITAS  — Predict viscosity of multicomponent chemical systems

VISKOSITAS Beta is a shallow neural network and has better efficiency when compared to neural networks in literature and other commercial software and uses the values of chemical composition and temperature to predict the viscosity value of the chemical system at the given temperature.

The database consists viscosity data with chemical composition and temperature of each sample and experimental test carried out, through 75 international scientific articles composing a database with 19 different chemical species. The experimental measurements were analyzed only by the rotational method. The database has a range up to log₁₀ η=8 (or log η≈18.42) (log = logₑ) in fully liquid chemical systems.

There is a wide range of temperature in industrial processes, such as in the production, refining and solidification of steel, refining, homogenization and molding of glass and geophysical systems, for example.

Data from Yang et al. (2021) were used as test data to evaluate the efficiency of VISKOSITAS Beta in relation to the Duchesne, ANNliq, FactSage® 8.0 and VISCOSITAS (full model) models. VISKOSITAS Beta demonstrated better efficiency than the Duchesne, ANNliq, FactSage® 8.0 models and the VISCOSITAS (full version) had fewer errors in the statistical methods used. All references, values, evaluations and data are on the link below:

https://docs.google.com/spreadsheets/d/1Vj4jJJGjt5PAQSB21vI7Gfywjm5t-Feh/edit?usp=sharing&ouid=117196539981136650965&rtpof=true&sd=true

All references used in mathematical and computational modeling, database, data analysis and computational model construction can be seen in the work of Duchesne et al. (2013) and/or Anjos undergratuate thesis (2021). The synthetic minority oversampling technique for regression with Gaussian noise (SMOGN) (SEE References below) was used as an over-sampling technique to balance the data.

A GUI application can be downloaded in Versions > VISKOSITAS_Beta_0.4.0.exe.

0.4.0 (November 7th, 2021)

- use of 20 lines, instead of 30 lines of the previous version, inducing greater performance and reducing execution time;
- time execution ("Time execution (s)"), at the bottom of the application, can now be copied and pasted to check the speed of VISKOSITAS.
- addition of 1 more example, in Steelmaking, in a slag SiO₂-CaO-MgO-Al₂O₃.
- in the Help menu, the options are introduced: - "Base File (.csv)", where a file can be downloaded to be used as a basis for VISKOSITAS calculations. The .csv file has 20 different data of Yang et al. paper (SEE References below); - "Errors and Exceptions", introducing errors and exceptions in the programming and GUI of VISKOSITAS.

(other updates can be seen in versions_upate)

Contact:

- E-mail: patrick.dosanjos@outlook.com
- Linkedin: https://www.linkedin.com/in/patrick-queiroz-dos-anjos/

References:

- Anjos, Patrick Queiroz dos. Undergratuate Thesis. Ifes, Vitória, p. 51-52, 2021. https://repositorio.ifes.edu.br/handle/123456789/1195

- Ding Yang, Hanghang Zhou, Jian Wang, Zhengde Pang, Guishang Pei, Zhiming Yan, Hongxia Mao, Guibao Qiu, Xuewei Lv. Journal of Materials Research and Technology p. 1615-1622, 12, 2021. https://doi.org/10.1016/j.jmrt.2021.03.069

- Duchesne, M., Bronsch, A., Hughes, R., Masset, P. Fuel. p. 38-43, v. 114, 2013. http://dx.doi.org/10.1016/j.fuel.2012.03.010

- Nick Kunz, 2019. Licensed under the General Public License v3.0 (GPLv3). https://github.com/nickkunz/smogn

### VISKOSITAS 0.4.0 (Beta) overview:

![Sem título](https://user-images.githubusercontent.com/72185214/140663778-b15dc2c0-933a-4b8d-8854-0ac94e42ba62.png)
