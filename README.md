![IMG_20211226_210634](https://user-images.githubusercontent.com/48711041/147412969-d7f514cb-451c-4d1b-82e8-4cc4e0218e63.png)

# Factor-Analysis-for-Geochemical-Data
Mainly focusing on the dominating factors through the entire region and deposits with their Geochemical data, which determined by the factor analysis.
## Data Normalization
The most important think for before the analysis, it's called data normalization which encompass the data having equal proportion entirely.
where the data would be the Major elements and Trace elements, there would present varying in their values. That means the major elements having a 
Weight percentage `%`  and the trace elements having a `ppm` values. 

example :
* Major elements (2.4930, 4.5637) 
* Trace elements (300, 28, 13)
     
The Equation for Data Normalization     
```math
log (C / (1 - C))
```
For the Major Elements 
> C = W / 100

For the Trace Elements 
> C = W / 1,000,000

## Input The Data
Input the Normalized data in the `X` values. The data looks like our `Orissa geochem data acc(1).xlsx` 

## Manually Choosing factor
If you want to choose factors for manually you can rewrite the code for the `A` segment assign a last value for your factor score, which regarding to present
as your values of factors.
