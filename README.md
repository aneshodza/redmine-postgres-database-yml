# Redmine Postgres database.yml

This repository holds a working `database.yml` for Redmine if using Postgres for your database. The reason I created it was: When I tried running my redmine plugin in CI it wouldn't work, as semaphore had an older version of MySQL. That caused some issue with id's.

You can simply clone this `database.yml` into the config folder and use it out of the box.

This saved me a lot of nerves, I hope it does the same for you!
