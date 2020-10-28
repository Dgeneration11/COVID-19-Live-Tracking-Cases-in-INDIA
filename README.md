# COVID-19-Live-Tracking-Cases-in-INDIA.
![2019-nCoV-CDC-23312_without_background small](https://user-images.githubusercontent.com/57309408/79447620-c3674580-7ffd-11ea-935f-5564545e7ea4.png)

Coronavirus or COVID-19 doesn't need any introduction. WHO has already declared it as pandemic because of it's last couple of weeks impact.

As of now, most of people are working from home. I decided to utilize my time to build a <b>Python Script</b> that takes the data as input from the official website of Ministry of Health and Family Welfare, Government of India and turn that information to use to plot graphs in Python. I know so many scripts are already available on the Internet, but building yours is a good practice.

<h2>Packages/Libraries used are - </h2>
<b>
Pandas<br>
Seaborn<br>
Matplotlib<br>
Requests<br>
BeautifulSoup<br>
Prettytable <br>
</b>

<h2>Install the above mentioned packages - </h2>
I hope you know how to install them but if you don't then just <b> pip install package_name </b> in your termianl.
After installing we are good to go.

<h2> How is it working?</h2>
1. So basically, we are sending<b> GET HTTP</b> request to the url where you want the data from, and respond will be in HTML content itself. To do this we are using Requests library.<br>
2. Then we will use BeautifulSoup library to get the data from HTML content and store it in a form of List.<br>
3. Output the data in formats such as .csv .xlsx .json,etc. and we can use this data to plot graphs, tables, charts,etc using matplotlib, searborn, geopandas,etc libraries.
<h3>Extras-</h3>
If you want to learn more about scraping data from websites, there is a great blog. So check that out.
https://www.pluralsight.com/guides/extracting-data-html-beautifulsoup

  

