# Data Augment

## Data Augmentation base on  AugmentTRAJ: A framework for point-based trajectory data augmentation
---

### EXAMPLE

#### ``` python .\data_augmentation.py --input JSON file --output FOLDER --mode "on", "in", "ps", "pd" --modified_ratio FLOAT ```

---
### On circle mode

#### ``` python .\data_augmentation.py --input "./data/trajectory/xxx.json" --output "./data/trajectory/xxx" --mode "On" --modified_ratio 0.5 ```
---
### In circle mode

#### ``` python .\data_augmentation.py --input "./data/trajectory/xxx.json" --output "./data/trajectory/xxx" --mode "In" --modified_ratio 0.5 ```

---
### Point Stretching mode

#### ``` python .\data_augmentation.py --input "./data/trajectory/xxx.json" --output "./data/trajectory/xxx" --mode "ps" --modified_ratio 0.5 --max_distance 0.1 --method random' ```
---
### Point Dropping mode

#### ``` python .\data_augmentation.py --input "./data/trajectory/xxx.json" --output "./data/trajectory/xxx" --mode "pd" --droping rate 0.5 ```


