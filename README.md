# A rebar-ized fork of [crone](http://catseye.tc/projects/crone/).

A simple `cron`-like facility written in Erlang. Unlike most `cron`s, it does
not periodically activate and run whatever tasks are due to run; instead it
calculates the amount of time between now and when the next is due to run and
sleeps exactly that long.
