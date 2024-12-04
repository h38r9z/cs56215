java cPLEASE READ ALL INSTRUCTIONS BELOW AND THROUGHOUT THE PROJECT CAREFULLY!
About the project:
For this project, you will select a firm of your choice from a subset of the SP 500 index firms available in the Excel file named Project 2 Stocks. Some firms in the index (marked with red   cells) are not   available for selection for various reasons.
Note on grading:
To give you an idea of how this project will be graded and points allocated to different sections and questions, a grading rubric is provided at the end of this Word document.    I will use this grading rubric to assign grades.
Write-up and Spreadsheet Instructions:
The project instructions and Excel template refer to the stock you pick as XYZ.    You should replace all instances of XYZ in your write-up and Excel file with your stock’s ticker.
Each project should include a write-up and Excel spreadsheet.    For the write-up, you should copy the write-up template on pages 3-7 and fill in the blanks.
You should use the project’s Excel template as your guide.    The Excel workbook (file) should have the following spreadsheets (tabs) with names and content as described below.NameContentDataIncludes all data used in the estimationsORPsAnalysis of optimal risky portfoliosCAPMCAPM estimation for XYZFFFama French 3-factor model estimation for XYZ
Project 2 Write-up
Section 1 – Data and Descriptive Analysis
1.   Download monthly data from June 1, 2016 to May 31, 2021 (5 years) from Yahoo! Finance for your stock.
a.   XYZ
b.   Analog Devices (ADI)
2.   Compute the HPRs to the securities.
3.   Compute the arithmetic average and sample standard deviation (use STDEV.S for this and all standard deviation calculations in the project) using HPRs and the Sharpe ratios of XYZ and ADI, as well as the correlations between the HPRs of the two securities.    Assume a monthly risk-free rate equal to 0.2%.    Fill in the following table:   XYZADI
Average
   
   
Sample standard deviation
   
   
Sharpe
   
   
Correlation
   
4.   Using your arithmetic average as the expected return and your standard deviation as the estimated risk for each security, compute the optimal risky portfolio for XYZ and ADI (assume no shorting and use Solver to find your solution).    Assume a monthly risk-free rate equal to 0.2%.
Weight XYZ
Weight ADI
Portfolio return
Portfolio risk
Portfolio Sharpe
   
   
   
   
   
Section 2 – CAPM and Fama French Estimations
1.   Please share with me why you have chosen to analyze XYZ.    You can be as brief or as detailed as you like.
Research XYZ, including discussions of its industry, competitors, and general business.    Focus your discussion on aspects of the company pertinent to understanding the firm’s betas (this includes coefficients on the market risk factor, SMB, and HML).
2.   Download monthly data from June 1, 2016 to May 31, 2021 (5 years) from Ken French’s data library   for the following.
a.   Three factors from the Fama-French 3-Factor model: mkt-rf, SMB, HML
b.   Market risk-free rate (rf)
Note all four items above can and should be retrieved from the same CSV file.
3.   Using the Fama French risk-free rate, compute excess returns for XYZ.    You are going to be estimating a CAPM and Fama French model.    Please use the Fama French market excess return (Mkt – rf) as your market index for both models.    
4.   Use your excess returns to estimate a CAPM regression for XYZ.    Use your beta estimates, along with a mo代 写Data and Descriptive Analysis
代做程序编程语言nthly risk-free rate of 0.2% and a monthly risk premium of 0.5% to estimate XYZ’s expected returns.    Continue to use your sample standard deviation of percent return (not excess returns) as your measure of risk.    Fill in the following table:
Alpha
   
Beta
   
Expected return
   
Risk
   
5.   Interpret your alpha and beta coefficients for XYZ.    Are they significant?    What do they mean?    Make sure to use your knowledge of XYZ in your beta discussion (see Question #1 in Section 2).6.   Find the optimal risky portfolio for XYZ and ADI using:
·   The expected returns derived from the CAPM as your measure of expected return for each security.    Note in the Excel template I have already provided the expected return for ADI implied by the CAPM.
·   The sample standard deviation of percent return as the measure of risk for each security (from the table from Question #3 in Section 1)
·   The correlation between HPRs as your correlation (from the table from Question #3 in Section 1)
·   A risk-free rate of 0.2%
Use Solver to find your answer, and assume no shorting.    Fill in the following table:
Weight XYZ
Weight ADI
Portfolio return
Portfolio risk
Portfolio Sharpe
   
   
   
   
   
7.   How does your Sharpe ratio for the optimal risky portfolio computed with the CAPM estimates of expected return (in the previous question) differ from the optimal risky portfolio computed with the sample averages as expected return (Question #4 in Section 1).    Explain the difference (Note: If you’re going to say a number is bigger because another number is smaller, a complete answer will include why that number is smaller.).
8.   Use your excess returns to estimate a Fama French regression for XYZ.    Use your coefficient estimates, along with a monthly risk-free rate of 0.2%, a monthly risk premium of 0.5%, a monthly SMB of 0.2%, and a monthly HML of 0.1% to estimate the stock’s expected returns.    Continue to use your sample standard deviation of percent return (not excess returns) as your measure of risk.    Fill in the following table:
Alpha
   
Beta
   
s (SMB beta)
   
h (HML beta)
   
Expected return
   
Risk
   
9.   Interpret your alpha, beta, SMB coefficient (s), and HML coefficient (h) for XYZ.    What do they mean?    Are they significant?    Make sure to use your knowledge of XYZ in your beta, s, and h in your discussion (See Question #1 in Section 2).
10.   Find the optimal risky portfolio for XYZ and ADI using:
·   The expected returns derived from the Fama French models as your measure of expected return for each security.    Note in the Excel template I have already provided the expected return for ADI implied by the Fama French model.
·   The sample standard deviation of percent return as the measure of risk for each security (from the table from Question #3 in Section 1)
·   The correlation between HPRs as your correlation (from the table from Question #3 in Section 1)
·   A risk-free rate of 0.2%
Use Solver to find your answer, and assume no shorting.    Fill in the following table:
Weight XYZ
Weight ADI
Portfolio return
Portfolio risk
Portfolio Sharpe
   
   
   
   
   
11.   You have now computed optimal risky portfolios using expected returns from historic averages, CAPM estimates, and Fama French estimates.    Which portfolio would you choose in which to invest and why?
   
   
   

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
