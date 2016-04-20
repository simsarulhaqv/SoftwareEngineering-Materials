##Unit test:

* Focus testing on a module.
* Simplified when a module is designed with high cohesion.
* Consist of Drivers and stubs. Stubs are useful in testing some module which communicate with other modules.
* Drivers are used to carry out testing on a set of modules and those drivers are called test drivers.


### Testing modules:
#### Top down integration
* Test main module first.
* Then integration test for subsequest modules.
* Driver are not needed.
* Costs of stubs are accounted at each level.
* For testing leaves, both drivers and stubs are not required.
#### Bottum up integration
* Test leaves first.
* Then integrate with the higher levels one by one.
* At each level we will have to use (all the parent nodes recursively as) drivers.
* Cost of drivers will accounted at each level.
* Stubs are not needed.
* One problem is that, error in the root is detected in the last stage.

:

