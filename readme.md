# 6Nations Sweepstake Calculator

A simple to calculate scores for a 6 Nations rugby sweepstake. Read the accompanying [blogpost](http://meigwilym.com/javascript-6-nations-sweepstake-calculator/).

See the [latest 2015 results](www.clwbrygbicaernarfon.co.uk/sweep).

### Background

The 6 Nations is an annual  international rugby union competition involving six European sides: England, France, Ireland, Italy, Scotland and Wales. 

http://www.rbs6nations.com/en/home.php

I wanted to create a way to quickly calculate and display the results of the sweepstake. 

## How to use

There is an example sheet to print out for participants (`table.html`). The fixtures are for the 2015 6 Nations' Championship. 

After collecting all the entries, the predictions must be to `predictions.csv`. The index file can be in a browser to view the results. 

See the [blogpost](http://meigwilym.com/javascript-6-nations-sweepstake-calculator/) and the `index.html` source comments for further details. 

## Sweepstake Rules

1. Predict the winning team, score of each team and number of tries for each of the 15 games.
2. Predict the final places of the six nations teams in the final table.

## Points Allocation

1. 1 point for the correct winning team of each match.
2. 1 point for the correct score of each team in each match.
3. 1 point for the correct points difference between the teams in each match.
4. 2 points for predicting the total number of tries (including penalty tries) in each match.
5. 2 points for every correct place in the final Six Nations table.
6. Maximum available points are:
  * 6 points for each game;
  * 12 points for the final table
7. In the event of two people having the same points at the end of the championship, the winner will be decided by the most correct try predictions.

## License

Licensed under the GPLv3 http://www.gnu.org/copyleft/gpl.html

Copyright 2015 Mei Gwilym 

[@meilyrg](http://twitter.com/meilyrg)