# AirBud
 
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


Sign up and login screen
Main home screen 
List of dogs in a tableview
Map view of dogs 
Calendar view of rental period
Payment screen 
Profile page of user
Add dogs to the user profile to rent out
 
 

#### External services
 
Firebase to store user, dog, and rental data. Facebook SDK to allow Facebook sign in through Firebase. AlamoFire (maybe?) for making network requests.

#### Views, View Controllers, and other Classes
* Views:
  * Dog table view cell 
  * Map view
  * Calendar view 
  * Profile avatar image view
 
* View Controllers:
  * Login VC
  * Main tab bar VC
  * Dog list VC
  * Map view VC
  * Scheduler VC
  * Payment VC
  * User Profile VC
  * Create Dog VC
  * Dog Profile VC
 
* Other Classes:
  * Auth service manager: to handle user authentication
  * Firebase service manager: to metadata on user, dog, and rental transaction data
  * Storage service manager: to store images of user and dog profile images
  * Payment service manager: to securely handle credit card transaction payments and to handle payments to dog owners

#### Data models
* Dog Class:
  * Name
  * Breed 
  * Time availability (start date, end date)
  * Rental transaction
 
* User Class:
  * Name 
  * isOwner?
  * Dogs available for rental
  * Dogs rented 
  * Rental transaction
 
* Rental Transaction Class:
  * Dog
  * User (owner)
  * User (renter)
  * Cost 
  * Time availability (start date, end date)
 
* Map location class
  * Location: longitude, latitude  
  * Dog 
  * User 

[Back to top ^](#)

---

### MVP Milestones

#### Week 1
_planing your app_
* Create the Auth and Sign up with FirebaseUI
* Add Container view controllers (tab bar embedded in nav)

#### Week 2
_finishing a usable build_
* Design and built User Profile header
* Add a tableView of [Dog] to the bottom portion of the user profile screen

#### Week 3
* Build add Dog screen and associate each Dog created with User in realtime db.
* Build schedule availability widget.
* Add Dog schedule-availability widget to add Dog screen.
#### Week 4
* Add User schedule-availability modal to home screen.
*Display modal on sign in and nav button edit schedule click
* Query all Users with schedule-available dogs in the area near you limited by distance
* Store all relevant Dogs in the tab bar controller

#### Week 5
_starting the polish_
*implement tableview and map view with relevant Dogs stored in tab bar controller.

#### Week 6
_submitting to the App Store_
* Polish (Unit testing, Flight)
* Submit to the App Store and prepare for the pitch and demo
 
![Flow Chart](http://i.imgur.com/OOMyiUY.jpg)

[Back to top ^](#)
