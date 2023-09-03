# Communicate Data Findings

### This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process:


#### [In Part I:](https://github.com/RawanAlsaedi/Communicate-Data-Findings/blob/main/Part_I_Ford%20Gobike%20Data%20Exploration%20Project.ipynb)  Exploratory data visualization, I used Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables.

#### [In Part II:](https://github.com/RawanAlsaedi/Communicate-Data-Findings/blob/main/Part_II_slide_deck_Presentation_v.ipynb)  Explanatory data visualization, I produced a short presentation that illustrates interesting properties, trends, and relationships that I discovered in the dataset. 

#### To Generate Slideshow:

Use the jupyter nbconvert command to generate the HTML slide show.  From the terminal or command line, use the following expression.

```
!jupyter nbconvert Part_II_slide_deck_Presentation_v.ipynb --to slides --post serve --no-input --no-prompt --ServePostProcessor.port=8885
```

## Required files
- [fordgobike-tripdata dataset:](https://github.com/RawanAlsaedi/Communicate-Data-Findings/blob/main/201902-fordgobike-tripdata%20(3).csv)
The dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area and containing the trip data of the ford gobike about 183,412 with 16 features.
- [Ford_Gobike_Data_Exploration dataset: ](https://github.com/RawanAlsaedi/Communicate-Data-Findings/blob/main/Ford_Gobike_Data_Exploration.csv)
Contain the data after exploration process.


## Notes
-This project was developed using **_Jupyter_ _Notebook_**.
- #### [Ford Gobike Data Presentation Slides:](https://github.com/RawanAlsaedi/Communicate-Data-Findings/blob/main/Part_II_slide_deck_Presentation_v%20slides.html)
  is the HTML slide show , this should open a tab in your web browser where you can scroll through your presentation. Sub-slides can be accessed by pressing 'down' 
        when viewing its parent slide.
 - #### [README File:](https://github.com/RawanAlsaedi/Communicate-Data-Findings/blob/main/README%5B1%5D%20(1).md)
   Contain the summary of findings and key insights for presentation.
