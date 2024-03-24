# Lab #5: Random Pets 🐶🐱

Submitted by: **Brian Zhang**

Time spent: **2** hours spent in total

## Summary

**Random Pet Parade** is an Android app that displays random images of pets, specifically dogs and cats, fetched from external APIs. Users can tap a button to load a new random pet image, alternating between dog and cat pictures.

If I had to describe this project in three (3) emojis, they would be: **🐕🐈‍⬛🔮**

## Application Features

The following REQUIRED features are completed:

- [X] Make an API call to an API of your choice using AsyncHTTPClient
- [X] Display at least two (2) pieces of data for each API entry retrieved
- [X] A working Button requests a new API entry and updates the data displayed

## API Choice

My chosen API for this project is **https://dog.ceo/api/breeds/image/random** and **https://api.thecatapi.com/v1/images/search**.

## Video Demo

Here's a video / GIF that demos all of the app's implemented features:

<p align="center">
  <img src='https://imgur.com/EcGiHu7.gif' title='Video Demo' width='' alt='Video Demo' />
</p>

GIF created with **ScreenToGif**

<!-- Recommended tools:
- [Kap](https://getkap.co/) for macOS
- [ScreenToGif](https://www.screentogif.com/) for Windows
- [peek](https://github.com/phw/peek) for Linux. -->

## Notes

- **API Integration:** Utilizes external APIs (Dog CEO's Dog API and The Cat API) to fetch random pet images, demonstrating how to work with JSON data in Android.
- **Asynchronous Networking:** Implements AsyncHttpClient for making network requests, highlighting asynchronous programming techniques for non-blocking operations.
- **Image Loading:** Uses Glide for efficient image loading and display within the app, showcasing the use of third-party libraries for improved performance and user experience.
- **UI Interaction:** Features a user interface with a button that triggers the loading of new pet images, exemplifying basic UI element interactions in Android development.
- **Random Selection Logic:** Incorporates a simple random selection mechanism to alternate between dog and cat images, demonstrating basic logic implementation in app functionality.

## License

Copyright **2024** **Brian Zhang**

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
