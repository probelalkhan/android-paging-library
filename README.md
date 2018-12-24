# Android Paging library Tutorial

In this app tutorial we will fetch data from stackOverflow API
using Retrofit and we will use paging library to load data 
gradually and gracefully within this app and display the results
with recyclerView 

 [Watch Video Tutorial](https://www.youtube.com/playlist?list=PLk7v1Z2rk4hjCQw1RVoYPRdeIzwdz5_Fi)

## Paging Library

The paging library is part of android architecture component

The Paging Library makes it easier for you to load data gradually and gracefully within your app's RecyclerView.

Many apps consume data from a data source that contains a large number of items, but only display a small portion at a time.

The Paging Library helps your app observe and display a reasonable subset of this data. This functionality has several advantages:

Data requests consume less network bandwidth and fewer system resources. Users who have metered or small data plans appreciate such data-conscious apps.
Even during data updates and refreshes, the app continues to respond quickly to user input.


[Documentation](https://developer.android.com/topic/libraries/architecture/paging/)

## Pre-Requisites
- Retrofit
- RecyclerView
- ViewModel

### Paging Library Key classes

- [Paging Adapter](https://github.com/probelalkhan/android-paging-library/blob/master/app/src/main/java/net/simplifiedcoding/androidpaginglibrary/ItemAdapter.java)
- [Data source](https://github.com/probelalkhan/android-paging-library/blob/master/app/src/main/java/net/simplifiedcoding/androidpaginglibrary/ItemDataSource.java)
- [Data source factory](https://github.com/probelalkhan/android-paging-library/blob/master/app/src/main/java/net/simplifiedcoding/androidpaginglibrary/ItemDataSourceFactory.java)
- [ViewModel](https://github.com/probelalkhan/android-paging-library/blob/master/app/src/main/java/net/simplifiedcoding/androidpaginglibrary/ItemViewModel.java)
