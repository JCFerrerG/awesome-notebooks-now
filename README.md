# awesome-notebooks-now

## Description 

A curated quick-start for experimenting with [notebooks interfaces](https://en.wikipedia.org/wiki/Notebook_interface).

Get started with a single `docker-compose up`!

Includes these notebooks (grouped by emphasis):

* Python and data-science
    * [Jupyter Docker Stacks](https://jupyter-docker-stacks.readthedocs.io/en/latest/)
        * [datascience-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-datascience-notebook)
        * [tensorflow-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-tensorflow-notebook)

* Scala and Spark
    * [Apache Zeppelin](https://zeppelin.apache.org/)
    * [Jupyter Docker Stacks](https://jupyter-docker-stacks.readthedocs.io/en/latest/) - [all-spark-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-all-spark-notebook)
    * [spark-notebook](https://github.com/spark-notebook/spark-notebook) (via [andypetrella/spark-notebook](https://hub.docker.com/r/andypetrella/spark-notebook/))

## Getting Started

* Run `docker-compose up`
* Navigate to the desired notebook:
    * Jupyter Docker Stacks
        * all-spark-notebook: http://localhost:8090/?token=test
        * datascience-notebook: http://localhost:8091/?token=test
        * tensorflow-notebook: http://localhost:8092/?token=test
    * spark-notebook: http://localhost:8080
    * zeppelin-notebook: http://localhost:8081

## See Also

More awesome notebook resources!

* [Jupyter Notebook support in Visual Studio Code](https://code.visualstudio.com/docs/python/jupyter-support)
* [Google Collab](https://colab.research.google.com)
* [markusschanta/awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)