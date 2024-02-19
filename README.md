# Spark-s-Lazy-Evaluation-and-Data-Lineage


Lazy Evaluation in Spark is an approach where the execution of operations is postponed until their results are explicitly needed. In simpler terms, when you instruct Spark to perform operations on your data, it doesn't execute them right away. Instead, it notes down the tasks and patiently waits until you explicitly request the final result by triggering an action.

During this waiting period, Spark keeps a record of the operations you've specified, but it refrains from executing them immediately. The benefit here is efficiency—Spark only executes the necessary computations when you demand the final outcome, minimizing unnecessary work. So, it's not being lazy in a slacker sense; it's more about strategic efficiency, doing the required work at the right time to optimize performance and resource usage.
