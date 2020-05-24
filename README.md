# presentation

(Slide - What and Why?)
What angular is and why you would want to learn angular?
Angular is a framework that is used to build client side applications and it is especially great fpr building single page applications where parts of the view get refreshed asynchronously whithout having to reload the entire page so any application that reliese heavily on JavaScript angular is a great choice.
As opposed to some other JS framework or library there are a couple of points: the first one is that by design angular promotes modular approach and hence the application you buld will have a clear stuctures and by making use of components which is a feature of angular we can have a lot of reusable code. Angular has a lot of inbuilt capabilities such as validation, routing and so on which makes development quicker and easier. Anglar even makes it possible to write unit testable and easly maintainable code and finally angular is also a product from Google team and makes use of typescript language from Microsoft so it is safe to angular is here to stay with that let's take a brief look at angular's history.

(Slide - History)
The first version of angular whitch is popularly known as angularjs was released in 2010. this was a huge hit and a lot of organizations started using angularjs to build their enterprise applications, but then in 2016 angular version two whitch was called as just angular was released. It was announced that angularjs will refer to the 1 dot X version and angular without the js will refer to versions two and up. In december 2016 angular four was annouced version three was skipped to avoid a confusion due to the misallignment of the routers package verson with was already distributed as version 3.3.
And the latest Angular 9 was released on February 2020. Version 9 moves all applications to use the Ivy compiler and runtime by default. Angular has been updated to work with TypeScript 3.6 and 3.7.

(Slide - Module)
The architecture of an Angular application relies on certain fundamental concepts. The basic building blocks are NgModules, which provide a compilation context for components.
An NgModule is a class marked by the @NgModule decorator. @NgModule takes a metadata object that describes how to compile a component's template and how to create an injector at runtime. It identifies the module's own components, directives, and pipes, making some of them public, through the exports property, so that external components can use them. @NgModule can also add service providers to the application dependency injectors.

(Slide - Types of NgModules)
What Types of NgModules?
There are five types of NgModules:
1. Features Module
2. Routing Module
3. Service Module
4. Widget Module
5. Shared Module

Features Module – The feature modules are NgModules for the purpose of organizing an application code.
Routing Module – The Routing is used to manage routes and also enables navigation from one view to another view as users perform application tasks.
Service Module – The modules that only contain services and providers. It provides utility services such as data access and messaging. The root AppModule is the only module that should import service modules.
Widget Module - The third party UI component libraries are widget modules.
Shared Module – The shared module allows you to organize your application code. You can put your commonly used components, directives, and pipes into the one module and use whenever required to this module.

(Slide - Components)
Components
Every Angular application has at least one component, the root component that connects a component hierarchy with the page document object model (DOM). Each component defines a class that contains application data and logic, and is associated with an HTML template that defines a view to be displayed in a target environment.
Components define views, which are sets of screen elements that Angular can choose among and modify according to your program logic and data.
Components use services, which provide specific functionality not directly related to views. Service providers can be injected into components as dependencies, making your code modular, reusable, and efficient.

(Slide - Components decorator)
The @Component() decorator identifies the class immediately below it as a component, and provides the template and related component-specific metadata.
