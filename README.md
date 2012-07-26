hive-join-predicate-test
========================

Given tables tmp_a and tmp_b

tmp_a
---

|a1|a2|a3|
|:-|-:|:-|
|facebook|7|daily|
|google|14|daily|
|facebook|21|daily|

tmp_b
---

|b1|b2|
|:-|-:|
|yahoo|2|
|facebook|4|

Join these tables on the columns tmp_a.a1 = tmp_b.b1
