*** About me ***

Replication is used to share load among identical instances of a component. Applications
might need to elect a leader. We can have multiple leaders to be elected in parallel
across shards.

Leader election algorithm is complex and limited in libraries. We can co-schedule a leader
election container along with application. A simple HTTP can be used over localhost network
to perform election.

We can re-use leader election container across any application.