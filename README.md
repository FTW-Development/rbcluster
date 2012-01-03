rbcluster
=========

Ruby bindings to the Cluster C library.

TODO
----

Functions:

  * Cluster.clustercentroids
  * Cluster.clustermedoids
  * Cluster::Tree#{cut,slice,[],fetch}

Other:

* an examples/ folder
* make :transpose work
* specs for bad inputs

DONE
----

* Cluster.pca
* Cluster.somcluster
* Cluster.treecluster
* Cluster.clusterdistance
* Cluster.kcluster
* Cluster.kmedoids
* Cluster.distancematrix
* Cluster.median
* Cluster.mean

See also
--------

* http://bonsai.hgc.jp/~mdehoon/software/cluster/software.htm
* http://bonsai.hgc.jp/~mdehoon/software/cluster/cluster.pdf
* http://github.com/jarib/rbcluster

Note on Patches/Pull Requests
-----------------------------

* Fork the project.
* Make your feature addition or bug fix.
* Add tests for it. This is important so I don't break it in a
  future version unintentionally.
* Commit, do not mess with rakefile, version, or history.
  (if you want to have your own version, that is fine but bump version in a commit by itself I can ignore when I pull)
* Send me a pull request. Bonus points for topic branches.

Copyright
---------

Copyright (c) 2011-2012 Jari Bakken. See LICENSE for details.
