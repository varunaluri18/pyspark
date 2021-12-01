# pyspark

Operations Performed on RDD's:
I.Transformations(Narrow and Wide Transformations)
II.Actions

I.Transformations:

1.Narrow Transformations
2.Wide Transformations

Narrow Transformations: Narrow Transformations are applied to a single partition of parent RDD to generate new RDD as the data required to process the RDD in available on the single partition of parent RDD
example:
.map()
.filter()
.flatmap()
.partition()
.mapPartitions()

Wide Transformations: Wide Transformations are applied on to multiple parttions of an RDD as the data required to generate a new RDD is present among the multiple partitons of the Parent RDD.
.reduceBy()
.union

II.Actions:
.collect()
.count()
.first()
.take()
