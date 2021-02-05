# Small PySpark example using the Google Cloud Platform

In this small example I connected a Jupyter Notebook to Google Cloud Platform (GCP), loaded some data from a BigTable there (using SQL and PySpark) and draw some small graphics. 

I was following this article:
https://towardsdatascience.com/data-science-for-startups-pyspark-1acf51e9d6ba

Screenshot for Google Cloud Platform (use your own google Account, installation takes only some minutes):

![Screenshot GCP BigQuery](https://user-images.githubusercontent.com/55921277/68198234-ef48be80-ffbb-11e9-9736-ff91a4add59d.JPG)

Run the Jupyter Notebook , e.g. by downloading it from here: https://github.com/AndreasTraut/PySpark-Google-Cloud-Platform-Example/blob/master/GCP%20Projekt%20analog-marking-258015.ipynb and uploading it to the Jupyter-Binder (https://jupyter.org/). 

Screenshot for Jupyter Notebook (same table as from GCP is shown):

![Screenshot Jupiter Query](https://user-images.githubusercontent.com/55921277/68198235-efe15500-ffbb-11e9-996f-629e0d3e44e0.JPG)

Use Python-Code:

births[['weight_pounds', 'mother_age']].hist()

Screenshot for Chart:

![Screenshot Chart](https://user-images.githubusercontent.com/55921277/68198233-ef48be80-ffbb-11e9-8f3a-a3e7b7759bbe.JPG)

