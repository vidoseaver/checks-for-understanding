## Week One - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!). 

Note: When you're done, submit a PR. 

1. List the five common HTTP verbs and what the purpose is of each verb.
Get, put, POST, Delete
2. What is Sinatra?
Sinatra is a framework for building applications
4. What is MVC?
Model Vew Control 
5. Why do we follow conventions when creating our actions/path names in our Sinatra routes?
We follow conventions to take the thought out of it, so we can focus on the true logic, not re-invent the wheel everytime and make it easier for someone else to see whats going on.
6. What types of variables are accessible in our view templates without explicitly passing them?
Instance variables
7. Given the following block of code, how would I pass an instance variable `count` with a value of `1` to my `index.erb` template?
@count = 1
  
  ```ruby
  get '/horses' do
    erb :index
  end
  ```

8. In the same code block, how would I pass a local variable `name` with a value of `Mr. Ed`?
erb :index locals =>{name: "name"}
9. What's the purpose of ERB?
its how ruby interacts with html and css
10. Why do I need a development AND test database?
the development database a allows you to have a wider set of data, the test database repopulates each time?
11. What's responsive design?
uhhh
12. What is CRUD and why is it important?
Create, read update and destroy(or destroy, i forget). Its the basis of what we'll be doing all mod.
13. What does HTTP stand for? 
Hyper text transfer protocol
14. What are the two ways to interpolate Ruby in an ERB view template? What's the difference between these two ways?
<%= This way puts explicitly returns stuff %>
<% This way just does the thing %>

15. What's an ORM?
Object relational Database
16. What's the most commonly used ORM?
SQL
17. Let's say we have an application with restaurants. There are seven verb + path combinations necessary to provide full CRUD functionality for our restaurant application. List each of the seven combinations, and explain what each is for.
get "/" >> send you to the index.erb of all the resaurants
get "/create" >> send you to the make a resturant page
post "/create" >> makes the restaurant and send you back to the index.erb
get "/:id >> send you specific restaurant page displayed in a show
get "/edit" >> send you to the edit a specific resaurant page
post "edit" >> changes the stuff and redirect "/:id"
delete "/delete" deletes the stuff and redirect :index
18. What's a migration? 
Changeing or building stuff in your database
19. When you create a migration, does it automatically modify your database?
No,  it is a place to modify you data base from. you fill it out with what you want done then you rake db:migrate. Then you check your schema.
20. How does a model relate to a database?
A model the schema of a specific table, it will also hold methods for that table.
