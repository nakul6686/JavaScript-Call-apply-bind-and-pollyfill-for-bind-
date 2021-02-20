# JavaScript-Call-apply-bind-and-pollyfill-for-bind-
JavaScript Call(), apply(), bind(), and pollyfill for bind() examples are given and also check readme file to theory part.


1. Bind() method returns a bound function that can excute later. call() and apply() functions invoke the function immediately.
2. Frist parameter in all these methods sets "this" value, which is the object on which the function is invoked upon.
3. The first argument should always refrence object and rest are the others arguments.
4. Bind() and call methods take argument like (object, "Jammu", "Kishtwar") but the apply method is take rest parameters except refrence object as an list of array like (object, ["Jammu", "Kishtwar"]).
5. Pollyfill for bind is custom method which should behave like bind() method.
Please checkout given examples in index file.
