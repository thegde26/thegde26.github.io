---
layout: post
title: "Series: Learning Web Development, Day 1"
date: 2020-09-07
---

<p>
Hello! Today I'm attempting my first of what will be a series of experiments in web development. 
I'm a complete beginner when it comes to web development, so this will be fun and challenging. 
My goal is to familiarize myself with a few different popular web frameworks so that I can better understand the pros and cons of each framework and grasp concepts that can only be learnt through doing. 
</p>
<p>
Here are the web frameworks I'd like to learn: 
</p>
<ol>
 <h1><li>Python - Django</h1>
     <p>To get started I'd like to try out the Django framework based on Python. I think Python is an easier to learn language and is something I'm already familiar with.</p>
     <ul>
          <li><p>With Django, I'll work on creating a Discussions Board website following the tutorial <a href="https://simpleisbetterthancomplex.com/series/beginners-guide/1.11/">here</a></p>
          </li>
     </ul>
</li>
<h1><li>Javascript/JSX - React</h1>
    <p>React is everywhere nowadays. React is actually a library and not a framework, but it seems to be a highly popular choice for application development.  
    Although there seems to be a bit of a learning curve with React, I'm willing to give it a try since it's so popular.</p>
    <ul>
         <li><p> With React, I'll attempt to make a To-Do List App following the tutorial <a href="https://www.kirupa.com/react/simple_todo_app_react.htm">here</a></p></li>
    </ul>
</li>
<h1><li>Ruby on Rails</h1>
    <p>Ruby also appears at the top of the list in popular frameworks being used today. It seems to be a developer friendly framework that uses the MVC model.</p>
    <ul>
         <li><p> With Ruby on Rails, I'll try the To-Do List App following the tutorial <a href="https://medium.com/@deallen7/how-to-build-a-todo-app-in-rails-e6571fcccac3"> here</a></p></li>
     </ul>
</li>
     
<hr />
<h4>Update on Today's Progress</h4>
<p>
I began working on the Django tutorial for building a discussion boards website. There are 7 parts in the series, and I made it through the first 3, and halfway into Part 4. 
</p>
<p>
The first section was helpful in showing me how to download Django and set up a virtual environment for Python - this basically allows you to isolate any libraries or    plugins into your specific Python project, so you're not downloading anything to your entire system that would affect other python projects.
</p>
<p>
The next few sections gave a very thorough look at all the steps needed for creating a Django application. Since I'm completely new to web development, this was a bit overwhelming, and I know I didn't grasp everything that I was doing through the tutorial. However, it was good to get my feet wet in this area, which is something I've been interested in learning for a long time.
</p>

<h5>The main takeaways from Day 1 are:</h5>
<blockquote>
     <ol>
          <li><p> manage.py -> this is used for starting the server, the command used to start the server is python manage.py runserver </p></li>
          <li><p> There is a concept of Apps vs Projects. An app can be a functioning part of a project (think User Authentication or the Discussion Boards) and these app(s) make up the >overall Project. The idea behind this is you can reuse apps across different projects, making it more flexible and modular.</p></li>
          <li><p> We used a base.html which had the overall template for each of the pages and then each specialized was an extension of the base.html. The html pages also all included placeholders that are dynamic</p></li>
          <li><p> Django comes with a SQLite database so in the models.py section, we specified the database tables as classes along with their respective columns as fields. You can include foreign keys to link tables together and also specify the field types</p></li>
     </ol>
</blockquote>

<p>
There's definitely a lot of stuff I'm still fuzzy with like what we did in the views.py, settings.py, and within the html files, but I feel good about making it this far on my first day!
</p>

     
 
    
     
     
   
