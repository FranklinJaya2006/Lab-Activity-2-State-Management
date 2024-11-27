# Lab-Activity-2-State-Management

## How to use this code : 
### First, 
``` cmd
git clone https://github.com/FranklinJaya2006/Lab-Activity-2-State-Management.git
```
### Second, if you want to run Scoped or Ephemeral u can
``` Terminal
cd app_state_codelab / ephemeral_state_codelab
```
### Third, in terminal run this command
``` Terminal
Flutter run
```
### After that, u can start from step 2, for another file.

### Just for information, if you got error because of the dependency you can run in Terminal : 
``` Terminal
Flutter Pub Get
```

## Different between Scoped and Ephemeral : 
- Scoped is very useful for application high complexity because, u can manage the state global better than Ephemeral can't manage the state.
- if Ephemeral need to send parameter or callback, Scoped don't need it because Scoped can access state global.
- Ephemeral is not recommended to use if we want to manage lots of data, but Scoped is better because can manage global data.

## Difference when dealing with user authentication, shopping carts, and other app-wide state needs 
Using App State Management can increase the application data management application. For example, in shopping carts, app state ensures consistent data accessibility between product and checkout pages, in user authentication, it maintains global login state and facilitates redirection between screens. Last in, app state management solutions like Provider, ScopedModel, and Bloc enable persistence and scalability, allowing features like theme changes, notification handling, and user settings.
