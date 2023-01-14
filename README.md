# WEB102 Prework - *Sea Monster Crowdfunding Site*

Submitted by: **Abenezer Amanuel**

**Loch Funding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **8** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='subGIF.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with [ScreenToGif](https://www.screentogif.com/).   
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

The process of building this app was highly educational and informative. Several web development concepts were implemented to make the site both aesthetically pleasing and, more improtantly, structurally functional. 

DOM manipulation was one such concept used extensively. Though challenging at first, the document-object model proved to be very rewarding in implementing features such as creating template HTML elements for containers that are visible on screen, populating these newly created elements with inner HTML elements, and displaying useful stats such as number of contributions and total funding raised.

Furthermore, there were challenges with the JSON object model. Particularly, the import of a JSON object from a different file and its subsequent transformation to a list was hard to wrap my head around. However, by drawing parallels with concepts of objects from other OOP languages such as Java, it was soon understood just how simple it can be to store and access specific information about each game from the JSON list of games.

The reduce() and filter() methods brought in a new syntax of writing functions in arrow functions, which admittedly took some time to get used to. However, once understood, these functions beatifully tied up the concepts from JSON and vanilla JavaScript to enable functionalities such as filtering and displaying funding stats.

## License

    Copyright 2023 Abenezer Amanuel

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
