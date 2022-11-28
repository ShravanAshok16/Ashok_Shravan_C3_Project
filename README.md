# Ashok_Shravan_C3_Project
Restaurant Finder Project
    Features
        RestaurantService.java: Acts as a service to interact with the actors
        Restaurant.java: Holds the details of a Restaurant
        Item.java: Holds the details of an Item
    Tests
        RestaurantServiceTest.java: Contains test methods to test all methods in RestaurantService class.
        RestaurantTest.java: Contains test methods to test all methods in Restaurant class. 

The Task
    Restaurant.java
        getMenu()
            Returns the list of items in the menu.
        isRestaurantOpen()
            Returns a boolean: whether the restaurant is open or not.
    RestaurantService.java
        findRestaurantByName()
            Searches for and returns the restaurant matching the input string.

  The following test methods are also to be implemented:

    RestaurantServiceTest.java
        searching_for_existing_restaurant_should_return_expected_restaurant_object()
           To test if findRestaurantByName() returns the expected restaurant object.
        searching_for_non_existing_restaurant_should_throw_exception()
           To test if findRestaurantByName() throws an exception when the restaurant cannot be found.
    RestaurantTest.java
        Is_restaurant_open_should_return_true_if_time_is_between_opening_and_closing_time()
           To test if the method isRestaurantOpen() returns true if the current time is between the opening and closing time.
        Is_restaurant_open_should_return_false_if_time_is_outside_opening_and_closing_time()
           To test if the method isRestaurantOpen() returns false if the current time is outside the opening and closing time.
