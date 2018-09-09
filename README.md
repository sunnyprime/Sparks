# Sparks

## Install pySpark in ubuntu

#### 1. Check python and python 3

```
python
python3
```

#### 2. Install pip

```
sudo apt install python3-pip   
```

#### 3. Install jupyter notebook

```
pip3 install jupyter
```

#### 4. open jupyter notebook

```
jupyter notebook  
```

#### 5. Update System

```
sudo apt-get update
```

#### 6. install java
```
sudo apt-get install default-jre
```

#### 7. check java version
```
java -version
```

#### 8. install scala

```
sudo apt-get install scala
```

#### 9. check scala version

```
scala -version
```

#### 10. connect java and scala with python

```
pip3 install py4j
```
### download apache sparks .tgz and paste it to home directory

#### 11. unzip the file
```
sudo tar -zxvf spark_filename.tgz
```

```
export SPARK_HOME=’home/prime/spark_folder name’

export PATH=$SPARK_HOME:$PATH

export PYTHONPATH=$SPARK_HOME/python:$PYTHONPATH

export PYSPARK_DRIVER_PYTHON=”jupyter”

export  PYSPARK_DRIVER_PTHON OPTS=”notebook”

export PYSPARK_PYTHON=python3
```
### ------perimission problem------

#### 12.  give permission to that folder
```
sudo chmod  777 spark_folder name
```

#### Install findspark

```
pip3 install findspark
```
