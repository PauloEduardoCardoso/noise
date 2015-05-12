# noise
Obtain Lden based on Ld, Le, Ld and apply formulation
# Ruido Lden
# Formula lden:
## 10 * log10(
##  (1/24)*(
##    (13  * (10^( ld.r / 10))) +
##      (3 * (10^((len.r + 5) / 10))) +
##      (8 * (10^((ln.r + 10) / 10)))
##  ))
