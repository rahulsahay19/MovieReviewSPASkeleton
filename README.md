Welcome to the Movie Review Application

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/Book_Cover.png)


I have created this app using bunch of client-server side technologies. Primarily, its built using ASP.NET Core, Entity Framework Core, Which is latest from Microsoft stack and also Angular JS. This SPA is marriage of tons of client/server side app. These are mentioned below. 

Client Side Technologies: –

***
  
  *  HTML 5
  *  CSS 3
  *  Modernizer & LESS
  *  Responsive Design
  *  Media Queries
  *  AngularJS
  *  Toastr JS
  *  Bootstrap Templates
  *  Font Awesome Icons
  *  Templating
  *  Bootbox
  *  Bower

Server Side Technologies

***


  *  NET Core
  *  SQL Server
  *  Entity Framework Core – Code First Approach
  *  Repository Pattern
  *  Unit of Work Pattern
  *  Web API
  *  JSON & AJAX
  *  NuGet
  *  IOC
  *  POCO Models

## Application Live Demo :- [Movie Review](http://moviereview.azurewebsites.net/#/)

Below is the glimpse of finished product in the best possible way.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/15th.png)
![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/16th.png)

Above shown screen shot is the home page of the app. Now, when you click on the Movies link, it will take you to the below shown page.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/17th.png)

Once, page gets loaded, little toast message at the bottom right of the screen pops up saying Movies Fetched Successfully. Now, from this screen you can do all the CRUD Operation. Here the very first link is Add Movie, which will give user flexibility to go ahead and add any new movie as shown below.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/18th.png)

Let’s suppose if we try to post the Form as it is blank, then it won’t allow. Because above fields are required and therefore form became invalid, which is taken care at angular level validation. Now, once I enter any information, different validation will get triggered.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/19th.png)

Even at this moment I cannot submit the form as the form is invalid. Once, I modify and enter valid details, then form will become valid and error messages will disappear.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/20th.png)

Now, at this instant I can go ahead and submit the movie. Once I click submit button; one toast message will appear saying Movie Saved Successfully and will get redirected back to movies link.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/21th.png)

Next is the Edit link corresponding to the movie. When you click on this, it will present the below screen for editing the same.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/22nd.png)

Here, also each and every validation will be there, what we have seen during creation. However, you can go ahead and edit anything over here, let’s say I change the year to 2002 and update.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/23rd.png)

Once I update the movie it will save the same in database and then get redirected to Movies link as shown below.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/24th.png)

However, let me change the same back to the original one as it’s not correct. Now, next to Edit link, there is review link, where in you can go ahead and add Reviews as shown below.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/25th.png)

Here, when I click on Add New Review, it will take me to the below form.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/26th.png)

Above form has also got different set of validations as shown below.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/27th.png)

Once done all the corrections, it will be like this

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/28th.png)

After successful, submission, it will redirect back to the movies link.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/29th.png)

Upon adding Review, position of newly added movie moves up in the list as behind the scene order by clause is working on total no of reviews. Now, when I click on the Reviews link again, it will show me the review which I have added.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/30th.png)

Similarly, I can go ahead and edit review as well by clicking on Edit link.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/31th.png)

Till now, we have seen create and update operation. However, site supports full-fledged CRUD operation. However, in order to delete any record, user has to login first. Therefore, anonymous user can’t delete any record. Hence, let’s go ahead and login in the app first.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/32nd.png)

In the above screenshot, when I click on Log in link, it will take me to the below login page.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/33rd.png)

Once, I logged in successfully, it will show my credentials on the top of the screen as shown below.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/34th.png)

Now, when I click on Movies link, it will produce the new links for deleting movie as well.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/35th.png)

Here, when I click on Remove button corresponding to any Movie, it will produce one confirmation popup as shown below.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/36th.png)

When, I click on Ok button, then it will delete the record and then get redirected back to the movies link as shown below.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/37th.png)

Also, for deleting reviews corresponding to the movie, first needs to refer the corresponding review as shown below.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/38th.png)

Then, in reviews screen, remove link will appear as shown below.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/39th.png)

Upon, clicking on remove button, this will also produce the similar behavior what happened in Movie. About App link lists all the details of the application like what technologies used what tools you need, where to download the code etc.….

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/40th.png)
![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/41th.png)

I have also used QUnit Library to test my Web APIs. Below is the glimpse for the same. You can refer the same [Movie Review API Tests](http://moviereview.azurewebsites.net/WEBAPITests/apitests.html).

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/42nd.png)

When you click on any individual test, it will present you the detailed results as shown below in the screen shot.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/43rd.png)

And if there is anything wrong with any end points, let’s suppose that doesn’t exist; easiest way to break the test, then it will be like

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/44th.png)

You can also verify these APIs like shown below

[Movie Review API](http://moviereview.azurewebsites.net/api/movies)

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/45th.png)

Similarly, different endpoints can be tested. Apart from Web API tests. I have also used Jasmine to test my Angular code. You will also learn how to test client side JavaScript code with Visual Studio. Below is the glimpse for the same.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/46th.png)

And Jasmine Spec Runner will produce the result like shown below.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/47th.png)

### Glimpse of Movie Review SOLUTION: –

Let me go ahead and show you the solution structure of finished app. Below in the screen shot, I have 5 different projects. Each is having its on dependency and responsibility.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/51th.png)

Here, the highlighted one is the web project which is dependent on other infrastructure projects like Data, Contracts and Model. Data project is the place where in you maintain initial seed data, Entity Framework DBContext and many other things interacts directly down the layer with database. Data Contract is the place where in you manage your repositories and apply Unit of Work Pattern on repositories like movies and moviereviews. Model is the section where you will be having your POCOs (Plain Old CLR Objects). This is also place for maintaining all properties attributed to the tables. Below is the glimpse of all projects in its expanded form.

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/52nd.png)

![](http://myview.rahulnivi.net/wp-content/uploads/2016/07/54th.png)


SUMMARY: –

In this section, we have seen the bits and bytes of the Single Page Application which we are going to make use while building the application. We have also seen the glimpse of app and solution. In the next section, we’ll start creating the application right from the scratch. I would recommend you to download the app from GitHub URL shown below to help you while building https://github.com/rahulsahay19/MovieReviewSPASkeleton.

P.S.:- I would appreciate if you guys leave constructive feedback upon reading the book. If you have any suggestions, please do put that too, so that going forward that can be incorporated. I hope, you people will like the book. With this, I would like to wrap the introduction here. However, in order to understand the book in detail, I do encourage you guys to watch the you-tube video for the same.

Links to Buy the book online.

Buy @ discounted price from [BPB Site](http://bit.ly/SPA-BPB)

or [Infbeam](http://bit.ly/Rahul-SPA-Infibeam)

or [Flipkart](http://bit.ly/SPA-Rahul-Flip)

or [Amazon India](http://bit.ly/Rahul-SPA-IN)

or [Amazon International](http://bit.ly/SPA-Rahul-Sahay)







