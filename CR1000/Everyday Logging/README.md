Everyday Programs
================

These are examples of standard logging programs using common sensors. Nothing fancy here. Good, solid examples that have been running for years.

####Highlights####

* [Reading from a Turner Designs C3](CB.CR1#L64-L68) sensor using a non-polled serial connection. 

* A [fast sequence](ME.CR1#L204) running during the wait time on a [slow sequence](ME.CR1#L256). Many of the commands in the slow sequence (SDI-12 for example) take longer than 5 seconds. Despite those commands, all 5 second data are captured.
