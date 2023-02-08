# closures---modules

2. What are Closures?
Richard Bovell sums up what a closure is nicely: A closure is an inner function that has access to the outer (enclosing) function’s variables.

So when we talk about closures we’re just talking about regular functions that are nested inside some outer function. What makes them special is their persistent access to variables from the outer function, even when that function has finished executing.

When a function is finished executing, JavaScript’s “garbage collection” cleans up the function and removes any variables inside of it. This is to save memory. However, if those variables are being accessed outside the function’s scope somewhere else, they will stay around. This is closure

