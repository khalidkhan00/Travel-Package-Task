# Travel-Package-Task
#Each travel package has a name, a passenger capacity, an itinerary (list of destinations) and a list of it's passenger
#Each destination has a name, and a list of the activities available at that destination
#Each activity has a name, a description, a cost and a capacity. Each activity is available at one destination only.
# each passenger can sign up for zero or more activity at each destination of the travel package.
# Once an activity has reached it's capacity no more passengers can sign up for it.
# Each passenger has a name and a passenger number
#. A passenger can be a standard, gold or premium passenger. 
    1. A standard passenger has a balance. And each time a standard passenger signs up for an activity the cost is deducted from their balance. They cannot sign up for an activity if they do not have sufficient balance.
    2. A gold passenger has a balance. Each time a gold passenger signs up for an activity, a 10% discount is applied on the cost of the activity and the discounted amount is deducted from their balance. They cannot sign up for an activity if they do not have sufficient balance.
    3. A premium passenger can sign up for activities for free
