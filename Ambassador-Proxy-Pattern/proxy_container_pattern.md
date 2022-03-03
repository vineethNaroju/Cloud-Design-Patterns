*** About me ***
Proxy container acts as a external service discovery layer. It also takes care of
connections and updating config.
This pattern is unique to containers since all pods running on same node share
the localhost network interface.

*** Example ***

POD [
    App-Container -> Proxy ambassador ->1, ->2, ->3 
]

Like proxying to different memcache shards (NICE)