# AutoCheck
This App consumes a dynamic API to display cars available for sale to clients.

Technologies used:  Retrofit, Nav Graph, GsonConverter, RecyclerView,  Repository, ViewModels, MVVM Architectiure Pattern.

Retrofit was used to make calls to the backend and fetch data. 

The Repository fetches the data from the remote server with the help of the retrofit and sends the data to the viewmodel, which is being observed by the UI and ready to display.


The Recyclerview is populated with data gotten from the Viewmodel and then displayed on the screen.
