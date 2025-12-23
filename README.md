# Sportiko – Sports Matchmaking & Community App
#### Video Demo:  <ADD YOUR YOUTUBE LINK HERE>
#### Description:

Sportiko is an Android application designed to connect people through sports. The app allows users to create sports games, join games created by other players, communicate through in-app chat, and stay updated with the latest sports news in one place. It is built with Java and Android Studio, and it stores user and game data locally using SQLite.

The goal of the project is to solve a real world problem: many people want to casually play sports like football, basketball or tennis, but organizing games or finding enough players is often difficult. Sportiko makes this easier by providing a simple platform where games can be created, viewed, joined and discussed.

Users can register an account, log in, create a profile and then access the main features of the app. They can browse available sports games, create new ones by entering details such as location, time and number of required players, and view or join existing games. A built-in chat system allows users to communicate, coordinate and socialize within the app.

In addition to game management, Sportiko also includes a Sports News section. This feature uses Retrofit and an external News API to fetch and display live sports headlines. Articles are shown in a scrollable list with pull-to-refresh functionality. For security reasons, the News API key is not included in the repository. To enable this feature, you can create a free key at newsapi.org and insert it into the project.

The project follows good Android development practices such as using RecyclerView with adapters for displaying lists, separating logic into activities, data and model classes, and implementing a clean UI using Material Design components. SQLite is used as the database layer, managed through helper and DAO classes. Networking is handled with Retrofit, OkHttp and Gson.

This final project reflects the skills gained throughout CS50, including problem solving, programming fundamentals, data management, user interface design and working with external libraries and APIs. It was challenging but rewarding to design and build a complete, functional mobile application that could realistically be used by a community of players. I am proud of how Sportiko turned out and how it brings people together through sport.
