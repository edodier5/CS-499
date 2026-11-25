# SNHU CS-499
Computer Science Capstone Course Completed By Evan Dodier.

## Project Description
Description of project goals, objectives, and relevance of enhancements made.

### Artifact One - Software Engineering and Design
##### Inventory Android Mobile Application - CS-360 Mobile Architecture and Programming // May, 2026
The artifact chosen for the software design and engineering category was an Android mobile application developed using Java. It was originally created during the CS-360 Mobile Architecture and Programming course. During the course we were given multiple options for the type of application we were developing, such as an inventory or event tracking application. However, each still needed to meet similar requirements like utilizing a SQLite database with at least two tables, a login screen, a screen to view a grid of database entries, methods to perform CRUD operations, and a notification system. Part of our task was to design and implement a user interface that supported these. Since I had chosen to create an inventory application, I was required to create a page to view items of an inventory within a grid. At the time I had also decided to expand the Applications UI to include multiple other screens. For instance. I created the inventory fragment as well as an events fragment and a profile fragment which were all housed inside of the main activity of the application. Combining this with additional tables created in the database, I was able to display notifications in a recycler view on the events fragment and allow a user to choose between different inventories on the profile fragments recycler view. 


#### Enhancement
Description.

### Enhancement Artifact Two - Algorithms and Data Structures
##### Vector Sorting Assignment - CS-300 DSA Analysis and Design // July, 2025
The artifact chosen for the algorithms and data structures category was a vector sorting program developed using C++. It was originally created from a pseudocode outline provided in the CS-300 Data Structures and Algorithms: Analysis and Design course. The intention of the assignment was to compare and contrast different sorting algorithms, including quicksort and selection sort, while using a vector to hold a large dataset of bid objects read from a CSV file. Beyond the code of the assignment, we wrote a reflection about the process that evaluated the efficiency of each algorithm both through their time complexities and observed execution times in our experience. In my reflection, I had explained that the two algorithms have equivalent worst-case complexities, O(n^2), due to pivot selection creating unequal groups during a quicksort. However, when quicksort utilizes balanced or more equal groups it has an average case time complexity of O(nlogn) while selection sort does not improve. As datasets grow larger, this difference in time complexity grows more apparent between the two algorithms and was reflected by our experience timing the sorts.
Including this vector sorting assignment as an artifact in my portfolio was intended to show my ability to design and evaluate computing solutions that solve a given problem using algorithmic principles and standards appropriate to its solution, while managing the trade-offs involved in design choices. Since the other enhancements I designed for my portfolio utilized the same inventory application project, I had Identified an opportunity to both solve a real problem of the inventory display system and apply my knowledge of algorithms gained from the vector sorting assignment. The inventory application was developed for a mobile device and features different lists of data being displayed to the user. For example, there is an events page that features a list of inventory events in a recyclerView, an inventory page that displays a grid view of items, an inventory users list, a friends list, and a profile page including a recyclerView of inventories. While some contain relatively few elements, others of these presentations detract from the user experience because of the need to scroll through a large list on the small device screen. Offering users a feature to reconfigure lists by specific sort criteria in ascending or descending order would improve navigation. Two particular examples are the events page and inventory page, which fill up fairly quickly with events and items respectively. I believe that the algorithmic solution demonstrated in the vector sorting assignment is suited to building this functionality. 

#### Enhancement
While completing this enhancement, I ported or translated the code design from C++ into Java. Within the inventory application, it is contained in the Quicksort class under the tools package. To make further enhancement upon the translation of the code into Java, I aimed to make my new implementation more modular and flexible. The original vector sorting assignment was only able to sort by the title of each object in the vector. In the enhancement, I wrote the class using Java generics which allow the quicksort method to be called using different data models of the application, for instance the InventoryModel, ItemModel, or EventModel. Another limitation of the vector sorting assignment was only including the functionality of one comparison method. By utilizing the Java comparator interface, the method of comparison could be defined as the quicksort method is called. This allows the method to be modular and reused on different data types of the inventory applications data models. 

### Enhancement Artifact Three - Databases
##### Inventory Android Mobile Application - CS-360 Mobile Architecture and Programming // 
Description.


#### Enhancement
Description.

## Code Review
Description.
<iframe width="560" height="315" src="https://www.youtube.com/embed/rD0sw-YqvbI?si=LgQH0BvFM5lnUG8Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Assessment of Project
Description.

## Version History

* 0.1
    * Initial Repo and Github Pages setup
* 0.2
    * Upload and Include Code Review on page
* 0.3
    * Add Artifact Descriptions and Enhancement plans
* 0.4
    * Assess Enhancements of The Project

## Author
Evan Dodier - [GitHub](https://github.com/edodier5), [LinkedIn](https://www.linkedin.com/in/evandodier) 
