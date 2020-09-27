## Refpred-RSA models

### General features of the models:
* The set of possible utterances is restricted to: "That dog is {big,small}", "That SUB_N is {big,small}", "That's a {big, small} dog", "That's a {big, small} SUB_N"
* The subject is assumed to contribute to reference, the predicate to predication.
* The representation of adjective meaning relies on degree semantics

### Models
* `main_refpred_model_speaker-CC-choice.wppl`: this is the main proposed model of the reference-predication trade-off hypothesis. It is based on speaker who may *choose the optimal comparison class* in order to communicate a particular referent.
* `mixture_refpred_model.wppl`: potential alternative model following Yoon et al. (2016), based on a speaker choosing an utterance optimal with respect to a weighted mixture of the informational goals (reference and predication). The pragmatic listener infers the weighting of these two goals. The comparison class is lifted to the level of the pragmatic listener. Predictions about the listed comparison class variable do not match expectation.
* `qud_refpred_model.wppl`:  potential alternative model of the reference-predication trade-off hypothesis. It is a QUD-based model where the speaker optimizes the utterance with respect to a particular goal, and the pragmatic listener reasons about that intended goal (following Kao et al., 2014). The pragmatic listener layer of this model does not run.  
