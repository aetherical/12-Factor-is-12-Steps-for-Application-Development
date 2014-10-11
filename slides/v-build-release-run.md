##  V. Build, Release, Run
----

### Strictly Separate <!-- .element: class="fragment" -->
### Build and Run Stages <!-- .element: class="fragment" -->
#### Impossible to make changes to code at runtime <!-- .element: class="fragment" -->
##### Fix and redeploy! <!-- .element: class="fragment" -->
note:
    Build == transform code into executable bundle

	Release == Combine build & combine with deploy's config

	Run == run the app in execution environment

	Every release has a unique release ID -- that way you know what's running!

	Run should have as few moving parts as possible!
	
    
