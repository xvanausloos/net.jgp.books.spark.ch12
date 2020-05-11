The examples in this repository are support to the **[Spark in Action, 2nd edition](http://jgp.net/sia)** book by Jean Georges Perrin and published by Manning. Find out more about the book on [Manning's website](http://jgp.net/sia).

# Spark in Action, 2nd edition - chapter 12

Welcome to Spark with Java, chapter 12. This chapter is about **data transformation**.

Datasets can be downloaded from:
* [United States Census Data](https://factfinder.census.gov/bkmk/table/1.0/en/PEP/2017/PEPANNRES/0100000US.05000.004|0400000US01.05000|0400000US02.05000|0400000US04.05000|0400000US05.05000|0400000US06.05000|0400000US08.05000|0400000US09.05000|0400000US10.05000|0400000US11.05000|0400000US12.05000|0400000US13.05000|0400000US15.05000|0400000US16.05000|0400000US17.05000|0400000US18.05000|0400000US19.05000|0400000US20.05000|0400000US21.05000|0400000US22.05000|0400000US23.05000|0400000US24.05000|0400000US25.05000|0400000US26.05000|0400000US27.05000|0400000US28.05000|0400000US29.05000|0400000US30.05000|0400000US31.05000|0400000US32.05000|0400000US33.05000|0400000US34.05000|0400000US35.05000|0400000US36.05000|0400000US37.05000|0400000US38.05000|0400000US39.05000|0400000US40.05000|0400000US41.05000|0400000US42.05000|0400000US44.05000|0400000US45.05000|0400000US46.05000|0400000US47.05000|0400000US48.05000|0400000US49.05000|0400000US50.05000|0400000US51.05000|0400000US53.05000|0400000US54.05000|0400000US55.05000|0400000US56.05000)

## Running the lab in Scala

Prerequisites:

You will need:
 * `git`.
 * Apache Spark (please refer Appendix P - "Spark in production: installation and a few tips"). 

1. Clone this project

    git clone https://github.com/jgperrin/net.jgp.books.spark.ch12

2. cd net.jgp.books.spark.ch12

3. Package application using sbt command

   ```
     sbt clean assembly
   ```

4. Run Spark/Scala application using spark-submit command as shown below:

   ```
   spark-submit --class net.jgp.books.spark.ch12.lab200_record_transformation.RecordTransformationScalaApp target/scala-2.12/SparkInAction2-Chapter12-assembly-1.0.0.jar  
   ```

Notes: 
 1. [Java] Due to renaming the packages to match more closely Java standards, this project is not in sync with the book's MEAP prior to v10 (published in April 2019).
 2. [Scala, Python] As of MEAP v14, we have introduced Scala and Python examples (published in October 2019).
 
---

Follow me on Twitter to get updates about the book and Apache Spark: [@jgperrin](https://twitter.com/jgperrin). Join the book's community on [Facebook](https://www.facebook.com/SparkWithJava/) or in [Manning's community site](https://forums.manning.com/forums/spark-in-action-second-edition?a_aid=jgp).
