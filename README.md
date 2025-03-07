# Eye-Tracking Data Processing for the Alternating Serial Reaction Time (ASRT) Task

## Overview

This repository provides scripts to process eye-tracking data from the Alternating Serial Reaction Time (ASRT) task, originally produced by [this task](https://github.com/tzolnai/Child_ASRT_eye_tracking). The pipeline includes:

- Data quality checks

- Cleaning and preprocessing

- Calculation of various measures needed for analysis

- Extensive exception handling to prevent the code from failing due to minor issues

## Credits

The code is based on [a previous version](https://github.com/tzolnai/Child_ASRT_eye_tracking) written by Emese Hallgató (@hallgatoemese) Tamás Zolnai (@tzolnai) Orsolya Pesthy (@OrsPesthy). This version was made by Orsolya Pesthy (@OrsPesthy), Flóra Hann (@hannflora), and Cintia Anna Nagy (@cintianagy). Since the last version, it has undergone substantial modifications, including:

- New calculations

- Improved exception handling

- Additional documentation

## Features

- Handles raw eye-tracking data and prepares it for statistical analysis

- Implements robust data validation to identify inconsistencies

- Adds custom metrics for in-depth analysis of ASRT performance

- Designed to be flexible and adaptable for different datasets

## Prerequisites

Python: Version 3.13 (optimally) or later

Required Packages:

pandas

numpy

os

glob


## Usage

Prepare your raw eye-tracking data.

Adjust vars_dict to match your dataset.

Run the processing scripts.

Retrieve cleaned and processed data, ready for analysis.

## Contributing

If you find issues or have suggestions, feel free to open a pull request or submit an issue.

## Future plans

- Enabling to handle more than one session's data in different folders
- Making it more userfriendly to 1) add input, 2) run just selected analyses

## License

This project is licensed under GNU GENERAL PUBLIC LICENSE 3.0
