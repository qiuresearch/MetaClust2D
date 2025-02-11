# RNA Properties from Chemical Mapping Data 
The models we are going to analyze predict several RNA features, such as stability and structure, from the chemical mapping data. 


## Background
The best place to start is the Kaggle [OpenVaccine gitub repository](https://github.com/eternagame/KaggleOpenVaccine) where you can learn a lot more about the data and models.

This exersise follows the steps provided by EternaBench (https://github.com/eternagame/EternaBench) and the Kaggle OpenVaccine project (https://github.com/eternagame/KaggleOpenVaccine).

More scientific discussion can be found in the 2022 paper (https://www.nature.com/articles/s42256-022-00571-8). 

## data

1. Train and test sets provided by [OpenVaccine](https://github.com/eternagame/KaggleOpenVaccine/tree/main/data/Kaggle_RYOS_data)

The .csv file contains almost the same columns as our pandas dataframe described below.


2. ChemMapping_Full_10Jul2021_nr80.pkl in the *data* folder

The file can be read in via *import pandas as pd; df=pd.read_pickle()*

The original set is obtained from [EternaBench](https://github.com/eternagame/EternaBench/tree/master/data). The data is a pickle file that contains a pandas DataFrame with the following columns:

    * `id` - the id of the RNA sequence
    * `sequence` - the RNA sequence
    * `reactivity` - the reactivity values for each nucleotide
    * `deg_Mg_pH10` - the degradation values for each nucleotide at pH 10
    * `deg_Mg_50C` - the degradation values for each nucleotide at 50C
    * `deg_pH10` - the degradation values for each nucleotide at pH 10
    * `deg_50C` - the degradation values for each nucleotide at 50C
    * `reactivity_error` - the reactivity error values for each nucleotide
    * `deg_error_Mg_pH10` - the degradation error values for each nucleotide at pH 10
    * `deg_error_Mg_50C` - the degradation error values for each nucleotide at 50C
    * `deg_error_pH10` - the degradation error values for each nucleotide at pH 10
    * `deg_error_50C` - the degradation error values for each nucleotide at 50C
    * `sequence_length` - the length of the RNA sequence
    * `structure` - the RNA structure
    * `predicted_loop_type` - the predicted loop type
    * `seq_scored` - the number of nucleotides scored
    * `reactivity_error_norm` - the normalized reactivity error values for each nucleotide
    * `deg_error_Mg_pH10_norm` - the normalized degradation error values for each nucleotide at pH 10
    * `deg_error_Mg_50C_norm` - the normalized degradation error values for each nucleotide at 50C
    * `deg_error_pH10_norm` - the normalized degradation error values for each nucleotide at pH 10
    * `deg_error_50C_norm` - the normalized degradation error values for each nucleotide at 50C
    * `reactivity_norm` - the normalized reactivity values for each nucleotide
    * `deg_Mg_pH10_norm` - the normalized degradation values for each nucleotide at pH 10
    * `deg_Mg_50C_norm` - the normalized degradation values for each nucleotide at 50C. 


## Tasks

### 1. Gain familarity with the OpenVaccine dataset



### 2. Select and run some models in the OpenVaccine models folder


### 3. Apply the selected models on test sequences and analyze model behaviors as we discussed

### 3. Develop our own model

