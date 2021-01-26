# freelancer-project-1
This is my first project as a Freelancer. 
The client needed to scrap ~250K records present in the website on a periodic basis.
I wrote a Python script using BS4 and requests lib to scrape the website

## How to Run the script

To run it, simply download the script and run it as <p>python script.py</p>

## Libraries required

Make sure you have all the below libraries installed
1. bs4 <p>pip install bs4</p>
1. pandas <p>pip install pandas</p>

## How much time it takes to complete the script

The script usually takes 13-14 hours to complete scrape the whole 250K records. The script has been written in such a way that
it can wait and retry if there is internet connectivity issue while running the script which leads to no data loss while scraping.
