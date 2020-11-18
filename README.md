# Dagger2DependencyInjection
 With Dagger, we don't have to write tedious and error-prone boilerplate code.


//****************     Firstly add these dependency in build.gradle(Module: app)***************//
implementation 'com.google.dagger:dagger:2.10'
annotationProcessor 'com.google.dagger:dagger-compiler:2.10'

//****************     Then create one java class as Named SharedPrefModule.java***************//
In SharedPrefModule, context is instantiated in its constructor.

//****************     Now create one Interface to create inject method***************//
MyComponent.java is my interface for this example.
