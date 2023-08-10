# Data
We have three datasets that are part of the gold extraction process, `gold_recovery_train.csv`, `gold_recovery_test.csv`, and `gold_recovery_full.csv` and several fields.

For the Technological process:

- *Rougher feed*: raw material

- Rougher additions(or reagent additions) — flotation reagents:

  Xanthate, Sulphate, Depressant

  - *Xanthate*: promoter or flotation activator;
  - *Sulphate*: sodium sulphide for this particular process;
  - *Depressant*: sodium silicate.

- *Rougher process*: flotation

- *Rougher tails*: product residues

- *Float banks*: flotation unit

- *Cleaner process*: purification

- *Rougher Au*: rougher gold concentrate

- *Final Au*: final gold concentrate

We also have several parameters:

- *air amount*: volume of air
- *fluid levels*
- *feed size*: feed particle size
- *feed rate*

Features are named like `[stage].[parameter_type].[parameter_name]`

Possible values for `[stage]`

- *rougher*: flotation
- *primary_cleaner*: primary purification
- *secondary_cleaner*: secondary purification
- *final*: final characteristics

Possible values for `[parameter_type]`

- *input*: raw material parameters
- *output*: product parameters
- *state*: parameters characterizing the current state of the stage
- *calculation*: calculation characteristics

# Description
Prepare a machine learning model that helps predict the amount of gold extracted from gold ore. 
