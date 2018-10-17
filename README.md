# Project McNulty Proposal
# Predicting Pitch Selection for Major League Baseball
### Alex Bell


## Domain
In major league baseball, the ability for batters to anticipate the type of pitch that the pitcher throws is a crucial skill. Batters have approximately 1/4 of a second to decide whether or not to swing at a pitch.

The goal of this project is to predict pitch types based on multiple factors such as game situation, the balls-strikes count, left or right-handed batters and pitchers. 

The website baseballsavant.mlb.com contains dataset of every pitch thrown during the 2018 regular season. There are over 720,000 recorded pitches with each measured on 63 features. 

Pitch types will be classified into various pitch types such as fastball, curveball, slider and change-up. The data will be split into training and test sets. A model for prediction will be developed on the training set and checked for usefullness on the test set. 

## Data

Variable         | Type       | Description
------------     | ---------- | ------------
Pitch Type |Response-What we are trying to predict |  Fastball, Curveball, Slider, Changeup
Count || 0-0, 0-1, ... 3-2
Pitcher Handedness | | LH or RH
Game Date 
Team |  
Runners On | | Empty, 1st, 1st & 2nd, ... Loaded
Inning || 1-9, or extra
Pitch Zone || locations 1-13
Outs || 0, 1, 2
Batter Handedness || LH or RH
Home or Away || 
Opponent
Game Situation || Tying Run, Go-ahead Run, etc.
IF alignment || Standard, Strategic, Shift
OF alignment || Standard, Strategic, Shift




