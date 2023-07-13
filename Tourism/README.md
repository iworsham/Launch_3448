# Launch Mod 3 Week 2 Assessment

## Questions (10 Points)

1. Define MVC and explain the purpose of each of the three parts of this pattern.
Model View Controller or better know as MVC is another way of organizing your code. The Controller chooses the View to display to the user, and provides it with any Model data it requires.
Model holds the data and the Controller uses that upon the users request to consider which View to display. The model and view never interact.
2. Explain the difference between the **New** route and the **Create** route.
The New route creates within the code, Create route creates within the database.
3. List all of the RESTful routes for the `employee` entity. Make sure to include the Route Name, Path, and HTTP Method for each of the routes. (2 points)
</br> Show,employees/show/:id,GET,
For the following three questions, explain both how to fix the error/bug and why the part of the code that was broken is important. (2 points each)

4. 
<img width="1213" alt="Screenshot 2023-06-13 102204" src="https://github.com/turingschool/launch-curriculum/assets/11747682/f37c233d-e7aa-483e-9f75-7c9b111811e5">

the view isnt passed anything, you need to give it the variable the you created because the index needs a database to pull hotels from.
5.
<img width="1245" alt="Screenshot 2023-06-13 102555" src="https://github.com/turingschool/launch-curriculum/assets/11747682/87c9fbf7-de63-4580-9b36-8632df27b91b">
the name of the view is "indexes", the name of the view must match the action inside the controller or else there would be no view to get.
6. 
<img width="1238" alt="Screenshot 2023-06-13 102856" src="https://github.com/turingschool/launch-curriculum/assets/11747682/a39b525d-ae05-463f-b724-be68aa70148c">

when using hotel in the foreach loop you must use "@" to let the code know you are using c# because it is a html file it wont know you are using c# unless you explicitly state it.
## Exercise (10 Points)

Make sure to first run `update-database` to populate the `Tourism` database used by this application.

This application already has the `Index` route for States.

Your task is to do the following:
1. Add the `Show` RESTful route to display the name and abbreviation for a particular state.
1. Add a test for your new `Show` route in the `StateCRUDTests.cs` file.
