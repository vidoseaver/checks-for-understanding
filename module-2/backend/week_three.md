## Week Three Recap

### Instructions
Fork this repository. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Questions

1. What are the 3 main features in an ERD?
entity-relationship diagram

3. What is the entry at the command line to create a new rails app?
rails _version_ new
4. What do Models generally inherit from in rails?
ActiveRecord::Base
5. What do Controllers generally inherit from in a rails project?
application controller
6. How would I create a route if I wanted to see a specific horse in my routes fitle assuming I'm sticking to standard conventions and that I didn't want other CRUD functionality?
horse_path(@horse)
7. What rake task is useful when looking at routes, and what information does it give you?

rake routes

8. What is an example of a route helper? When would you use them?

companies_path you use them as short hand intead of typeing out the route 

9. What's the difference between what `_url` and `_path` return when combined with a routes prefix?

path returns just the the thing after the .com i think url is everything


10. What are strong params and why are the necessary?

I'm not sure


11. What role does `form_for` play in helping us create our forms?

its a method provided by rails that sets up a form for whatever instance variable(s) you pass it


12. How does `form_for` know where to submit the user's input?

from the instance variable object you pass it

13. Create a form using a `form_for` helper to create a new `Horse`. 

14. Why do we want to validate our models?
