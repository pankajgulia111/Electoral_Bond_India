# Indian Electoral Bond Data

This repository contains information in JSON format about Indian Electoral Bonds. The data includes details on both the receivers and the buyers of these bonds.

## Overview

Electoral Bonds are financial instruments for making donations to political parties. These bonds aim to ensure that all donations made to a party are accounted for and transparent.

The JSON data provided here includes:

- Date of Purchase
- Purchaser Name
- Denomination

- Date of Encashment
- Name of the Political Party
- Denomination

## Data Format

The data is stored in a JSON file with an array of records. Each record has the following structure:

```json
{
  "Date of Purchase": "DD/MM/YYYY",
  "Purchaser Name": "Name of the Purchaser",
  "Denomination": Amount
}
```
```json
{
  "Date of Encashment": "DD/MM/YYYY",
  "Name of the Political Party": "Name of the Political Party",
  "Denomination": Amount
}
```
## Usage

This data can be used for analysis, research, and understanding the flow of political funding in India through Electoral Bonds.

## Contribution

Contributions to this dataset are welcome. Please ensure that any added data follows the existing format and is accurate.

## License

This dataset is provided for educational and research purposes. Please use this data responsibly.
