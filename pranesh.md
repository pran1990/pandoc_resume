Pranesh Pandurangan
===================

-----------------------
praneshpg@gmail.com 
http://lnkd.in/KmtDgn 
(408)-893-0689
-----------------------

Education
---------

2011-2013
:   **MS, Computer Science** Georgia Institute of Technology(Atlanta)

    *Specialization: Systems*

2007-2011
:   **BTech, Computer Science and Engineering** National Institute of
    Technology(Trichy)


Experience
----------

**Software Engineer, Dropbox**, Nov 2016 - 

* As a two-engineer team, moved all of the app infrastructure state from
  MySql to Dropbox's custom graph database.  
* Design and implement techniques to allow apps to scan a team's dropbox
  efficiently, as part of a larger project to normalize filesystem and shared
  folder authorization across the company. 
* Remove Amazon S3 dependency in our file upload API.  
* API Proxy
    * In context of breaking down our monolithic code into services, design and
      implement an external facing service to proxy API requests to internal
      services.  
    * Move dropbox from multiple IDLs to one (protobuf)  
    * Design a standardized auth object to pass around between internal services.


**Senior Software Engineer, GoDaddy Inc**, Mar 2016 - Nov 2016  

* Prototype managed Kubernetes cluster
* Prototype managed Openstack Ironic cluster

**Tech Yahoo, Intermediate, Yahoo Inc**, Jul 2013 - Mar 2016

[Openstack](http://www.openstack.org/) developer 

* Getting OpenStack to be used at Y! (as its core infrastructure), which 
  involved code changes to OpenStack, conferences and session talks on needed 
  features (ie to be used at Y! scale) and integration into Y!'s core systems 
  and ensuring the work that Y! does is given back to the community.

    * Techniques to package and deploy openstack robustly at Yahoo using
      [anvil](http://www.github.com/openstack/anvil). We went from deploying
      once in six months (once every major upstream release), to being able to
      deploy at every commit.

    * Work on integrating the openstack provision and deprovision flow into
      Yahoo’s provisioning system. Integrate into Yahoo’s dns, ops, load
      balancer databases/services.

    * Work on a fork of openstack to allow us to migrate a six-figure number of
      machines at Yahoo to a more elastic model. An outcome of this that I was
      responsible for was to reduce the SLA for obtaining a new machine in a
      standard configuration from O(months) to under 5 hours. Two major chunks
      I worked on were to design a Yahoo-focussed, generic quota system, and to hack at
      the scheduler to handle a 10x higher load than it was designed for.

    * Work on improving the community baremetal project,
      [Ironic](http://www.github.com/openstack/ironic) to improve concurrency
      by elminating some race conditions in the scheduler. This was a community
      solution that I implemented, tested and proved better (through scale 
      tests).

**Graduate Research Assistant, Georgia Tech**, 2012-2013  

* Computation Offloading for mobile applications  
  Automatically detect and offload computation-intensive components of mobile 
  applications to the cloud, while accounting for intermittent connectivity to
  the internet. Implemented on android.
    * COSMOS: Computation Offloading as a Service for Mobile Devices.  
      Cong Shi, Karim Habak, Pranesh Pandurangan, Mostafa Ammar, Mayur Naik,
      and Ellen Zegura. MobiHoc'14: ACM Symposium on Mobile Ad Hoc Networking 
      and Computing.
* Intermittent Storage for Mobile Devices  
  Framework to enable mobile devices to temporarily offload files to nearby devices
  when out of space and lacking network connectivity. Implemented the framework in the
  [ONE simulator](http://www.netlab.tkk.fi/tutkimus/dtn/theone/)

**Interim Engineering Intern, Qualcomm Inc.**, 2012  

* Designed and implemented a task level profiling tool in C and Python. This
  was a software implementation of a hardware tool used in judging modem
  performance


Technical Experience
--------------------

Programming Languages
:   Python, C, C++, Java
