*** About me ***
The side car container extends and works with primary container.
It's used when we have clear task separation b/w primary container and secondary tasks
that need to be done for it.

*** Example ***

Web server container(primary) needs to have its logs parsed and forwaded to log storage(secondary task).
We can use a sidecar Log saving container to store logs else where.