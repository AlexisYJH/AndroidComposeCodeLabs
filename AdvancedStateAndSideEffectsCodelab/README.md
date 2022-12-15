# Advanced State in Jetpack Compose Codelab

This folder contains the source code for the
[Advanced State in Jetpack Compose Codelab](https://developer.android.com/codelabs/jetpack-compose-advanced-state-side-effects)
codelab.

The project is built in multiple git branches:
* `main` – the starter code for this project, you will make changes to this to complete the codelab
* `end` – contains the solution to this codelab

## [Optional] Google Maps SDK setup

Seeing the city on the MapView is not necessary to complete the codelab. However, if you want
to get the MapView to render on the screen, you need to get an API key as
the [documentation says](https://developers.google.com/maps/documentation/android-sdk/get-api-key),
and include it in the `local.properties` file as follows:

```
google.maps.key={insert_your_api_key_here}
```

When restricting the Key to Android apps, use `androidx.compose.samples.crane` as package name, and
`A0:BD:B3:B6:F0:C4:BE:90:C6:9D:5F:4C:1D:F0:90:80:7F:D7:FE:1F` as SHA-1 certificate fingerprint.

## Design
- Compose: State & SideEffects
- Hilt
- Coil
- Google Map
- ViewModel + StateFlow

## State
- remember >> CraneHomeContent
- MutableState >> CraneHomeContent
- rememberSaveable >> MapViewContainer

## SideEffects
- LaunchedEffect >> MapViewContainer
- rememberCoroutineScope >> CraneHome
- rememberUpdatedState >> ToDestinationUserInput
- DisposableEffect >> rememberMapViewWithLifecycle
- SideEffect
- produceState >> DetailsScreen
- derivedStateOf >> ExploreSection
- snapshotFlow