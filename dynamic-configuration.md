The purpose of this branch is to try to enable Hazelcast to allow dynamic map-configurations even after the node have started. Note that it will not allow _changing_ the configuration of a Map, but it will allow a node to use the configuration of a map as it's defined by another node in the cluster.

[This issue](https://github.com/hazelcast/hazelcast/issues/380) defines the problem.

