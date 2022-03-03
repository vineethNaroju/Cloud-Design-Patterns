*** About me ***

In search engines, an external client sends an intial request to a root / parent node.
The root "Scatters" the request out to a group of servers to perform a set of tasks in 
parallel and each shard returns partial data. The root then "Gathers" and assembles data
into a single response.

We have a lot of generic code that can be put into containers to do most of the work.

Client -> Framework Supplied Root Container(Root - Scatter)

Root Query-> Dev supplied Container-1, Dev supplied container-2, etc.

Root merge([]response) -> Dev supplied Container