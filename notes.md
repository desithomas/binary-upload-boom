Does the client natively come with the ability to make a PUT request? 
    - No 

How can you make a built in POST request? 
    -forms 

Simple GET requests 
    -links, refreshing the page 

How have we been making PUT and DELETE requests up to this point? 
    -fetch
        - fetch is a web api is dependent on the environment to work; it needs to have the APIs that can work. if the client does not have the client available to it, the application cannot work 
        -there are situs where the client does not have the fetch api available to it; rn there is no native way to do PUTS and DELETEs

Forms by default are POSTS requests. 
    - if we need them to be a PUT then we need to override the method
        - the form uses the action to figure what to do 

What are some of the perks of not having any client side JavaScript? 
    -code can load faster 
    -we are no longer dependent on a client that exposes a fetch api -> a risk with older browsers or devices; kitchens, etc 
    -if they are loading HTML, they can load POSTS via forms. As long as the device supports HTML then the apps will always work 

{$inc: {fieldName: amount }} $inc is an update operator that atomically increments or decrements a numeric field in the database 

Where is the styling coming from? The classes are coming from Bootstrap. 

Where is the logic that says whether we should show the trash can or not? 
    -In the ejs

-Await?
    -pauses the execution of an async function until a Promise settles; lets you avoid having to keep using and chaining .then() and .catch()


    