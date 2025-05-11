MFE-5210-Assignment
i. Correlation matrix 
         Alpha1  Alpha4  Alpha5  Alpha8  Alpha12  Alpha23  Alpha32  Alpha45  \
Alpha1     1.00    0.39    0.36    0.76    -0.11     0.43     0.94     0.18   
Alpha4     0.39    1.00    0.42    0.28     0.20    -0.11     0.32     0.03   
Alpha5     0.36    0.42    1.00    0.29    -0.08    -0.05     0.29     0.08   
Alpha8     0.76    0.28    0.29    1.00    -0.08     0.71     0.70     0.17   
Alpha12   -0.11    0.20   -0.08   -0.08     1.00     0.04    -0.07    -0.16   
Alpha23    0.43   -0.11   -0.05    0.71     0.04     1.00     0.45     0.01   
Alpha32    0.94    0.32    0.29    0.70    -0.07     0.45     1.00     0.18   
Alpha45    0.18    0.03    0.08    0.17    -0.16     0.01     0.18     1.00   
Alpha67    0.46    0.59    0.50    0.36    -0.02    -0.00     0.38    -0.21   

         Alpha67  
Alpha1      0.46  
Alpha4      0.59  
Alpha5      0.50  
Alpha8      0.36  
Alpha12    -0.02  
Alpha23    -0.00  
Alpha32     0.38  
Alpha45    -0.21  
Alpha67     1.00  

ii. Average sharp ratio for all alpha factors (without 
cost)
         mean  Sharpe  Cumulative_Return
Alpha1  -0.00   -1.07              -0.23
Alpha4  -0.03    0.24               0.05
Alpha5  -0.01    0.87               0.22
Alpha8  -0.04   -0.46              -0.12
Alpha12 -0.00   -0.36              -0.09
Alpha23 -0.00   -0.51              -0.13
Alpha32 -0.00   -1.06              -0.23
Alpha45 -0.00   -0.07              -0.02
Alpha67  0.01    0.21               0.05

iii.​Factor Analysis​​
​1. Factor Correlation Analysis​​

The correlation matrix reveals significant differences in interdependencies:

    ​​High Positive Correlation​​:
        Alpha1 vs. Alpha32 (0.94) and Alpha8 (0.76) show strong collinearity, indicating potential redundancy in capturing market signals.
        Alpha8 vs. Alpha23 (0.71) suggests overlapping risk exposures.
    ​​Unique Factors​​:
        Alpha12 has low correlations with others (absolute values <0.2), especially negative with Alpha1 (-0.11) and Alpha8 (-0.08), offering diversification potential.
        Alpha67 moderately correlates with Alpha4 (0.59) and Alpha5 (0.50) but remains distinct from others.

​​2. Risk-Return Performance​​

    ​​Effective Factors​​:
        ​​Alpha5​​ has the highest Sharpe ratio (0.87) and cumulative return (0.22), indicating robust risk-adjusted performance.
        ​​Alpha67​​ shows weak but positive Sharpe (0.21) and return (0.05), outperforming most peers.
    ​​Underperforming Factors​​:
        ​​Alpha1 & Alpha32​​ have critically low Sharpe (-1.07, -1.06) and large losses (-0.23), likely due to overfitting or regime shifts.
        ​​Alpha8 & Alpha23​​ correlate with high-return factors but exhibit negative Sharpe (-0.46, -0.51), requiring revalidation.

​​3. Optimization Recommendations​​

    ​​Remove Redundant Factors​​: Retain only one from Alpha1/Alpha8/Alpha32 (e.g., Alpha1) to avoid multicollinearity.
    ​​Prioritize Alpha5​​: Use as the core factor, complemented by Alpha67 for diversification.
    ​​Monitor Alpha12​​: Its low correlation may improve portfolio stability, but validate its standalone efficacy.
    ​​Suspend Problematic Factors​​: Discontinue Alpha32 and Alpha23 until further validation.





