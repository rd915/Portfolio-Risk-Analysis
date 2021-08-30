# whale_portfolio

This project imports several .csv files using Pandas and creates Panda dataframes. It performs a comparative analysis of the returns, volatility, and risk_adjusted returns of stock portfolios and the S&P. It solves the problem of performing the calculations individually on each portfolio and allows the user to perfom the calculations simultaneously on all the portfolios using Panda dataframes.

## Technologies

This project uses Python 3.8 and iPython in Jupyter Lab.  Windos 10 is the operating system.

### Libraries Used
    Pandas - used to create dataframes and manipulate data in dataframes
    Numpy - used to perform calculations on data
    Datetime - specifies date and time
    Path - path library used to set filepath
    matplotlib - used to graphically display data and calculations
    
## Installation Guide
This project requires the latest version of Anaconda

## Examples

![](./Images/combineddataframe.jpg)


## Usage 

To use this project change the path to your desired .csv files and import.

        # Set filepath
        csvpath = Path('./budget_data.csv')
        
Once you have set the proper file path, run the program, and view the analysis.

After the program has run, check the location of the generated text file. 
        
        # Sets path for analysis.txt
        output_path = Path("analysis.txt")


     
## Contributors
Ryan Dibeler

ryandibeler@gmail.com

## License
MIT License

Copyright (c) [2021] [Ryan Dibeler]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



