# Stock Earning Impact

In this project, we divide the Russell 3000 stocks into 3 groups according to their earning surprise percentage and do the bootstrap to calculate the average AAR and CAAR based on IWV benchmark. We found that in general, stocks with higher surprise percentage would have higher CAAR after earning announcement date.

## Program Flow Chart

<div align=center><img width="600" height="500" src="https://user-images.githubusercontent.com/98775790/174504948-3997761f-61d8-46b8-8cfd-6a13c370ba35.png"/></div>

## UML Diagram


<div align=center><img width="800" height="500" src="https://user-images.githubusercontent.com/98775790/174504997-046e264a-558b-407b-b9d1-25c76ba20020.png"/></div>

## Averaged CAAR for Beat, Meet, Miss Groups


<div align=center><img width="800" height="500" src="https://user-images.githubusercontent.com/98775790/174505057-3a386e8e-4181-4ce8-a2d2-ea8f1f7f0a93.png"/></div>


## Conclusion

Earning releases of Russell 3000 stocks have a huge impact on their future stock prices, and stocks with higher surprise will have higher CAAR after earning announcement date.

<div align=center><img width="1000" height="450" src="https://user-images.githubusercontent.com/98775790/174505104-0e8ed909-c119-4896-9334-3476f27cc1ab.png"/></div>

## Additional Notes

- Some third party libraries (libcurl and json) are required to run the program
- Stock price data are downloaded from EOD database using multi-threading




