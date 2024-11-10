# NFL Big Data Bowl 2025

## Setup

1. Copy data from kaggle competition into `data` directory [here](https://www.kaggle.com/competitions/nfl-big-data-bowl-2025/data)
1. install dependcies by running `pip install -r requirements.txt` or `pip install -r requirements-m1.txt` if you're using a Mac system w/ M-series GPU.

## Introduction

- NFL offenses have 40 seconds in which to run a play. That time begins with substitutions, as players run on and off the field until both teams' personnel are configured.
  - It continues into the play call, where both the offensive and defensive units learn their formation and assignments.
  - It ends with myriad strategic decisions by the 22 players on the field, including motion, shifts, and alignment changes, designed to both confuse the opponent and capitalize on any advantages.
- In all that action prior to the snap, both teams likely divulge patterns in what players will do after the snap. The goal of this year's competition aims to tell us just what those patterns are.
- Submission Deadline: **January 6, 2025**

## High-level Goals

- Identify defensive adjustments in response to following pre-snap actions:

  - pre-snap offensive player movements;
  - pre-snap offensive adjustments (audibles)

- Identify how offensive playcalls are influenced by the outcome of the previous play
  - Can timeOffBlock metrics be used to influence where the ball should go? If one side of the D-line is taking more time to get off blocks, does that present an advantage for run plays that way?

- Determine if there is a competitive advantage to 2-point plays/fourth down conversions
  
  - Similar to how there is a deal of research regarding 2-point vs. 3-point shooting in the NBA.
  - Could there be a WAR equivalant in football – as there is in baseball.
