### Supporting materials for the B.Sc. thesis "Inferring Comparison Classes of Gradable Adjectives: The Role of Informational Goals and Sentence Structure" by Polina Tsvilodub

This repository contains materials relevant for the thesis; it is a subset of the project repository which can be found under [https://github.com/polina-tsvilodub/refpred](https://github.com/polina-tsvilodub/refpred). Our paper which this thesis builds upon can be found [here](https://psyarxiv.com/n8eyj/).

This is how the repository is structured:

## Analysis
This directory contains analysis scripts.
* `prereg-syntax-rating-expt.Rmd`: analysis of [Experiment 1](https://github.com/polina-tsvilodub/bSc-thesis/tree/master/experiments/E1-sentence-rating)
* `prereg-np-prod-expt.Rmd`: analysis of [Experiment 2](https://github.com/polina-tsvilodub/bSc-thesis/tree/master/experiments/E2-N-production)
* `prereg-comp-class-infer-expt.Rmd`: analysis of [Experiment 3](https://github.com/polina-tsvilodub/bSc-thesis/tree/master/experiments/E3-cc-inference)
* `direct-modification-pilots.Rmd`: analysis of [Experiment 4](https://github.com/polina-tsvilodub/bSc-thesis/tree/master/experiments/E4-direct-modification)
* `supplementary_fig.Rmd`: script used to generate figures for the text
* `direct-modification_power_write-up.Rmd`: script for the Bayesian power analysis for the main study of Experiment 4

## Experiments

The experiment folder contain all experiment files for the experiments reported. You can look at the experiments and preregistrations [here](https://tinyurl.com/y2b7ajg7). To run an experiment locally, clone the repo, navigate to the subdirectory of the respective experiment and run `npm install` on the command line (requires node.js). Then open the `index.html` file. All the experiments were created from the [magpie departure-point](https://github.com/magpie-ea/magpie-departure-point)


This subdirectories contain all files for the experiments.
* Experiment 1: `E1-sentence-rating` directory. The stimuli can be found in `04_trials.js`
* Experiment 2: `E2-N-production` directory. The subject-N condition can be found in `exp1-subj`, the predicate-NP condition can be found in `exp1-pred`, respectively. For both, stimuli can be accessed in `04_trials.js`
* Experiment 3: `E3-cc-inference` directory. The stimuli can be found in `04_trials.js`
* Experiment 4: `E4-direct-modification` directory. The stimuli can be found in `04_trials.js`

## Data

The data is anonymized.
* `E1_sentence_rating`: contains raw data of Experiment 1
* `E2_N_production`: contains raw data from the subject-N and predicate-N conditions of Experiment 2
* `E3_cc_inference`: contains raw data of Experiment 3
* `E4_direct_mod`: contains the raw and cleaned data files from the two pilot studies reported for Experiment 4. `results_all_pilots_tidy.csv` contains tidy data used for the power analysis.

## Model

The directory contains the WebPPL scripts for the *Refpred-RSA Model*

* `main_refpred_model_speaker-CC-choice.wppl`: the main speaker-enrichment based Refpred-RSA model proposed in the thesis
* `qud_refpred_model.wwpl`: potential alternative model based on reasoning about QUDs
* `mixture_repred_model.wppl`: potential alternative model based on utility mixture

## Writing
The directory contains the TeX-files of the thesis. The `images` directory contains the plots, the `R4Tex` directory contains csv-files with results of statistical analyses reported in the thesis.  
