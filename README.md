Cloud Balance
=============

An application to manage your cash and compute your cash flow.  Uses the bucket budgeting method. 


## Products
- [App Engine][1]

## Language
- [Java][2]
- [Angular JS][4]
- [Bootstrap][5]


## Setup Instructions
1. Import the project into Eclipse.
1. Make sure the App Engine SDK jars are added to the `war/WEB-INF/lib`
   directory, either by adding them by hand, or having Eclipse do it. (An easy)
   way to do this in Eclipse is to unset and reset whether or not the project
   uses Google App Engine.
1. Update the value of `application` in `appengine-web.xml` to the app ID you
   have registered in the App Engine admin console and would like to use to host
   your instance of this sample.
1. Run the application, and ensure it's running by visiting your local server's
   address (by default [localhost:8888][3].)
1. Deploy your application.



[1]: https://developers.google.com/appengine
[2]: http://java.com/en/
[3]: https://localhost:8888/
[4]: https://angularjs.org/
[5]: http://getbootstrap.com/2.3.2/