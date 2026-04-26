# Continuos Integration Demo

A Looker project for demos of Continuous Integration. Built on top of the 'thelook' dataset.


###ERROR 1:

id technical name renamed as order_item_id. This will break an existing Look in the repository. Content validator should find the issue

 ### ERROR 2:

 Delivered dimension based on a mispelled field (missing _at)The SQL expression is not working. SQL validator should find the issue.

### Tests

Defined tests in in ci_demo model. e.g. orders_items_2021
