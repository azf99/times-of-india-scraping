# times-of-india-scraping
Code to scrape news articles from the website of the newspaper Times of India

# Setup:
pip3 install bs4 tqdm

# Steps:
1. Go to "https://timesofindia.indiatimes.com/" and search for your desired topic.
2. Then paste the link to that topic in the line 11 of the python code file
3. run the file using:- python3 code.py
4. I will take time, depending on the internet connection, and export the articles in CSV file with the format:
      {'Headlines': headlines,
                 'Article' : news,
                 'Published_Dates' : dates,
                 'Source_URLs' : urls
       }
       
