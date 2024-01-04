### pyspark setup
Note this setup is adapted from following repo : https://github.com/jplane/pyspark-devcontainer for learning from the following book : **Spark The Definitive Guide**

#### requirements
* install docker-desktop
* install vscode
* install vscode extension : dev containers

#### open in dev-container
* open command-pallete and select: reopen in container

##### note :
* this repo(spark_basics) uses some resources from the following repo for running : https://github.com/databricks/Spark-The-Definitive-Guide
* clone this at the root of the project : `git clone https://github.com/databricks/Spark-The-Definitive-Guide`


#### changelog :
* original repo doesn't work on m1 macs : added this to devcontainer.json to fix :`	"initializeCommand": "ls"`