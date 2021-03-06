# Browsermob Proxy
This python script is an example for implementing the browsermob proxy in order to get the HAR JSON file and parse the response as required
Used : Python v 3.5.1

# Script Functionality
#### test_case.py
A Selenium Python Script to perform the Network Request and Log Parameters

#### test_phantom.py
A Selenium Python Script to perform the Network Request and Log Parameters using PhantomJS


# Script Actions
### Task 1:
Go to google.com
Select search input
Put in 'search teat'
Click Search
Wait till results are shown
Click first result from organic search
### Task 2:
Once clicked URL has been loaded, please check the below :
● A request was made to google analytics (apply filter “collect”)
● A request was made to host: dc.optimahub.com (apply filter “optimahub”)
### Task 3:
Check that in google analytics (from previous point), has the following parameters
● dt
● dp
Log the values into csv log file.

# Prerequisite
 #### Install BrowserMob Proxy to handle NEtwork Data
 ```
 $ pip install browsermob-proxy
 ```
 #### Install Python unittest framework
 
 # How to Use with Selenium Webdriver
 1. Download the files test_case.py and parameters.py
 2. Run the file test_case.py
 ```
 $ python test_case.py
 
 ```
 3. The Test result will produce a CSV LOG file with parameters along with status of the request
 4. Use test_phantom.py script to run the above task using PhantomJS
 
 ```
  $ python test_phantom.py
  
 ```
