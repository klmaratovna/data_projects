# Recovery of gold from ore.
## Research purpose:
Build a machine learning model that highlights the process of recovering gold from gold ore and calculate its efficiency.

## Research objectives:
1. Prepare input data,
2. Analyze input data,
3. Modeling data,
4. Calculate quality metric,
5. Train different models using cross-validation,
6. Test the best model on test set.

## Data:
    
- gold_recovery_train_new.csv - training sample,
- gold_recovery_test_new.csv - test sample,
- gold_recovery_full_new.csv - initial data;

## Signs:
    
- Rougher feed - feedstock
- Rougher additions (or reagent additions) - flotation reagents: Xanthate, Sulphate, Depressant
- Xanthate ** - xanthate (promoter, or flotation activator);
- Sulphate - sulfate (in this production, sodium sulfide);
- Depressant - depressant (sodium silicate).
- Rougher process (English "rough process") - flotation
- Rougher tails
- Float banks - flotation unit
- Cleaner process - cleaning
- Rougher Au - rough gold concentrate
- Final Au - final gold concentrate

## Stage parameters:

- air amount — air volume
- fluid levels - fluid level
- feed size - feed granule size
- feed rate - feed rate

## Stages:

- rougher - flotation
- primary_cleaner - primary cleaning
- secondary_cleaner - secondary cleaning
- final - final characteristics

## Parameter types:

- input — raw material parameters
- output — product parameters
- state — parameters characterizing the current state of the stage
- calculation - calculated characteristics
