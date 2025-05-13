MFE-5210-Assignment


i. Correlation matrix 

![图片](https://github.com/user-attachments/assets/53c0cac3-ccd2-464f-9325-ca35a6439e52)

ii. Average sharp ratio for all alpha factors (without 
cost)

![图片](https://github.com/user-attachments/assets/442f0c4d-6048-4c05-b5c5-4b61bf181b1e)


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





