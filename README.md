##spark-training

Exercises and examples from Spark Summit 2014.

To run the examples, you need to define ```SPARK_HOME``` as an environment variable

and run ```sbt package``` to create the jar inside ```target``` folder.

Run them with ```spark-submit --class``` **class-name** ```target/scala-2.10/```*theJar*

If you have any problems installing Spark correctly take a look at my [Spark installation guide](https://github.com/tomduhourq/dotfiles/blob/master/install/spark)
