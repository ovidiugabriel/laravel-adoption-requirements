# Laravel adoption requirements

What I need from Laravel before being able to adopt it to my projects:

 * Add Route Annotations
    * https://tomgrohl.medium.com/using-route-annotations-in-laravel-9-2683e67eb955 (source: https://github.com/smashed-egg/laravel-route-annotation)
 * Implicit routes support
 * Add a better driver for MicrosoftSQL
    * stored procedure call support
    * vector for multiple result set of a single query and debug output
 * First class Firebase support
 * First class authentication using LDAP
 * Cookieless session support
 * Middleware for security rules
 * Better folder organization
    * I need all folders under the app folder (for example: logs not in `storage/logs` but in `app/logs`, view not in `resources/views` but in `app/views`, routes `app/routes.php` and not in `routes/web.php` etc. )
 * Better logger
    * Ability to print millisecond timestamp
 * Being able to install it without having to use composer 
