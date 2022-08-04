The current variant of BTST that we are running live is the one where the Gap is calculated from the days open. Alternatively we have tried two More Variations:

1) The Gap is being calculated from Previous Day's Close as opposed to Current Day's Open. There was no significant improvement in the results in the results.
   No Optimizations or Backtest for are saved.
   
2) Fundamental Filters like ROCE and Market Cap were added to the existing BTST System to see if those filters added any value. The ROCE and Market Cap data
   was got from Ace Equity and Imported onto the "F&O Equities" database. Ranking and Trading is being done on Equities and the code can be found here.
   [BTSTBuyRankTimeFundamentalFilters]
   https://github.com/qodeinvestments/BTST/blob/701f50dd3194811c6ea7509acac0288227fb1883/Amibroker_Codes/BTSTBuyRankTimeFundamentalFilters
   The Optimizations is saved on E:\Dropboximac\Dropbox\Strategy Testing\BTST\2022\BTST With Fundamental Filters on the E: Drive.
   The Filters did not add any value.
