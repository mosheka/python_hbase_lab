# python_hbase_lab
Open lab for python and hbase 

Your target is to create a users actions log table that could be used to detect users that had significant number of loses in their last games (lets say, 70% loses in last 10 games).

Implementation should be done using https://github.com/wbolster/happybase

Use for the following as a guidence: https://github.com/wbolster/happybase/blob/master/doc/user.rst

1. Create connection to HBase
1. Create a new table that could store: user id, action date, game type, result (amount of win/loss)
1. Insert random values for 1000 users and for each 100 games w/ reasults between -10 and 10
1. Find the users that in their last 10 games lost 70% of their games
	