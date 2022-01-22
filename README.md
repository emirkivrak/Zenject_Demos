# Zenject_Demos

I created this repository for working on demo projects with [Zenject](https://github.com/modesttree/Zenject), a Unity DI(Dependecy injection) framework.

## Dependency Injection
Dependency injection is a technique whereby one object supplies the dependencies of another object. A dependency is an object that can be used (a service). An injection is the passing of a dependency to a dependent object (a client) that would use it.  

This fundamental requirement means that using values (services) produced within the class from new or static methods is prohibited. The client should accept values passed in from outside. This allows the client to make acquiring dependencies someone else's problem.  

The intent behind dependency injection is to decouple objects to the extent that no client code has to be changed simply because an object it depends on needs to be changed to a different one.

Dependency injection is one form of the broader technique of inversion of control. As with other forms of inversion of control, dependency injection supports the dependency inversion principle. The client delegates the responsibility of providing its dependencies to external code (the injector). The client is not allowed to call the injector code. It is the injecting code that constructs the services and calls the client to inject them. This means the client code does not need to know about the injecting code. The client does not need to know how to construct the services. The client does not need to know which actual services it is using. The client only needs to know about the intrinsic interfaces of the services because these define how the client may use the services. This separates the responsibilities of use and construction.

## What is Zenject?
Zenject is a lightweight dependency injection framework built specifically to target Unity 3D (however it can be used outside of Unity as well). It can be used to turn your application into a collection of loosely-coupled parts with highly segmented responsibilities. Zenject can then glue the parts together in many different configurations to allow you to easily write, re-use, refactor and test your code in a scalable and extremely flexible way.  
*Source: [Zenject ReadMe](https://github.com/modesttree/Zenject/blob/master/README.md)*
