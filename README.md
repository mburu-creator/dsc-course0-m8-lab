# Aviation Accident Analysis


## Goal

An aircraft insurer wants to know which airplanes are safest when an accident happens: which ones are least likely to be destroyed, and least likely to leave people dead or seriously injured. They want separate answers for small and large planes.

## Data

NTSB aviation accident data from Kaggle, 1948 to 2022.

## Cleaning

- Kept professionally built airplanes from 1983 onwards.
- Filled in missing aircraft categories using the make and model.
- Created an injury rate (share of people killed or seriously injured) and a destroyed yes/no column.
- Cleaned make and model names.

Cleaned data: `data/AviationData_cleaned.csv`

## Findings

- Large planes: McDonnell Douglas, Bombardier, Embraer and Boeing had the lowest injury and destruction rates.
- Small planes: Maule and Aviat did best.
- Bad weather (IMC) accidents were about three times as likely to be severe.
- More engines did not mean safer.

## Recommendations

- Large planes: McDonnell Douglas, Bombardier, Embraer, Boeing.
- Small planes: Maule, Aviat.
- Be cautious with operators who often fly in bad weather.

## Limitations

The data only covers planes that had accidents, so it doesn't show how often each plane crashes. Some plane types have few accidents, so those results are less certain.

