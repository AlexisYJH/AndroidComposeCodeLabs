# Migrating to Jetpack Compose

This folder contains the source code for the [Migrating to Jetpack Compose codelab](https://developer.android.com/codelabs/jetpack-compose-migration).

The codelab which migrates parts of [Sunflower](https://github.com/android/sunflower)'s Plant
details screen to Jetpack Compose is built in multiple GitHub branches:

* `main` is the codelab's starting point.
* `end` contains the solution to this codelab.

## Pre-requisites
* Experience with Kotlin syntax, including lambdas.
* Knowing the [basics of Compose](https://developer.android.com/codelabs/jetpack-compose-basics/).

## Getting Started
1. Install the latest Android Studio [canary](https://developer.android.com/studio/preview/).
2. Download the sample.
3. Import the sample into Android Studio.
4. Build and run the sample.

## Design
- ViewModel + LiveData + Room
- DataBinding;
- Navigation
- WorkManager：读取json文件数据存入数据库

- ViewPager2 + Fragment
- TabLayoutMediator：实现TabLayout与ViewPager2的绑定与滑动联动效果
- AppBarLayout(CollapsingToolbarLayout) + NestedScrollView +  FloatingActionButton
- RecyclerView + MaterialCardView
