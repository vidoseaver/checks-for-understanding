## Week Two - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON - YOU are a web developer!!!). 

Note: When you're done, submit a PR. 

1. At a high level, what is ActiveRecord? What does it do/allow you to do?

Active record is a framework for SQL that has methods and allows data to be manipulated more easily.

2. What kind of methods are `belongs_to`, and `has_many`? (i.e. class or instance) Give an example.

pointers? I don't know/ forget the name -  but they point to other objects that they either belong to or have alot of.

3. What do they allow you to do?

They allow you to access the items from another table with the corresponding id.

4. What's the difference between agile workflow and waterfall method?

Agile is a closer production cycle that builds on itself. Waterfall is taking the long shot.

5. What is the difference between `#new` and `#create`?

new is the get method. create is  a post

6. At a basic level, what does cURL allow you to do?

Send stuff like it was being brought in from an outside ip? I think

7. In a database that's holding students and teachers, what will be the relationship between students and teachers? Draw the schema diagram.


students                  teachers
 id                          id
 name                       name
 teacher_id                           

belongs to teacher         has_many :students

8. Define foreign key, primary key, and schema.


Foriegn key: the teacher id in students
primary key: id in students
schema: the map of the table layout.

9. Describe the relationship between a foreign key on one table and a primary key on another table.


the primary key of teachers is the foriegn key in student

10. What are the parts of an HTTP response?


 you have the server, port then stuff and then params
 
11. Describe some techniques to make our Sinatra code more DRY. Give an example of when you would use these techniques.

Make methods for stuff you're doing over and overagain in your controllers.  For tests build them in the test helper.

### Optional Questions

1. Name your five favorite ActiveRecord methods (i.e. methods your models inherit from ActiveRecord) and describe what they do.
2. Name your three favorite ActiveRecord rake tasks and describe what they do.
4. What can you expect from a group as you begin working together? As you continue working together?
5. What two columns does `t.timestamps null: false` create in our database?
6. What cURL flag can you use to send a `POST` request?
7. What case does JSON (and JavaScript) use for multi-word variables?
8. What case does Ruby use for multi-word variables?
9. In a database that's holding schools and teachers, what will be the relationship between schools and teachers?
10. In the same database, what will you need to do to create this relationship (draw a schema diagram)?
11. Give an example of when you might want to store information besides ids on a join table.
12. Describe and diagram the relationship between patients and doctors.
13. Describe and diagram the relationship between museums and original_paintings.
14. What are some examples of acceptable values for the parts of an HTTP response?
15. What types of output do we want to test when we test our controllers?
16. What could you see in your code that would make you think you might want to create a partial?
17. Why might you use a helper method?
