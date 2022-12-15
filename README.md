# CS360-Mobile-Architect-Programming

# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The app checks the username and password against the database when the user attempts to log in, if the user has never logged in before then they are able to create a new login and passowrd that is saved in the database. A completed database was developed to allow a user to create, delete, update, and read items related to inventory storage for an applciation. The user is also given the option to receive text alerts if the inventory count of a specific item reaches 0.

# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The necessary screens were login, register, the inventory home page, a page to add new items and update existing items. 

# How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

I began with the UI. I then turned my attention to Java and databases. I started by attempting to use fragments and instances. Although it was somewhat effective, it was very difficult to implement database operations that affected specific fragments. Utilizing activities was the second option I went with. This was considerably more successful because each activity had an own Java class where I could control the appearance and data. This was quite helpful in making my job as a coder lot easier, thus I would use it again. After I finally understood the fragment dynamic population, I was unable to delete from the database since the IDs would never match.

# How did you test to ensure your code was functional? Why is this process important and what did it reveal?

I mostly tested by launching the application in the emulators. Additionally, I could have run some JUnit tests. I also used Toasts a lot to emphasize when tasks were satisfactorily done. This procedure shows you where your code is failing, which is crucial because you want to test how it will function in a user's hands on a real phone.

# Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

I needed to be creative with the database functions. I required a system that could dynamically fill a list of weights based on the time that each entry was made. To start, I created a fragment and called an instance of it for each weight. It took some time, but it eventually worked. 

#In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

The UI was where I most effectively displayed my abilities. Although I believe the back end could use refinement, the user interface is, in my opinion, rather simple and clear. In my instance, I too believe the login process went really smoothly. 
