# Named Mercury Craters as of November 2024 
 
View project here: https://chilinhhovo.github.io/Mercury/

# Goal 
To see which continent has the most icons named on Mercury 

# Final output 
Charts and a write up of my findings 

# Tech stack used:
- Python — BeautifulSoup and Pandas
- Regex
- HTML + CSS 
- Google Sheets - pivot table 
- Illustrator 
- Photoshop

# Process summary
1. Found the list of crater names via Wikipedia, scraped Wikipedia for names https://en.wikipedia.org/wiki/List_of_craters_on_Mercury (code in notebook Scraping Wikipedia.ipynb) 
3. Scraped NASA links https://planetarynames.wr.usgs.gov/SearchResults?Target=14_Mercury&Feature%20Type=9_Crater,%20craters (code in notebook Scraping US site for ethnicity.ipynb) 
4. All data saved to (Ethnicity_Data.csv) 
5. Used Google Sheets to analyzed the data. This includes manually going over the sheet to define country's continent and figures' gender.  https://docs.google.com/spreadsheets/d/1zfwp9k8m24LGGS6zyZNjCFcMJ4KtZxq25E9qwja8F8E/edit?usp=sharing
6. Used DataWrapper to make chart
7. Used Flourish to make treemap and traced over using Illustrator to achieve the colour paletted I wanted (all charts are in Data Studio (Mercury).ai) 
8. Created hero image using Photoshop (hero_image_mercury.psd)
9. Write up

# Result 
1. Mercury’s Named Craters – The craters on Mercury are named after the most prolific literary and artistic figures in human history, rule set by International Astronomical Union’s (IAU).
2. Mercury’s Physical Features – It is a small, rocky planet with a heavily cratered surface due to meteoroid impacts, with notable basins like Caloris and Rachmaninoff. Cliffs formed due to the planet's interior contraction over time.
3. Europe’s Artistic Dominance – Over half of the crater names belong to European figures, reflecting historical cultural influence. France, Italy, and England have the most honorees.
4. America’s Cultural Rise – The U.S. has the highest number of individual names, reflecting its emergence as a creative powerhouse in the 19th and 20th centuries, with figures like Poe, Ellington, and Morrison.
5. Global Artistic Recognition – Though Europe and the U.S. dominate, figures from Asia (Tagore, Du Fu), Africa (Equiano, Umm Kulthum), Latin America (Mistral, Villa-Lobos), and Oceania (Namatjira, Beckett) also feature.
6. Gender Imbalance – For every woman honored, five men receive recognition, highlighting historical artistic exclusion. However, recent additions like Maya Angelou and Audre Lorde show progress.
7. Poetry Leads the List – More craters are named after poets than any other profession, showcasing poetry’s historical significance in storytelling and cultural preservation
8. Mercury as a Cultural Archive – The crater names provide insight into artistic history, gender disparities, and shifting cultural influences, immortalizing creativity in space.

# Things that are not working
- Video is not playing when published on Github, only on local host

# Lesson learned: 
- Do not use Illustrator to make charts, only to annotate and small tweaks. Tracing takes a long long time. 