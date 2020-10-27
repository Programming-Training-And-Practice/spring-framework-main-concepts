# Dependency Injection. DI.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Dependency Injection for 5 year olds.](#dependency-injection-for-5-year-olds)
* [Dependency Injection.](#dependency-injection)
* [Types of Dependency Injection.](#types-of-dependency-injection)
* [Concrete Classes vs Interfaces.](#concrete-classes-vs-interfaces)
* [Inversion of Control. IoC.](inversion-of-control.md)
* []()
* [Help](#help)





## About.





## Documentation.





## Dependency Injection for 5 year olds.
When you go and get things out of the refrigerator for yourself, you can cause problems. You might leave the door open, 
you might get something Mommy or Daddy doesn't want you to have. You might even be looking for something we don't even 
have or which has expired. What you should be doing is stating a need, "I need something to drink with lunch," and then 
we will make sure you have something when you sit down to eat.
John Munsch, 28 October 2009




## Dependency Injection.
* Dependency Injection is where a needed dependency is injected by another object.
* The class being injected has no responsibility in instantiating the object being injected.
* Some say you avoid declaring objects using ‘new’.
* Not 100% correct...





## Types of Dependency Injection:
* By class properties - least preferred.
  * Can be public or private properties.
  * Using private properties is EVIL.
* By Setters - Area of much debate.
* By Constructor - Most Preferred.





## Concrete Classes vs Interfaces:
* DI can be done with Concrete Classes or with Interfaces.
* Generally DI with Concrete Classes should be avoided.
* DI via Interfaces is highly preferred:
  * Allows runtime to decide implementation to inject.
  * Follows Interface Segregation Principle of SOLID.
  * Also, makes your code more testable.





## Best Practices with Dependency Injection:
* Favor using Constructor Injection over Setter Injection.
* Use final properties for injected components.
* Whenever practical, code to an interface.





## 
## 
## Help.
