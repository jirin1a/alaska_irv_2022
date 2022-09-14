# alaska_irv_2022
Code to process IRV ballots cast in the Alaska Special Election 2022

### `notebooks` 
Content: jupyter notebook to read the JSON.zip, parse the IRV election, identify over/undervote, save as CSV

### `data`
Content: 

Our version of the csv file. This file contains 1 ballot per row and includes all over/undervotes

A "profile file" that contains unique ranknigs along with their count. Over/undervotes have been dealt with (ballots either discarded or truncated)


