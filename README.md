Python Client for Indicative's REST API

This REST client creates a JSON representation of your event and posts it to Indicative's Event endpoint.

Features:

+ No external dependencies, so you'll never have library conflicts
+ Asynchronous, designed to never slow down or break your app
+ Fault tolerent

Sample usage:

    // First call init() with your project's API key
    init('Your-API-Key-Goes-Here');
    
    // Then record events with a single method call
    record('Registration', 'user47', {'Gender': 'Female', 'Age': 23});

You should modify and extend this class to your heart's content.  If you make any changes please send a pull request!

As a best practice, consider adding a method that takes as a parameter the object representing your user, and adds certain default properties based on that user's characteristics (e.g., gender, age, etc.).

For more details, see our documentation at: http://www.indicative.com/docs/integration.html



