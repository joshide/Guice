We need to create google guice injector in main class. Injector.createInjector().
Here we define all our guice modules.
These guice modules extends AbstractModule.
@Override configure : where we bind implementation to interface in case of many implementations.
@implementedBy
Guice Module's wins over @implementedBy
injector.getIntsance : return the instance of class or interface
Provider helps in lazy initialization
We can have both implicit and explicit providers
Providers can be defined within guice module using @Provides