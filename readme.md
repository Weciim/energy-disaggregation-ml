# NILM Transfer Learning Project

This repository contains the code and notebooks for my project on non-intrusive load monitoring (NILM) using deep learning and target-house calibration.

The main goal of the project is to estimate appliance-level power consumption from aggregate household electricity measurements, with a particular focus on transfer learning across buildings.

## Project focus

The project started with a broader multi-appliance setup and later moved toward more focused appliance-specific experiments.  
The fridge became the strongest case study, especially for transfer learning and target-house calibration.  
Other appliances such as washing machine and boiler were also explored during the development process.

## Repository contents

This repository includes:
- data preprocessing notebooks
- training and regression notebooks
- appliance-specific experiments
- transfer learning and calibration experiments
- dependency file for reproducibility

Large datasets, checkpoints, generated features, and local environments are not included in this repository.

## Main files

- `data-preprocess.ipynb` - general preprocessing steps
- `preprocess_targeted.ipynb` - targeted preprocessing pipeline
- `pipeline.ipynb` - main experimental pipeline
- `regression.ipynb` - regression experiments
- `hybrid-transfso-seq2pt.ipynb` - hybrid sequence-to-point model work
- `washing_machine.ipynb` - washing machine experiments
- `washing_machine_threshold.ipynb` - washing machine threshold analysis
- `boiler-data-preprocess.ipynb` - boiler preprocessing
- `boiler.ipynb` - boiler experiments

## Requirements

Install the dependencies with:

```bash
pip install -r requirements.txt
```

## Notes

This repository only contains safe and necessary project files.  
Raw datasets, prepared data folders, checkpoints, and virtual environments are intentionally excluded.

## Author

Wecim Derwich