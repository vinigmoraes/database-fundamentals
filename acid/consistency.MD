# Consistency

We have two types of consistency in database, they are read consistency and write Consistency

## Read inconsistency

For example, if I have a cluster of database, we have the possibility when reading a data in some replica, that data is inconsistency because the master of cluster didn't replicate the data yet.

## Write inconsistency

When the user try to insert a data in database not following the rules given

Example:

Try to insert a data writing varchar in a integer column.
