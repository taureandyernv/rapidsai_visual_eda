# rapidsai_visual_eda

These notebooks introduce you to where and how **cuxfilter**, the in-workflow visualization library in the RAPIDS ecosystem, can greatly enhance your exploratory data analytics capabilities.  By using these easy to create, dynamic, interactive charts and cross filtering capabilities, a data scientist can:
- visualize big data (millions of points) quickly and effectively - 25 million points, and their problems, understood in a few seconds
- get near real time interactions during their exploration
- add a higher level of visual context to more accurately verify their data comprehension - no more guessing!
- quick, code free clean and export their data- WYSIWYG style
- be able to validate the "goodness" of clustering and embeddings
- create end user (specialist) visualizations with Plot.ly Dash web apps or Graphistry 


There are 2 notebooks in this repo:
1. The notebook ending in **local** is a longer notebook that uses the ~2GB Jan 2015 Yellow Taxi Cab data.  It may require at least dedicated 16GB GPU to run without running out of memory as coded.  
1. The notebook ending in **bsql** is a "shared GPU resource" friendly version, using the much smaller Jan 2016 Green Taxi Cab dataset. It runs well on app.blazingsql.com, which now allows you to use the cuxfilter dashboard for that interactive experience.  

This was presented at PyData DC metup on 11/05/2020