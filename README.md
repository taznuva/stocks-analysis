# Stocks-Analysis_VBA_Challenge


## Overview of Project
### Purpose
In this project, we're refactoring the code we made for Steve from the module. The whole point of refactoring code is to make it neater, less convoluted, and more efficient such as faster run-time. Refactoring is important process to coding as our first code may not always be efficient and therefore we need to edit. It is also good practice to edit code as it could be our entry point to a company and their existing code. In this case, we're refactoring code from the previous dataset to expand the dataset so Steve can see the entire stock market. Applying the knowledge gained from the module and practice from previous code, we'll be comparing the runtimes between the original code and the refactored one. 

## Results
### 2017 Dataset
The 2017 dataset with the original code ran faster than compared to the refactored and with the 2018 dataset. It also suggests that the stock market in 2017 did very well than in 2018. 

<img width="549" alt="Screen Shot 2021-10-27 at 6 45 08 PM" src="https://user-images.githubusercontent.com/33046642/139613369-008af346-f042-426c-a26e-6da9e231fa9c.png">

In the refactored 2017 dataset, the code ran significantly longer (about 7.5 seconds) than the original did as shown below screenshot. 

<img width="512" alt="VBA_Refactored 2017" src="https://user-images.githubusercontent.com/33046642/140248908-3735b9f2-489e-4e17-9e6d-afbc798270a8.png">

### 2018 Dataset
The 2018 dataset with the original code ran more than for 2017 and suggests that the stock market did not do so well in 2018. 

<img width="549" alt="Screen Shot 2021-10-27 at 6 45 39 PM" src="https://user-images.githubusercontent.com/33046642/139613382-4b20f0d9-8813-4b01-96ee-8545e37e2c90.png">

In the refactored, the code took 2 seconds longer to run through as shown below.

<img width="512" alt="VBA_Refactored 2018" src="https://user-images.githubusercontent.com/33046642/140249103-ca3cd595-c354-4736-851d-6a88faf643d4.png">



## Summary

1)What are the advantages or disadvantages of refactoring code?

Advantages - neater, comprehension is improved for a different user or coming back to code after a long time, less memory required, faster run-time. In this project, all code was refactored into one subroutine whereas the original had 2-3 subroutines. 
Disadvantages - may take more time to edit, possible more debugging with initializing arrays in 'for' loops. It may run longer or even be more memory depending on length of code.

2)How do these pros and cons apply to refactoring the original VBA script?

Although I've been able to compress the original code from running multiple macros into a single one, I feel it took more time editing to fewer steps compared to original. Also, if one isn't familiar working with arrays it can lead to complications when debugging the code. Lastly, even though it's a great to have all code in one subroutine, my code took longer in terms of run-time compared to the original. In my opinion, it's more organized if there was separate subroutines to accomplish a function and takes less time to run. 
