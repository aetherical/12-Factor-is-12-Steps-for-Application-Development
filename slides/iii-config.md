##  III. Config
----

### Store Config in the Environment

* Strict separation of config from code. 
* Config varies across deploys, code _does not_. 
* Doesn't include internal app config, such as `config/routes.rb` in Rails. 
* Don't check config into code repository. 
* Environment Variables are agnostic. 
* Environment set at _RUNTIME_. 

note:
    This one is perhaps a bit contentious.

	Avoids situations where code isn't same across environments

	
