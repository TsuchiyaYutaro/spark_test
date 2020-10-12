# spark_test
pyspark での線形回帰

# Setup

イメージのインストール

```
$ docker pull jupyter/pyspark-notebook
```

コンテナ起動

```
$ docker run --name spark_test -it -p 8888:8888 -v $PWD:/home/jovyan/work jupyter/pyspark-notebook
```

上記表示される URL へアクセス
