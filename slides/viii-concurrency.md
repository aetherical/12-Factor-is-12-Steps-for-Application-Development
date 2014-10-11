##  VIII. Concurrency
----

### Scale Out <!-- .element: class="fragment" -->
##### -via- <!-- .element: class="fragment" -->
### Process Model <!-- .element: class="fragment" -->

note:
    This makes scaling much easier. VM's can only be so big!
	Lots of JVM's in a huge monolithic box == thread contention!
	Each type of work in its own process type.  Unix philosophy -
	lots of tools that do one thing well!

	Erlang uses this model

	Apache web server has multiple worker processes.

	Use a load balancer in front of workers to scale
    
