# Observer


Following the implementation in the Book „Expert Python programming“ (n:\fem\AUTOMOTIVE\00_METHODEN\SoftwareentwicklungCAE\Documents\Books\python\Expert_Python_programming.pdf), page 334, modify the class Event in the following way:
1.	When subscribing to an event by “register”, observers provide not just the function that has to be called but also the subscriber ID.
2.	Modify the method “unregister” so that it accepts the subscriber ID instead of the function itself.
3.	Add methods “block”, “unblock” that accept subscriber IDs and temporarily exclude the specified observer from the notification.
4.	When subscribing to an event by “register”, the observers may provide some more context arguments. During notifications, these context arguments should be passed to the function called. Use the mechanism “*args” for this.
