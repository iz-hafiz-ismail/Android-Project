# Native_Android-Full-Project
There are two main languages for native android development. It was Java and Kotlin. From my observation, people have left java for Kotlin due to google saying that Kotlin will be the main language for android development but people can still use Java for development. Please keep in mind that my project structure is quite messy because this was a collection of my past project. I just optimized the code without changing the base code. If there are any issues, with my code, feel free to open a pull request or ask the question.

### Kotlin
- **[AllChef - Recipe application](https://github.com/iz-hafiz/RecipeApps-Hafiz-Android-Kotlin)** <br>
Basic Recipe application that user can display, edit, add and delete the recipe. A remote database was used for auth and a local database was for keeping recipe data. The recipe data in JSON format will be loaded up when the user is using the app for the first time. User can also reset the database. I created this project due to my job assessment for the mobile developer role where I was given a task to complete a recipe apps within 3 days. 


### Java
- **[BlackJack - Blackjack application]()** <br>
BlackJack is an app where you can play blackjack with comp. The animation was quite bad as I just code the animation myself using XML. So don't expect too much as it is the first app that my friend and I collaborated on together. My friend handles the auth and database-related code and I only do the BlackJack logic game. Both of us does the front-end together.

<br>
<br>

# Kotlin sub project
 Collection of my mini sub project for future refrences. Some project is list based on main component which I feel important during development process

## Project List
### Data Binding (Basic)
- **[User Info](https://github.com/iz-hafiz/Kotlin-sub-project/tree/main/Data%20Binding%20(Basic)/UserInfoDataBinding)**  
User Info app will view user data using data binding method. The data can be change using next and previous button.The goals of this app was to teach me basic concept of data binding
- **[Account List](https://github.com/iz-hafiz/Kotlin-sub-project/tree/main/Data%20Binding%20(Basic)/AccountListRecyclerView)**<br>
Account List is an app where it list out all account. We can add account by clicking add button(account randomly generated with unique id). Account data will be shown in recycler view. If user click on account data list, the data will be delete based on account that has been click.

### View Model + Live Data
- **[Match Score Counter](https://github.com/iz-hafiz/Kotlin-sub-project/tree/main/Live%20data%20%2B%20View%20Model/MatchScoreCounterLiveDataViewModel)**  
Match Score Counter was an app where it help user to count score mark. It is a very simple app which use View Model and Live Data with data binding method.

### Navigation Component Architecture
- **[Setting Navigation](https://github.com/iz-hafiz/Kotlin-sub-project/tree/main/Navigation%20Component%20Architecture/SettingInterfaceNavigationArchitectureComponent)**  
Setting Navigation is simple app to view profile in setting. Actually, it was my mistake for putting wrong name ;). So, this app was to help me learning how to use Navigation Architecture Component where as using single activity with multiple fragment.

### Room with Coroutine
- **[Account List Plus](https://github.com/iz-hafiz/Kotlin-sub-project/tree/main/Room/AccountListPlusRoom)**  
Account List plus is an app where it list out all account with some improvement. Now we can create account and save on local. Account data can be retrieved even apps is killed and will be shown in recycler view. We will be using Room and Flow to save and emit data. We doesn't replace it completely as at the end of the day, we still need convert it to Live data again to display. Throught this project we also learn interaction of data from database with view from start to end.

### Retrofit
- **[Album](https://github.com/iz-hafiz/Kotlin-sub-project/tree/main/Retrofit/RetrofitBasic)**  
Album is and apps to view photo that has been categorize based on user. As the name of the apps suggest, it only just to view image. I am using Retrofit to retrieve data from API call and Glide for displaying image from URL. The sorce of data is from https://jsonplaceholder.typicode.com/ where they provide user,album and photo but for some reason photo URL doesnt provide meaningful data when been called so i replaced  the source of image with random image from https://picsum.photos/ 
