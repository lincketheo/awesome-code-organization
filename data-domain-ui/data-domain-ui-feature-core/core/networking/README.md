I contain networking code that __doesn't depend on any feature__. 

Maybe setting up network api clients.

The iffy line is do you contain your wire level api's in here if they relate very well to a specific feature? E.g. `NewEventController` - it relates to the `New Event` feature, but it's wire level
