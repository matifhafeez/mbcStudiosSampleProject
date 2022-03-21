# mbcStudiosSampleProject
A sample project from a hypothetical organization mbcStudios. 
The data shared in the file contains the profit earned for the 4 products (A, B, C and D) across different regions for a period of 5 days. What is expected from the data are 4 lines in one chart containing the percentage contribution across regions for a product for a period of 5 days. The product here needs to be a filter on the basis of which these lines should change based on dynamic calculation in Power BI.
The calculation needs to be done for each product on a daily basis for a particular date. For example for date 07/03/2021 :
(A)% east = 100/(100+175+225+57)
(A)% west = 249/(249+641+373+242)
(A)% north = 299/(299+233+427+383)
(A)% south = 421/(421+234+273+432)
Similarly the same should be done for all the other dates for A, B, C and D. When a user selects any of these products from the filter selection the percentage across regions for this category should change for the 5 days.
