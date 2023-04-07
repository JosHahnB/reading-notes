# Day 13 notes

### Local Storage

The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. This is where local storage comes in. You would keep a key on the user’s computer and read it out when the user returns. 

You should not store objects or anything else in local storage, only strings. There are methods to  work around this by using the native JSON.stringify() and JSON.parse().

## Things I want to learn more about
