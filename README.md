# C-.net-MVC5-study

## New features that added in MVC 5
### Authethication filters
- A new kind of filter that can be used to include different types of authethication within the same controller

### Filter overrides
- A new kind of filter that is applied to action methods to prevent filters defined globally or on the controller from taking effect

### Attribute routing
- A set of attributes that allow URL routes to be defined within the controller class

## MVC easy explanations

### Model
- Which contain or represent the data that users work with. Theses can be simple view models, which just represent data being transferred between views and controllers.

### Controller
- incoming request handled by controllers.
- construct the data and send it to view
- contollers are just C# class

### View
- User interfaces

### what is Viewbag?
- ViewBag can be useful when you want to transfer temporary data (which is not included in model) from the controller to the view. 
- The viewBag is a dynamic type property of ControllerBase class which is the base class of all the controllers.

