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
[explain the goal of the app]
 
Allow users to search around their areas to allow them to rent dogs for specific amount of days. Users also have options to allow requirements for caring and what they can and can’t do with their dog, such as walking them outside or giving them showers.

#### Audience
[who is this app targeting?]
 
The app is targeted for people who are animal lovers, but more specifically, lovers of dogs. The age group might range from kids to full grown adults who might need company. The income group will range to people who can afford at least $10 a day in rent expense to even more. We’re trying to be inclusive of everybody. Not everyone can buy a dog, but they could rent a dog to know how it feels like. The app can be used any time but pickup and drop off ranges are determined by the owner.

#### Experience
[how will your users interact with this app?]
 
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
1. Login VC
2. Main tab bar VC
3. Dog list VC
4. Map view VC
5. Scheduler VC
6. Payment VC
7. User Profile VC
8. Create Dog VC
9. Dog Profile VC
 
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
 
User class
Name 
Dogs available for rental
Dogs rented 
Rental 
 
Rental transaction
 
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
* Add Container view controllers (tab bar embeded in nav

#### Week 2
_finishing a usable build_
* User profile and let user to edit the profile and create doggy profiles 

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
 

 
