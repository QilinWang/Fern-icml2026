SLDS BASE 
dl-AVG & 4.424 & 1.444 & 3.503 & 35.6 & dl & ALL \\
fr-AVG & 2.839 & 1.263 & 1.458 & 23.1 & fr & ALL \\
kp-AVG & 2.962 & 1.312 & 1.959 & 24.2 & kp & ALL \\
mtcn-AVG & 1.961 & 1.083 & 1.102 & 23.7 & mtcn & ALL \\
pfnn-AVG & 3.520 & 1.290 & 2.966 & 19.9 & pfnn & ALL \\
tm-AVG & 4.537 & 1.669 & 2.801 & 17.4 & tm & ALL \\
tst-AVG & 2.268 & 1.141 & 1.048 & 26.2 & tst & ALL \\

SLDS BASE (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE **4.446**, SWD 3.469  |  0.95× / 1.15× tm  | rank 2.00
Fern     :  MSE 5.090, SWD **2.613**  |  1.09× / 0.87× tm  | rank 2.00
Koopa    :  MSE 6.059, SWD 4.242  |  1.30× / 1.41× tm  | rank 5.00
ModernTCN:  MSE 7.733, SWD 5.549  |  1.65× / 1.84× tm  | rank 6.00
TimeMixer:  MSE *4.675*, SWD *3.008*  |  1.00× / 1.00× tm  | rank 2.00
PatchTST :  MSE 5.619, SWD 3.654  |  1.20× / 1.21× tm  | rank 4.00

 

SLDS_PARAM
dl-AVG & 2.255 & 1.176 & 1.502 & 10.2 & dl & ALL \\
fr-AVG & 2.359 & 1.221 & 1.357 & 6.2 & fr & ALL \\
kp-AVG & 2.185 & 1.168 & 1.378 & 6.2 & kp & ALL \\
mtcn-AVG & 2.296 & 1.194 & 1.797 & 9.4 & mtcn & ALL \\
pfnn-AVG & 2.566 & 1.242 & 2.126 & 7.4 & pfnn & ALL \\
tm-AVG & 2.597 & 1.261 & 1.580 & 7.6 & tm & ALL \\
tst-AVG & 2.177 & 1.173 & 0.910 & 8.1 & tst & ALL \\

SLDS PARAM (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 2.255, SWD 1.502  |  0.87× / 0.95× tm  | rank 3.50
Fern     :  MSE 2.359, SWD *1.357*  |  0.91× / 0.86× tm  | rank 3.50
Koopa    :  MSE *2.185*, SWD 1.378  |  0.84× / 0.87× tm  | rank 2.50
ModernTCN:  MSE 2.296, SWD 1.797  |  0.88× / 1.14× tm  | rank 5.00
PFNN     :  MSE 2.566, SWD 2.126  |  0.99× / 1.35× tm  | rank 6.50
TimeMixer:  MSE 2.597, SWD 1.580  |  1.00× / 1.00× tm  | rank 6.00
PatchTST :  MSE **2.177**, SWD **0.910**  |  0.84× / 0.58× tm  | rank 1.00


SLDS_SWITCH
dl-AVG & 4.728 & 1.613 & 3.375 & 20.9 & dl & ALL \\
fr-AVG & 4.047 & 1.543 & 2.022 & 14.2 & fr & ALL \\
kp-AVG & 4.558 & 1.625 & 3.378 & 17.5 & kp & ALL \\
mtcn-AVG & 9.472 & 2.254 & 5.821 & 19.5 & mtcn & ALL \\
pfnn-AVG & 8.227 & 1.977 & 6.812 & 20.1 & pfnn & ALL \\
tm-AVG & 7.840 & 2.183 & 4.838 & 17.8 & tm & ALL \\
tst-AVG & 9.564 & 2.313 & 5.190 & 14.3 & tst & ALL \\

SLDS SWITCH (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 4.728, SWD *3.375*  |  0.60× / 0.70× tm  | rank 2.50
Fern     :  MSE **4.047**, SWD **2.022**  |  0.52× / 0.42× tm  | rank 1.00
Koopa    :  MSE *4.558*, SWD 3.378  |  0.58× / 0.70× tm  | rank 2.50
ModernTCN:  MSE 9.472, SWD 5.821  |  1.21× / 1.20× tm  | rank 6.00
PFNN     :  MSE 8.227, SWD 6.812  |  1.05× / 1.41× tm  | rank 6.00
TimeMixer:  MSE 7.840, SWD 4.838  |  1.00× / 1.00× tm  | rank 4.00
PatchTST :  MSE 9.564, SWD 5.190  |  1.22× / 1.07× tm  | rank 6.00


SEASONAL_AR_BASE
dl-AVG & 0.056 & 0.189 & 0.010 & 336.000 & dl & ALL \\
fr-AVG & 0.055 & 0.186 & 0.011 & 336.000 & fr & ALL \\
kp-AVG & 0.056 & 0.188 & 0.013 & 335.525 & kp & ALL \\
mtcn-AVG & 0.055 & 0.187 & 0.013 & 336.000 & mtcn & ALL \\
pfnn-AVG & 1.847 & 1.204 & 1.208 & 4.586 & pfnn & ALL \\
tm-AVG & 0.055 & 0.187 & 0.013 & 336.000 & tm & ALL \\
tst-AVG & 0.074 & 0.219 & 0.021 & 336.000 & tst & ALL \\

SEASONAL_AR_BASE (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 0.056, SWD **0.010**  |  1.02× / 0.77× tm  | rank 2.50
Fern     :  MSE **0.055**, SWD *0.011*  |  1.00× / 0.85× tm  | rank 1.50
Koopa    :  MSE 0.056, SWD 0.013  |  1.02× / 1.00× tm  | rank 4.00
ModernTCN:  MSE *0.055*, SWD 0.013  |  1.00× / 1.00× tm  | rank 3.00
PFNN     :  MSE 1.847, SWD 1.208  |  33.58× / 92.92× tm  | rank 7.00
TimeMixer:  MSE 0.055, SWD 0.013  |  1.00× / 1.00× tm  | rank 4.00
PatchTST :  MSE 0.074, SWD 0.021  |  1.35× / 1.62× tm  | rank 6.00

SEASONAL_AR_PARAM
dl-AVG & 0.380 & 0.491 & 0.053 & 335.361 & dl & ALL \\
fr-AVG & 0.355 & 0.474 & 0.053 & 336.000 & fr & ALL \\
kp-AVG & 0.366 & 0.482 & 0.075 & 335.666 & kp & ALL \\
mtcn-AVG & 0.359 & 0.479 & 0.065 & 336.000 & mtcn & ALL \\
pfnn-AVG & 10.826 & 2.913 & 7.432 & 4.374 & pfnn & ALL \\
tm-AVG & 0.361 & 0.480 & 0.065 & 336.000 & tm & ALL \\
tst-AVG & 0.480 & 0.555 & 0.128 & 336.000 & tst & ALL \\

SEASONAL_AR_PARAM (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 0.380, SWD **0.053**  |  1.05× / 0.82× tm  | rank 3.00
Fern     :  MSE **0.355**, SWD *0.053*  |  0.98× / 0.82× tm  | rank 1.50
Koopa    :  MSE 0.366, SWD 0.075  |  1.01× / 1.15× tm  | rank 4.50
ModernTCN:  MSE *0.359*, SWD 0.065  |  0.99× / 1.00× tm  | rank 2.50
PFNN     :  MSE 10.826, SWD 7.432  |  29.99× / 114.34× tm  | rank 7.00
TimeMixer:  MSE 0.361, SWD 0.065  |  1.00× / 1.00× tm  | rank 3.50
PatchTST :  MSE 0.480, SWD 0.128  |  1.33× / 1.97× tm  | rank 6.00

## GARCH_BASE
dl-AVG & 0.264 & 0.404 & 0.190 & 2.480 & dl & ALL \\
fr-AVG & 0.227 & 0.377 & 0.220 & 3.009 & fr & ALL \\
kp-AVG & 0.255 & 0.397 & 0.217 & 2.587 & kp & ALL \\
mtcn-AVG & 0.261 & 0.403 & 0.210 & 2.253 & mtcn & ALL \\
pfnn-AVG & 0.255 & 0.397 & 0.208 & 2.521 & pfnn & ALL \\
tm-AVG & 0.234 & 0.381 & 0.201 & 2.799 & tm & ALL \\
tst-AVG & 0.271 & 0.411 & 0.174 & 2.616 & tst & ALL \\

GARCH_BASE (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 0.264, SWD *0.190*  |  1.13× / 0.95× tm  | rank 4.00
Fern     :  MSE **0.227**, SWD 0.220  |  0.97× / 1.09× tm  | rank 4.00
Koopa    :  MSE 0.255, SWD 0.217  |  1.09× / 1.08× tm  | rank 4.50
ModernTCN:  MSE 0.261, SWD 0.210  |  1.12× / 1.04× tm  | rank 5.00
PFNN     :  MSE 0.255, SWD 0.208  |  1.09× / 1.03× tm  | rank 4.00
TimeMixer:  MSE *0.234*, SWD 0.201  |  1.00× / 1.00× tm  | rank 2.50
PatchTST :  MSE 0.271, SWD **0.174**  |  1.16× / 0.87× tm  | rank 4.00

## GARCH_PARAM
dl-AVG & 0.183 & 0.336 & 0.135 & 3.432 & dl & ALL \\
fr-AVG & 0.177 & 0.334 & 0.174 & 2.989 & fr & ALL \\
kp-AVG & 0.191 & 0.350 & 0.172 & 2.678 & kp & ALL \\
mtcn-AVG & 0.206 & 0.345 & 0.163 & 3.130 & mtcn & ALL \\
pfnn-AVG & 0.236 & 0.376 & 0.196 & 2.643 & pfnn & ALL \\
tm-AVG & 0.186 & 0.341 & 0.156 & 3.125 & tm & ALL \\
tst-AVG & 0.220 & 0.372 & 0.138 & 2.525 & tst & ALL \\

GARCH_PARAM (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE *0.183*, SWD **0.135**  |  0.98× / 0.87× tm  | rank 1.50
Fern     :  MSE **0.177**, SWD 0.174  |  0.95× / 1.12× tm  | rank 3.50
Koopa    :  MSE 0.191, SWD 0.172  |  1.03× / 1.10× tm  | rank 4.50
ModernTCN:  MSE 0.206, SWD 0.163  |  1.11× / 1.04× tm  | rank 4.50
PFNN     :  MSE 0.236, SWD 0.196  |  1.27× / 1.26× tm  | rank 7.00
TimeMixer:  MSE 0.186, SWD 0.156  |  1.00× / 1.00× tm  | rank 3.00
PatchTST :  MSE 0.220, SWD *0.138*  |  1.18× / 0.88× tm  | rank 4.00

## DOUBLEWELL_BASE
dl-AVG & 0.055 & 0.185 & 0.034 & 336.000 & dl & ALL \\
fr-AVG & 0.054 & 0.184 & 0.028 & 336.000 & fr & ALL \\
kp-AVG & 0.049 & 0.174 & 0.042 & 335.997 & kp & ALL \\
mtcn-AVG & 0.049 & 0.174 & 0.043 & 336.000 & mtcn & ALL \\
pfnn-AVG & 1.465 & 1.183 & 1.411 & 2.645 & pfnn & ALL \\
tm-AVG & 0.059 & 0.188 & 0.043 & 335.132 & tm & ALL \\
tst-AVG & 0.091 & 0.221 & 0.057 & 330.753 & tst & ALL \\

DOUBLEWELL_BASE (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 0.055, SWD *0.034*  |  0.93× / 0.79× tm  | rank 3.00
Fern     :  MSE 0.054, SWD **0.028**  |  0.92× / 0.65× tm  | rank 2.00
Koopa    :  MSE **0.049**, SWD 0.042  |  0.83× / 0.98× tm  | rank 2.00
ModernTCN:  MSE *0.049*, SWD 0.043  |  0.83× / 1.00× tm  | rank 3.00
PFNN     :  MSE 1.465, SWD 1.411  |  24.83× / 32.81× tm  | rank 7.00
TimeMixer:  MSE 0.059, SWD 0.043  |  1.00× / 1.00× tm  | rank 5.00
PatchTST :  MSE 0.091, SWD 0.057  |  1.54× / 1.33× tm  | rank 6.00

## DOUBLEWELL_PARAM

dl-AVG & 0.847 & 0.728 & 0.711 & 112.594 & dl & ALL \\
fr-AVG & 0.682 & 0.714 & 0.506 & 61.076 & fr & ALL \\
kp-AVG & 1.030 & 0.825 & 0.856 & 61.010 & kp & ALL \\
mtcn-AVG & 1.003 & 0.834 & 0.815 & 57.887 & mtcn & ALL \\
pfnn-AVG & 0.837 & 0.862 & 0.756 & 2.883 & pfnn & ALL \\
tm-AVG & 1.084 & 0.855 & 0.843 & 54.549 & tm & ALL \\
tst-AVG & 0.983 & 0.846 & 0.721 & 47.147 & tst & ALL \\

DOUBLEWELL_PARAM (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 0.847, SWD *0.711*  |  0.78× / 0.84× tm  | rank 2.50
Fern     :  MSE **0.682**, SWD **0.506**  |  0.63× / 0.60× tm  | rank 1.00
Koopa    :  MSE 1.030, SWD 0.856  |  0.95× / 1.02× tm  | rank 6.50
ModernTCN:  MSE 1.003, SWD 0.815  |  0.93× / 0.97× tm  | rank 5.00
PFNN     :  MSE *0.837*, SWD 0.756  |  0.77× / 0.90× tm  | rank 3.00
TimeMixer:  MSE 1.084, SWD 0.843  |  1.00× / 1.00× tm  | rank 6.50
PatchTST :  MSE 0.983, SWD 0.721  |  0.91× / 0.86× tm  | rank 3.50

## OU_BASE
dl-AVG & 0.234 & 0.387 & 0.166 & 9.579 & dl & ALL \\
fr-AVG & 0.234 & 0.388 & 0.195 & 9.187 & fr & ALL \\
kp-AVG & 0.251 & 0.403 & 0.156 & 8.289 & kp & ALL \\
mtcn-AVG & 0.241 & 0.393 & 0.178 & 9.514 & mtcn & ALL \\
pfnn-AVG & 0.237 & 0.391 & 0.216 & 8.156 & pfnn & ALL \\
tm-AVG & 0.251 & 0.401 & 0.131 & 8.656 & tm & ALL \\
tst-AVG & 0.273 & 0.417 & 0.112 & 8.569 & tst & ALL \\

OU_BASE (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE **0.234**, SWD 0.166  |  0.93× / 1.27× tm  | rank 2.50
Fern     :  MSE *0.234*, SWD 0.195  |  0.93× / 1.49× tm  | rank 4.00
Koopa    :  MSE 0.251, SWD 0.156  |  1.00× / 1.19× tm  | rank 4.00
ModernTCN:  MSE 0.241, SWD 0.178  |  0.96× / 1.36× tm  | rank 4.50
PFNN     :  MSE 0.237, SWD 0.216  |  0.94× / 1.65× tm  | rank 5.00
TimeMixer:  MSE 0.251, SWD *0.131*  |  1.00× / 1.00× tm  | rank 4.00
PatchTST :  MSE 0.273, SWD **0.112**  |  1.09× / 0.85× tm  | rank 4.00

## OU_PARAM
dl-AVG & 0.239 & 0.392 & 0.163 & 11.865 & dl & ALL \\
fr-AVG & 0.239 & 0.391 & 0.170 & 9.323 & fr & ALL \\
kp-AVG & 0.251 & 0.403 & 0.156 & 8.281 & kp & ALL \\
mtcn-AVG & 0.241 & 0.393 & 0.178 & 9.508 & mtcn & ALL \\
pfnn-AVG & 0.383 & 0.508 & 0.358 & 5.773 & pfnn & ALL \\
tm-AVG & 0.251 & 0.401 & 0.131 & 8.646 & tm & ALL \\
tst-AVG & 0.273 & 0.417 & 0.112 & 8.559 & tst & ALL \\

OU_PARAM (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE **0.239**, SWD 0.163  |  0.95× / 1.24× tm  | rank 2.50
Fern     :  MSE *0.239*, SWD 0.170  |  0.95× / 1.30× tm  | rank 3.50
Koopa    :  MSE 0.251, SWD 0.156  |  1.00× / 1.19× tm  | rank 3.50
ModernTCN:  MSE 0.241, SWD 0.178  |  0.96× / 1.36× tm  | rank 4.50
PFNN     :  MSE 0.383, SWD 0.358  |  1.53× / 2.73× tm  | rank 7.00
TimeMixer:  MSE 0.251, SWD *0.131*  |  1.00× / 1.00× tm  | rank 3.50
PatchTST :  MSE 0.273, SWD **0.112**  |  1.09× / 0.85× tm  | rank 3.50

## ROSSLER_BASE
dl-AVG & 5.418 & 1.266 & 5.057 & 285.955 & dl & ALL \\
fr-AVG & 0.019 & 0.082 & 0.011 & 335.349 & fr & ALL \\
kp-AVG & 11.941 & 2.306 & 5.579 & 69.850 & kp & ALL \\
mtcn-AVG & 0.469 & 0.311 & 0.421 & 325.844 & mtcn & ALL \\
pfnn-AVG & 21.046 & 3.438 & 16.639 & 103.706 & pfnn & ALL \\
tm-AVG & 1.032 & 0.449 & 0.903 & 326.762 & tm & ALL \\
tst-AVG & 2.447 & 0.729 & 2.248 & 309.322 & tst & ALL \\

ROSSLER_BASE (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 5.418, SWD 5.057  |  5.25× / 5.60× tm  | rank 5.00
Fern     :  MSE **0.019**, SWD **0.011**  |  0.02× / 0.01× tm  | rank 1.00
Koopa    :  MSE 11.941, SWD 5.579  |  11.57× / 6.18× tm  | rank 6.00
ModernTCN:  MSE *0.469*, SWD *0.421*  |  0.45× / 0.47× tm  | rank 2.00
PFNN     :  MSE 21.046, SWD 16.639  |  20.39× / 18.43× tm  | rank 7.00
TimeMixer:  MSE 1.032, SWD 0.903  |  1.00× / 1.00× tm  | rank 3.00
PatchTST :  MSE 2.447, SWD 2.248  |  2.37× / 2.49× tm  | rank 4.00

## ROSSLER_PARAM
dl-AVG & 28.736 & 2.505 & 25.423 & 266.660 & dl & ALL \\
fr-AVG & 0.036 & 0.110 & 0.017 & 335.586 & fr & ALL \\
kp-AVG & 25.071 & 2.916 & 17.907 & 109.950 & kp & ALL \\
mtcn-AVG & 1.639 & 0.430 & 1.374 & 324.219 & mtcn & ALL \\
pfnn-AVG & 28.090 & 3.432 & 23.084 & 157.229 & pfnn & ALL \\
tm-AVG & 3.491 & 0.552 & 2.908 & 314.279 & tm & ALL \\
tst-AVG & 10.024 & 1.074 & 8.615 & 304.112 & tst & ALL \\

ROSSLER_PARAM (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 28.736, SWD 25.423  |  8.23× / 8.74× tm  | rank 7.00
Fern     :  MSE **0.036**, SWD **0.017**  |  0.01× / 0.01× tm  | rank 1.00
Koopa    :  MSE 25.071, SWD 17.907  |  7.18× / 6.16× tm  | rank 5.00
ModernTCN:  MSE *1.639*, SWD *1.374*  |  0.47× / 0.47× tm  | rank 2.00
PFNN     :  MSE 28.090, SWD 23.084  |  8.05× / 7.94× tm  | rank 6.00
TimeMixer:  MSE 3.491, SWD 2.908  |  1.00× / 1.00× tm  | rank 3.00
PatchTST :  MSE 10.024, SWD 8.615  |  2.87× / 2.96× tm  | rank 4.00

## LORENZ_BASE

dl-AVG & 76.548 & 6.396 & 39.340 & 61.955 & dl & ALL \\
fr-AVG & 21.663 & 2.393 & 4.409 & 241.249 & fr & ALL \\
kp-AVG & 95.501 & 7.570 & 11.049 & 5.631 & kp & ALL \\
mtcn-AVG & 26.023 & 3.009 & 5.962 & 258.725 & mtcn & ALL \\
pfnn-AVG & 198.152 & 11.028 & 120.587 & 9.056 & pfnn & ALL \\
tm-AVG & 43.209 & 3.739 & 10.087 & 202.829 & tm & ALL \\
tst-AVG & 38.889 & 3.654 & 10.563 & 197.391 & tst & ALL \\

LORENZ_BASE (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 76.548, SWD 39.340  |  1.77× / 3.90× tm  | rank 5.50
Fern     :  MSE **21.663**, SWD **4.409**  |  0.50× / 0.44× tm  | rank 1.00
Koopa    :  MSE 95.501, SWD 11.049  |  2.21× / 1.10× tm  | rank 5.50
ModernTCN:  MSE *26.023*, SWD *5.962*  |  0.60× / 0.59× tm  | rank 2.00
PFNN     :  MSE 198.152, SWD 120.587  |  4.59× / 11.95× tm  | rank 7.00
TimeMixer:  MSE 43.209, SWD 10.087  |  1.00× / 1.00× tm  | rank 3.50
PatchTST :  MSE 38.889, SWD 10.563  |  0.90× / 1.05× tm  | rank 3.50


## LORENZ_STATE
dl-AVG & 70.360 & 6.100 & 35.584 & 64.428 & dl & ALL \\
fr-AVG & 19.256 & 2.274 & 3.727 & 246.543 & fr & ALL \\
kp-AVG & 97.853 & 7.666 & 13.517 & 6.321 & kp & ALL \\
mtcn-AVG & 28.488 & 3.220 & 5.676 & 235.240 & mtcn & ALL \\
pfnn-AVG & 210.898 & 11.434 & 122.113 & 9.107 & pfnn & ALL \\
tm-AVG & 48.814 & 4.188 & 10.218 & 187.854 & tm & ALL \\
tst-AVG & 40.708 & 3.861 & 10.903 & 190.862 & tst & ALL \\

LORENZ_STATE (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 70.360, SWD 35.584  |  1.44× / 3.48× tm  | rank 5.50
Fern     :  MSE **19.256**, SWD **3.727**  |  0.39× / 0.36× tm  | rank 1.00
Koopa    :  MSE 97.853, SWD 13.517  |  2.00× / 1.32× tm  | rank 5.50
ModernTCN:  MSE *28.488*, SWD *5.676*  |  0.58× / 0.56× tm  | rank 2.00
PFNN     :  MSE 210.898, SWD 122.113  |  4.32× / 11.95× tm  | rank 7.00
TimeMixer:  MSE 48.814, SWD 10.218  |  1.00× / 1.00× tm  | rank 3.50
PatchTST :  MSE 40.708, SWD 10.903  |  0.83× / 1.07× tm  | rank 3.50

## LORENZ_PARAM
dl-AVG & 70.694 & 6.194 & 32.885 & 75.291 & dl & ALL \\
fr-AVG & 25.213 & 2.475 & 4.613 & 260.641 & fr & ALL \\
kp-AVG & 103.703 & 7.779 & 17.856 & 10.905 & kp & ALL \\
mtcn-AVG & 35.957 & 3.462 & 7.566 & 243.487 & mtcn & ALL \\
pfnn-AVG & 218.569 & 11.818 & 150.879 & 8.314 & pfnn & ALL \\
tm-AVG & 52.097 & 4.305 & 10.633 & 200.207 & tm & ALL \\
tst-AVG & 40.591 & 3.698 & 9.189 & 220.571 & tst & ALL \\

LORENZ_PARAM (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 70.694, SWD 32.885  |  1.36× / 3.09× tm  | rank 5.50
Fern     :  MSE **25.213**, SWD **4.613**  |  0.48× / 0.43× tm  | rank 1.00
Koopa    :  MSE 103.703, SWD 17.856  |  1.99× / 1.68× tm  | rank 5.50
ModernTCN:  MSE *35.957*, SWD *7.566*  |  0.69× / 0.71× tm  | rank 2.00
PFNN     :  MSE 218.569, SWD 150.879  |  4.20× / 14.19× tm  | rank 7.00
TimeMixer:  MSE 52.097, SWD 10.633  |  1.00× / 1.00× tm  | rank 4.00
PatchTST :  MSE 40.591, SWD 9.189  |  0.78× / 0.86× tm  | rank 3.00

## LORENZ96_BASE
dl-AVG & 10.981 & 2.591 & 6.023 & 105.567 & dl & ALL \\
fr-AVG & 5.190 & 1.471 & 1.329 & 247.132 & fr & ALL \\
kp-AVG & 17.416 & 3.265 & 3.409 & 9.060 & kp & ALL \\
mtcn-AVG & 10.379 & 2.417 & 3.642 & 150.268 & mtcn & ALL \\
pfnn-AVG & 20.172 & 3.648 & 15.563 & 9.929 & pfnn & ALL \\
tm-AVG & 8.031 & 2.090 & 2.968 & 170.151 & tm & ALL \\
tst-AVG & 6.354 & 1.833 & 2.491 & 200.926 & tst & ALL \\

LORENZ96_BASE (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 10.981, SWD 6.023  |  1.37× / 2.03× tm  | rank 5.50
Fern     :  MSE **5.190**, SWD **1.329**  |  0.65× / 0.45× tm  | rank 1.00
Koopa    :  MSE 17.416, SWD 3.409  |  2.17× / 1.15× tm  | rank 5.00
ModernTCN:  MSE 10.379, SWD 3.642  |  1.29× / 1.23× tm  | rank 4.50
PFNN     :  MSE 20.172, SWD 15.563  |  2.51× / 5.24× tm  | rank 7.00
TimeMixer:  MSE 8.031, SWD 2.968  |  1.00× / 1.00× tm  | rank 3.00
PatchTST :  MSE *6.354*, SWD *2.491*  |  0.79× / 0.84× tm  | rank 2.00

## LORENZ96_SWITCH
dl-AVG & 13.681 & 2.898 & 7.801 & 91.257 & dl & ALL \\
fr-AVG & 9.564 & 2.186 & 3.139 & 170.418 & fr & ALL \\
kp-AVG & 21.606 & 3.634 & 4.591 & 6.643 & kp & ALL \\
mtcn-AVG & 11.775 & 2.578 & 5.250 & 133.163 & mtcn & ALL \\
pfnn-AVG & 24.420 & 4.015 & 17.901 & 8.673 & pfnn & ALL \\
tm-AVG & 11.964 & 2.590 & 5.337 & 128.290 & tm & ALL \\
tst-AVG & 10.726 & 2.425 & 4.729 & 154.304 & tst & ALL \\

LORENZ96_SWITCH (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 13.681, SWD 7.801  |  1.14× / 1.46× tm  | rank 5.50
Fern     :  MSE **9.564**, SWD **3.139**  |  0.80× / 0.59× tm  | rank 1.00
Koopa    :  MSE 21.606, SWD *4.591*  |  1.81× / 0.86× tm  | rank 4.00
ModernTCN:  MSE 11.775, SWD 5.250  |  0.98× / 0.98× tm  | rank 3.50
PFNN     :  MSE 24.420, SWD 17.901  |  2.04× / 3.35× tm  | rank 7.00
TimeMixer:  MSE 11.964, SWD 5.337  |  1.00× / 1.00× tm  | rank 4.50
PatchTST :  MSE *10.726*, SWD 4.729  |  0.90× / 0.89× tm  | rank 2.50

## CHUA_BASE
dl-AVG & 0.720 & 0.481 & 0.507 & 265.772 & dl & ALL \\
fr-AVG & 0.056 & 0.119 & 0.033 & 305.118 & fr & ALL \\
kp-AVG & 1.106 & 0.705 & 0.482 & 50.3 & kp & ALL \\
mtcn-AVG & 0.051 & 0.135 & 0.029 & 331.431 & mtcn & ALL \\
pfnn-AVG & 1.771 & 1.006 & 1.672 & 28.052 & pfnn & ALL \\
tm-AVG & 0.094 & 0.149 & 0.046 & 316.833 & tm & ALL \\
tst-AVG & 0.186 & 0.228 & 0.119 & 298.558 & tst & ALL \\

CHUA_BASE (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 0.720, SWD 0.507  |  7.66× / 11.02× tm  | rank 5.00
Fern     :  MSE *0.056*, SWD *0.033*  |  0.60× / 0.72× tm  | rank 2.00
ModernTCN:  MSE **0.051**, SWD **0.029**  |  0.54× / 0.63× tm  | rank 1.00
PFNN     :  MSE 1.771, SWD 1.672  |  18.84× / 36.35× tm  | rank 6.00
TimeMixer:  MSE 0.094, SWD 0.046  |  1.00× / 1.00× tm  | rank 3.00
PatchTST :  MSE 0.186, SWD 0.119  |  1.98× / 2.59× tm  | rank 4.00


## CHUA_PARAM
dl-AVG & 0.681 & 0.511 & 0.559 & 272.963 & dl & ALL \\
fr-AVG & 0.021 & 0.105 & 0.011 & 310.506 & fr & ALL \\
kp-AVG & 0.944 & 0.640 & 0.353 & 33.568 & kp & ALL \\
mtcn-AVG & 0.030 & 0.110 & 0.021 & 335.995 & mtcn & ALL \\
pfnn-AVG & 2.312 & 1.128 & 2.140 & 20.539 & pfnn & ALL \\
tm-AVG & 0.013 & 0.080 & 0.008 & 335.636 & tm & ALL \\
tst-AVG & 0.097 & 0.199 & 0.078 & 305.614 & tst & ALL \\

CHUA_PARAM (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 0.681, SWD 0.559  |  52.38× / 69.88× tm  | rank 5.50
Fern     :  MSE *0.021*, SWD *0.011*  |  1.62× / 1.38× tm  | rank 2.00
Koopa    :  MSE 0.944, SWD 0.353  |  72.62× / 44.12× tm  | rank 5.50
ModernTCN:  MSE 0.030, SWD 0.021  |  2.31× / 2.62× tm  | rank 3.00
PFNN     :  MSE 2.312, SWD 2.140  |  177.85× / 267.50× tm  | rank 7.00
TimeMixer:  MSE **0.013**, SWD **0.008**  |  1.00× / 1.00× tm  | rank 1.00
PatchTST :  MSE 0.097, SWD 0.078  |  7.46× / 9.75× tm  | rank 4.00

## CHUA_SWITCH
dl-AVG & 0.770 & 0.516 & 0.591 & 258.279 & dl & ALL \\
fr-AVG & 0.178 & 0.225 & 0.106 & 256.657 & fr & ALL \\
kp-AVG & 1.107 & 0.677 & 0.584 & 48.757 & kp & ALL \\
mtcn-AVG & 0.099 & 0.164 & 0.068 & 332.606 & mtcn & ALL \\
pfnn-AVG & 1.744 & 0.971 & 1.635 & 32.742 & pfnn & ALL \\
tm-AVG & 0.174 & 0.204 & 0.123 & 311.783 & tm & ALL \\
tst-AVG & 0.318 & 0.313 & 0.230 & 287.896 & tst & ALL \\

CHUA_SWITCH (MSE ↓ / SWD ↓). Base = TimeMixer (tm).

DLinear  :  MSE 0.770, SWD 0.591  |  4.43× / 4.80× tm  | rank 5.50
Fern     :  MSE 0.178, SWD *0.106*  |  1.02× / 0.86× tm  | rank 2.50
Koopa    :  MSE 1.107, SWD 0.584  |  6.36× / 4.75× tm  | rank 5.50
ModernTCN:  MSE **0.099**, SWD **0.068**  |  0.57× / 0.55× tm  | rank 1.00
PFNN     :  MSE 1.744, SWD 1.635  |  10.02× / 13.29× tm  | rank 7.00
TimeMixer:  MSE *0.174*, SWD 0.123  |  1.00× / 1.00× tm  | rank 2.50
PatchTST :  MSE 0.318, SWD 0.230  |  1.83× / 1.87× tm  | rank 4.00


# ETTH2
dl-AVG & 16.846 & 2.701 & 11.030 & 161.662 & dl & ALL \\
fr-AVG & 21.960 & 3.271 & 18.371 & 129.868 & fr & ALL \\
kp-AVG & 16.552 & 2.671 & 11.378 & 161.795 & kp & ALL \\
mtcn-AVG & 20.615 & 2.977 & 13.255 & 154.367 & mtcn & ALL \\
pfnn-AVG & 80162388475.500 & 64224.398 & 80161449429.000 & 1.129 & pfnn & ALL \\
tm-AVG & 16.951 & 2.714 & 11.444 & 154.770 & tm & ALL \\
tst-AVG & 17.565 & 2.798 & 10.987 & 155.825 & tst & ALL \\

# ETTH1
dl-AVG & 10.392 & 1.805 & 5.001 & 79.681 & dl & ALL \\
fr-AVG & 10.965 & 1.875 & 5.750 & 63.340 & fr & ALL \\
kp-AVG & 10.747 & 1.886 & 5.547 & 67.780 & kp & ALL \\
mtcn-AVG & 14.522 & 2.137 & 9.006 & 72.108 & mtcn & ALL \\
pfnn-AVG & 2222.362 & 21.704 & 1988.746 & 3.205 & pfnn & ALL \\
tm-AVG & 10.507 & 1.847 & 5.227 & 70.972 & tm & ALL \\
tst-AVG & 10.974 & 1.897 & 4.834 & 69.782 & tst & ALL \\

# ETTM1
dl-AVG & 9.710 & 1.654 & 6.251 & 123.3 & dl & ALL \\
fr-AVG & 8.965 & 1.656 & 5.365 & 107.6 & fr & ALL \\
kp-AVG & 9.224 & 1.652 & 5.692 & 115.4 & kp & ALL \\
mtcn-AVG & 11.141 & 1.888 & 7.114 & 109.6 & mtcn & ALL \\
pfnn-AVG & 43.688 & 5.056 & 34.253 & 5.9 & pfnn & ALL \\
tm-AVG & 9.115 & 1.647 & 5.625 & 122.9 & tm & ALL \\
tst-AVG & 8.826 & 1.635 & 5.487 & 120.0 & tst & ALL \\

# ETTM2
dl-AVG & 12.195 & 2.257 & 8.187 & 260.0 & dl & ALL \\
fr-AVG & 13.062 & 2.437 & 8.586 & 224.5 & fr & ALL \\
kp-AVG & 11.943 & 2.235 & 8.308 & 258.6 & kp & ALL \\
mtcn-AVG & 13.697 & 2.380 & 9.379 & 257.0 & mtcn & ALL \\
pfnn-AVG & 289.025 & 14.258 & 244.082 & 1.3 & pfnn & ALL \\
tm-AVG & 12.002 & 2.230 & 7.885 & 259.3 & tm & ALL \\
tst-AVG & 12.120 & 2.256 & 8.166 & 258.5 & tst & ALL \\
