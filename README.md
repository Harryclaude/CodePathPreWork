# CodePathPreWork
# Pre-work - *ToDo App*

**TodoApp** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Harry Claude DELICE**

Time spent: **40** hours spent in total

## User Stories

The following **required** functionality is completed:

* [X] User can **successfully add and remove items** from the todo list
* [X] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [X] User can **persist todo items** and retrieve them properly on app restart

The following **optional** features are implemented:

* [ ] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [ ] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [ ] Add support for completion due dates for todo items (and display within listview item)
* [ ] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [ ] Add support for selecting the priority of each todo item (and display in listview item)
* [ ] Tweak the style improving the UI / UX, play with colors, images or backgrounds

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** [So far, I really like Android app development and I am really enthusistic to deepen my skills in Android app development. What is really interesting is that I have already build some skills in Java in the context of my Java Class at CTPEA. Since I have taken that class, I could not wait to go deeper. And this prework gets me confident that I will be able to make a lot of things in the Android development which is based Java. And also, I will learn so much during this 8-intensive weeks. Before experiencing Android development, I have made a little Web Development using HTML, CSS, JavaScript, And the fact that Android use layouts to create interface facilitates a lot our task as developer, it's quite simple and beyond all, it gives an interesting User interface.].

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:** [I would say that an ArrayAdapter is a bridge to take datas from a data source (The ArrayList) and to add it to the List View which is the visual representation of these datas. The convertView is one of the parameter of the GetView method that indicates the old view to reuse].

## Notes

Describe any challenges encountered while building the app.
	I did not really meet challenge while buiilding the app because all the steps was described in the slides. Although, my main problem was to set up Android Studio, especially because of the gradle. When creating a project, despite the long time spent waiting for the gradle to build, many times, when starting the project, the gradle was not synced with the App. I tried several times, made ressearch to face this obstacle and at the end, I overcomed it. 

## License

    Copyright [2018] [Hary Claude DELICE]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
