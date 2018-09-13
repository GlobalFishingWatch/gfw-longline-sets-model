# gfw-longline-sets-model

Model for predicting set times based on AIS transponder data.

## Model

The model is defined in `LonglineSetsModel.ipynb`.

## Data


### Tracks

The track data used to run this model is not currently available
here due to licensing restrictions. We hope to be able to
release an anonymized dataset soon so that others can run
the model on our original data.

### Day / Night calculations

These rely on internal tables at Global fishing watch, so you'll need to 
compute these in some other way, or not worry about day and night. Day /
night is not used in the model itself, it's only added to the output to 
allow easy evaluation of whether a vessel was day or night setting.

