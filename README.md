# IDS_Project_UFO_Sightings

We had 3 goals in this project
1. Find out where and what kind of UFO-s are most frequently seen.
2. Find which US states report the most UFO sightings and how frequently they happen.
3. Have UFO sightings increased over time?

Data is taken from [ Kaggle ](https://www.kaggle.com/mysarahmadbhat/ufo-sightings?fbclid=IwAR39rZKoKOsv4znQwIEdm1BoeK5sMJ83QorBJ7qFSsulW-JIdgQPA051zN4)

[ Poster with results ](UFO_sightings.pdf)

### Installation info
This project uses the geopandas module, which is a pretty picky module. So in order for it to work properly, it is suggested that you create a new conda environment to run projects in. Follow these steps down below in your conda environment to set up a new environment. Additional info can be found [here](https://geopandas.org/en/stable/getting_started/install.html)                                                                                             
 > - conda create -n geo_env
 > - conda activate geo_env
 > - conda config --env --add channels conda-forge
 > - conda config --env --set channel_priority strict
 > - conda install python=3 geopandas

Also this project uses Reverse Geocoder module. For installing:
> - pip install reverse_geocoder

or

> - conda install -c conda-forge reverse_geocoder

### Used graphs

Most of the graphs are done using the Tableau program. So in order to view them, you should have Tableau installed, which can be done [here](https://www.tableau.com/). The file is in the folder "data" with name "Book1.twb". Down below is a short description for each graph:

1. **with USA** - sightings across world categorized by countries with USA
2. **no USA** - sightings across world categorized by countries withou USA
3. **Records adding/occuring** - table, where in columns are years of posting and in rows years when was UFO seen
4. **Popular months** - line graph, where sightings are categorized by years and months started from year 1965. 
5. **Records by year** - line graph, where sightings are are categorized by years.
6. **Records by months** - bar graph, where sightings are categorized by days of months and months.
7. **Records by days of month** - bar graph, where sightings are categorized by days of month.
8. **Records by hours and months** - bar graphs, where sightings are categorized by hours and months.
9. **Shapes by hours** - bar graphs, where sightings are categorized by shapes and hours.
10. **Shapes** - bar graph, where sightings are categorized by shapes.
11. **Duration in minutes** - bar graph, where sightings are group by range of minutes.

