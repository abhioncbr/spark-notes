# spark-notes [Notes/blogs/tutorials/talks around basics &amp; better optimzed usage Apache Spark]

1. Talk on tuning of Spark for big jobs by FB guys: [Tuning Apache Spark for Large Scale Workloads - Sital Kedia & Gaoxiang Liu -2017](https://www.youtube.com/watch?v=5dga0UT4RI8)

2. Talk on Catalyst & Tungsten framework by Sameer Agarwal: [SparkSQL: A Compiler from Queries to RDDs: Spark Summit East talk by Sameer Agarwal](https://www.youtube.com/watch?v=AoVmgzontXo)
  * Key takeaways:
    * Catalyst framework role in converting sql queries to logical plan to physical plan and than applying transformation to      produce optimized query plan.
    * Tungsten Framework introduction, sharing concept of [Volcana Iterator Model](https://paperhub.s3.amazonaws.com/dace52a42c07f7f8348b08dc2b186061.pdf) and brief introduction of [Whole-Stage Codegen](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6122906529858466/293651311471490/5382278320999420/latest.html)

3. Talk on Sql table bucketing support: [Hive Bucketing in Apache Spark - Tejas Patil](https://www.youtube.com/watch?v=6BD-Vv-ViBw)
 * Key takeaways:
   * Introduction to bucketing and how it is helping in reducing sortinf & shuffling operations done by spark sql planner.
   * Comparsion of bucketing support in hive & spark and various jira's tickets around spark sql optimization for bucketing. 
   
4. Talk on Spark's memory model & data aware cache: [A Developer’s View into Spark's Memory Model - Wenchen Fan](https://www.youtube.com/watch?v=-Aq1LMpzaKw)

5. Talk on Spark's cost based optimizer: [Cost Based Optimizer in Apache Spark 2 2 - Ron Hu & Sameer Agarwal](https://www.youtube.com/watch?v=qS_aS99TjCM)
