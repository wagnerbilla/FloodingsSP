# FloodingsSP

This project concerns data files used in the experiment described in the article "Analyzing the spatial interactions between rainfall levels and flooding prediction in São Paulo".

The "dataset" folder contains the data structured in WEKA's ARFF file format. Their meanings are described below:

	FloodingsSP.arff - contains all data regarding the floodings events registered between 2015 and 2016 in São Paulo. It has rainfall precipitation partial values, the distance between a flood event and the rain gauge used to read the rainfall data, the soil impermeability in the flooding point, the HAND* index value, and a boolean-labeled class attribute indicating that a flood event occurred or not (1 and 0 values, respectively);

	FloodingsSP_raindata.arff - contains rainfall precipitation partial values and the class attribute;
	
	FloodingsSP_raindata_distance.arff - contains rainfall precipitation partial values, the distance attribute, and the labeled class;
	
	FloodingsSP_raindata_HAND.arff - contains rainfall precipitation partial values, the HAND index, and the labeled class.

I hope you enjoy the contents and can easily reproduce the experiment. All generated files are intended not to have copyright constraints; use them freely.

* HAND stands for "Height Above the Nearest Drainage," and the following reference gives more details of this index meaning:

NOBRE, A. D.; CUARTAS, L. A.; HODNETT, M.; RENNÓ, C. D.; RODRIGUES, G.; SILVEIRA, A.; SALESKA, S. Height above the nearest drainage–a hydrologically relevant new terrain model. Journal of Hydrology, Elsevier, v. 404, n. 1-2, p. 13–29, 2011.
