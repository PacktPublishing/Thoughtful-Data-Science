# Thoughtful Data Science
This is the code repository for [Thoughtful Data Science](https://www.packtpub.com/big-data-and-business-intelligence/thoughtful-data-science?utm_source=github&utm_medium=repository&utm_campaign=9781788839969), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book


Data science has become the one scientific endeavor every business has to contend with today. We also need to learn why data algorithms work, but even more importantly, we need to be able to create new insights from our data that we can actually work with. The why is addressed in many publications today, but it is not easy to create insights such that the data scientist does not look like a mountebank creating opaque notebook code before getting to the visually compelling bits of data science: the data science process itself has to be transparent, easy to understand, and it has to be straightforward to optimise.

David Taieb created Pixiedust in Python to be able to teach non-data scientists to use Jupyter notebooks, without having to slog through the considerable amount of Jupyter code required to be able to create simple and sometimes not-so-simple insights into data. It is possible to use Pixiedust by just writing a few lines in HTML and CSS, while retaining the ability to drop or remove algorithms and visualisation options, adjust the data pipeline to the requirements posed by the data or just get some very quick results. The case studies represent a carefully graded ladder of progress, ranging all the way from data mined from social media to geo-analytical data helpful in business decision making.

It is, however, possible to use both Python and Scala to add features to the Pixiedust data pipeline, and ultimately, to bring the power of the Spark big data framework to the data scientist.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
import pandas
data_url = "https://data.cityofnewyork.us/api/views/e98g-f8hy/rows.
csv?accessType=DOWNLOAD"
building_df = pandas.read_csv(data_url)
building_df
```

Most of the software needed to follow the example is open source and
therefore free to download. Instructions are provided throughout the book,
starting with installing anaconda which includes the Jupyter Notebook server.
In Chapter 7, Big Data Twitter Sentiment Analysis, the sample application
requires the use of IBM Watson cloud services including NLU and Streams
Designer. These services come with a free tier plan, which is suffi cient
to follow the example along

## Related Products
* [Beginning Data Science with Python and Jupyter](https://www.packtpub.com/big-data-and-business-intelligence/beginning-data-science-python-and-jupyter?utm_source=github&utm_medium=repository&utm_campaign=9781789532029)

* [Hands-On Data Science with Anaconda](https://www.packtpub.com/big-data-and-business-intelligence/hands-data-science-anaconda?utm_source=github&utm_medium=repository&utm_campaign=9781788831192)

* [Hands-On Data Science with Command Line](https://www.packtpub.com/big-data-and-business-intelligence/hands-data-science-command-line?utm_source=github&utm_medium=repository&utm_campaign=9781789132984)
