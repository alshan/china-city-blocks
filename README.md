# The City Blocks of Beijing in GeoJSON format

![beijing_city_blocks_2016.svg](./lets-plot-images/beijing_city_blocks_2016.svg)

### Content of this repository
                              
- ### `data/DT39` folder

The **"Boundaries and blocks in redefined cities of China 2011 & 2016"** dataset.
         
The `redefined_cities_2016_blocks` shapefile in this dataset
consists of 187 thousand blocks within the 4678 redefined cities, and
includes two attributes: the corresponding ID of redefined cities (CityID) and areas of blocks (Aream2).

The entire **"Boundaries and blocks in redefined cities of China 2011 & 2016"** dataset
is available for the download at [Beijing City Lab](https://www.beijingcitylab.com/data-released-1/data21-40/) (see dataset 39)
as a ZIP file.

Because this dataset's archive (DT39.zip) and the unpacked `redefined_cities_2016_blocks.shp` file (107.59 MB)
both exceed GitHub's file size limit of 100.00 MB,
this repository only stores a compressed copy of the `redefined_cities_2016_blocks` shapefile in the `/data/DT39` folder:
`redefined_cities_2016_blocks.zip`.


- ### `output/beijing_city_blocks_2016.geojson` (rendered on the figure above)
  
A GeoJSON file containing 4,401 Beijing city block (2016).

- ### `cities_and_blocks.ipynb`

A Jupyter notebook with a Python code which extracts the city blocks of Beijing from the
`redefined_cities_2016_blocks` shapefile.


### Credits

Song, Yongze, Ying Long, Peng Wu, and Xiangyu Wang. "Are all cities with similar urban form or not? Redefining cities with ubiquitous points of interest and evaluating them with indicators at city and block levels in China." International Journal of Geographical Information Science 32, no. 12 (2018): 2447-2476. Doi: 10.1080/13658816.2018.1511793