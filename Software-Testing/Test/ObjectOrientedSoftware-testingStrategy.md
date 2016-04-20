##Testing object oriented softwares

* Class testing is used in this case. It is analogous to unit testing in convenstional softwares.
* Focus on the operations encapsulated by the class
* Both drivers and stubs can be used.
* Drivers can be used to test a whole group of classes. Also used to replace the user interface, so that the software can be tested before the implementation of user interface.

###Strategies:

* Thread-based testing:
	- Integrates the set of classes required to respond to one input or event for the system. A thread(here) can be defined as the smallest unit of work, system can perform.
	- Each thread is seperately tested and integrated.
	- Regression testing is applied after.

* Use-based testing:
	- First test the independent classes.
	- Then add next layer of dependent classes.
	- And go on, until the entire system is constructed.
