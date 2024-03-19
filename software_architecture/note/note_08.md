#note

https://refactoring.guru/design-patterns
lack
interpreter

https://github.com/viettranx/go-design-pattern

Behavioral
    #strategy
        It defines a family of algorithms, 
        encapsulates each one, and makes them interchangeable
        ex: ILogger.log(), FileLogger, StdLogger

Creational 
    #factory_method (virtual constructor)
        provides an interface 
        for creating objects in a superclass 
        but allows subclasses 
        to alter the type of objects that will be created
        ex: ILoggerFactory.getLogger() or ILogger.getLogger()
    #abstract_factory
        provides an interface 
        for creating families 
        of related or dependent objects 
        without specifying 
        their concrete classes.
        ex: theme , bright color text + black background, 
        ex: environment config, dev, stg, prd


