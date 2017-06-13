# Rent-A-Dog
## Table of Contents
  * [App Design](#app-design)
    * [Objective](#objective)
    * [Audience](#audience)
    * [Experience](#experience)
  * [Technical](#technical)
    * [Screens](#Screens)
    * [External services](#external-services)
    * [Views, View Controllers, and other Classes](#Views-View-Controllers-and-other-Classes)
  * [MVP Milestones](#mvp-milestones)
    * [Week 1](#week-1)
    * [Week 2](#week-2)
    * [Week 3](#week-3)
    * [Week 4](#week-4)
    * [Week 5](#week-5)
    * [Week 6](#week-6)

---

### App Design

#### Objective
 
Allow users to search around their areas to allow them to rent dogs for specific amount of days. Users also have options to allow requirements for caring and what they can and can’t do with their dog, such as walking them outside or giving them showers.

#### Audience


The app is targeted for people who are animal lovers, but more specifically, lovers of dogs. The age group might range from kids to full grown adults who might need company. The income group will range to people who can afford at least $10 a day in rent expense to even more. We’re trying to be inclusive of everybody. Not everyone can buy a dog, but they could rent a dog to know how it feels like. The app can be used any time but pickup and drop off ranges are determined by the owner.

#### Experience
 
As a Rent-A-Dog user, I want to be able to quickly see pictures of dogs and rent them out for company. 
 
Apps with similar looks: AirBnb, Lyft, and Uber.

[Back to top ^](#)

---

### Technical

#### Screens
* [list the different screens used in the app]


Sign up and login screen
Main home screen 
List of dogs in a tableview
Map view of dogs 
Calendar view of rental period
Payment screen 
Profile page of user
Add dogs to the user profile to rent out
 
 

#### External services
* [list which APIs or external services will your app use?]
 
Firebase database to store user, dog, and rental data.

#### Views, View Controllers, and other Classes
* Views
Dog table view cell 
Map view
Calendar view 
Profile avatar image view
 
* View Controllers
Login VC
Main tab bar VC
Dog list VC
Map view VC
Scheduler VC
Payment VC
User Profile VC
Create Dog VC
Dog Profile VC
 
* Other Classes
Auth service manager
Firebase service manager 
Storage service manager
Payment service manager

#### Data models
* [list all Parse data models your app will need]
Dog class
Name
Breed 
Time availability 
Rental transaction
 
User class
Name 
Dogs available for rental
Dogs rented 
Rental transaction
 
Rental transaction
Dog
User (renter)
User (rentee)
Cost 
Time availability 
 
Map location class
Location: longitude, latitude  
Dog 
User 
 
 

[Back to top ^](#)

---

### MVP Milestones
[The overall milestones of first usable build, core features, and polish are just suggestions, plan to finish earlier if possible. The last 20% of work tends to take about as much time as the first 80% so do not slack off on your milestones!]
 


#### Week 1
_planing your app_
* Create the Auth and Sign up with FirebaseUI
* Add Container view controllers (tab bar embedded in nav)

#### Week 2
_finishing a usable build_
* Design and built User Profile header
* Add a table 

#### Week 3
* Populate the database with user and dog profiles.s

#### Week 4
* Create the UITableView of dogs nearby and allow user to request a dog walker.

#### Week 5
_starting the polish_
* Polish the app and add finishing touches

#### Week 6
_submitting to the App Store_
* Submit to the App Store and prepare for the pitch and demo

[Back to top ^](#)
 

