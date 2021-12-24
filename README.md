# Viskositas

## Viskositas  — Predict viscosity of multicomponent chemical systems

_Viskositas_ (Beta) is a deep neural network and has better efficiency when compared to classic equations, neural networks in literature and other commercial software and uses the values of chemical composition and temperature to predict the viscosity value of the chemical system at the given temperature.

The database consists viscosity data with chemical composition and temperature of each sample and experimental test carried out, through tens international scientific articles composing a database with 19 different chemical species. The experimental measurements were analyzed only by the rotational method. The database has a range up to log₁₀ η=8 (or log η≈18.42) (log = logₑ) in fully liquid chemical systems.

There is a wide range of temperature in industrial processes, such as in the production, refining and solidification of steel, refining, homogenization and molding of glass and geophysical systems, for example.

All references used in mathematical and computational modeling, database, data analysis and computational model construction can be seen in the work of Duchesne et al. (2013), Chen et al. (2021) and Anjos (2021).

A GUI application can be downloaded in Versions > VISKOSITAS_Beta_0.4.1.exe (updates can be seen in versions_update) (Viskositas 1.0.1 will be avaible soon!!)

## Testing

Through a database with 6358 different chemical composition data, temperature and viscosity measured experimentally, a preprocessing was carried out relating chain depolymerization (NBO/T) and liquidus temperature (Tliq) parameters (Vargas et al., 2001). A database for training, validation and testing was separated. The test dataset was _not_ used for training the neural network.

The test database can be seen at the link:
https://docs.google.com/spreadsheets/d/1D2P586GdPxGDtiExOhSxcPoetDIa8basNCdQz-0xWNI/edit?usp=sharing.

With the test database (tab _test_data_) predictions were performed in Viskositas 1_x version, 12 literature models and in FactSage® 7.2 software (tab _predictions_). Viskositas 1_X version showed lower mean absolute error (MAE), lower standard deviation of error and higher coefficient of determination (R²) in relation to models S2, Watt-Fereday, Bomkamp, Riboud (Vargas et al., 2001), Duchesne, ANNliq (Duchesne et al., 2013) and FactSage® 7.2 (tab _metrics_).

## Advanced

The Viskositas 1_x version model is a deep neural network with arbitrary depth built using the minimum width equation developed by Kidger and Lyons (2020) to the continuous function classes endowed with an uniform norm.

A pipeline was built with a preprocessing using standard scaler and the deep neural network developed through Keras (TensorFlow backend). Training and validation graphs, computational model graph, histograms and parameter distribution can be seen at the link:
X

# Contact

- E-mail: patrick.dosanjos@outlook.com
- Linkedin: https://www.linkedin.com/in/patrick-queiroz-dos-anjos/

# License

© 2021, Patrick Queiroz dos Anjos. Licensed under the MIT License.

# References

- Duchesne, M., Bronsch, A., Hughes, R., Masset, P. Fuel. p. 38-43, v. 114, 2013. http://dx.doi.org/10.1016/j.fuel.2012.03.010

- Ziwei Chen, Minghao Wang, Zhao Meng, Hao Wang, Lili Liu, Xidong Wang. Ceramics International. p. 30691-30701, v. 47, 2021. https://doi.org/10.1016/j.ceramint.2021.07.248.

- Anjos, Patrick Queiroz dos. Ifes, Vitória, p. 51-52, 2021. https://repositorio.ifes.edu.br/handle/123456789/1195

- S. Vargas, F.J. Frandsen, K. Dam-Johansen. Progress in Energy and Combustion Science. p. 237±429, v. 27, 2001. https://doi.org/10.1016/S0360-1285(00)00023-X

- Patrick Kidger, Terry Lyons. Proceedings of Machine Learning Research. p. 1–22, v. 125, 2020. https://arxiv.org/abs/1905.08539

### Viskositas 0.4.1 (Beta) overview:

![Sem título](https://user-images.githubusercontent.com/72185214/141020004-2811ccd4-7c68-48f8-bd76-449497744628.png)
