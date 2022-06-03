# Project 1 - Flixster

Flixster shows the latest movies currently playing in theaters. The app utilizes the Movie Database API to display images and basic information about these movies to the user.

Time spent: 10 hours spent in total

## User Stories

The following **required** functionality is completed:

* [Y] User can **scroll through current movies** from the Movie Database API
* [Y] Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
* [Y] For each movie displayed, user can see the following details:
  * [Y] Title, Poster Image, Overview (Portrait mode)
  * [Y] Title, Backdrop Image, Overview (Landscape mode)
* [Y] Allow user to view details of the movie including ratings within a separate activity

The following **stretch** features are implemented:

* [Y] Improved the user interface by experimenting with styling and coloring.
*       Justified title on detail view, Changed portrait image to backdrop image on detailed view for better fitting, and a cream background
* [Y] Apply rounded corners for the poster or background images using [Glide transformations](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#transformations)
* [N] Apply the popular [View Binding annotation library](http://guides.codepath.org/android/Reducing-View-Boilerplate-with-ViewBinding) to reduce boilerplate code.
* [N] Allow video trailers to be played in full-screen using the YouTubePlayerView from the details screen.

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='[https://imgur.com/a/jTACkRV](https://imgur.com/a/jTACkRV)' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with ![proj1 copy](https://user-images.githubusercontent.com/96102973/171967655-e6ec627f-eb8e-4bb4-bc26-df2e8ecea85b.gif)
[Kap](https://getkap.co/).

## Notes

I accidently skipped a step in the instructions and thought that caused a mistake whose source I couldnt ubicate for 30 minutes.
After hidding the api key some issues were encountered while trying to concatenate it to the url. This was fixed by moving it down after a couple of declarations

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2022] [Alejandro Malla]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
