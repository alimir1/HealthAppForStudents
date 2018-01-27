# Health App Beg
**Health App Beg** is an iOS app (for beginners) that receives health information from patients and displays result for doctor to see.

## Video Walkthrough

<img src='https://i.imgur.com/R8Lvwl6.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Before you begin

1. Create a new iOS project
2. Call it "Health App Beg"
3. Save the project
4. Download these [images](https://github.com/alimir1/HealthAppForStudents/tree/master/HealthAppImages) and save them to your assets folder on your XCode project.

## Required Features

**Overview:**
There will be two ViewControllers: HomeViewController & ResultViewController. HomeViewController will collect information from the user and ResultViewController will display the information that was collected on the HomeViewController.

### HomeViewController
<img src='https://i.imgur.com/vYh66Tc.png' title='Video Walkthrough' width='' alt='Video Walkthrough' />

* 4 UIButtons with images of: Happy, Sad, Surprised, and Angry
* UISegmentedControl for gender
* 3 UITextFields: full name, height, and weight
* UIDatePicker for date of birth (remember to set 'mode' to 'Date' on the attribute inspector)
* UIButton at the very bottom that takes users to the ResultViewController -- do this VISUALLY.

### ResultViewController
<img src='https://i.imgur.com/Vr69Ge6.png' title='Video Walkthrough' width='' alt='Video Walkthrough' />
* Labels that display information for the user's: mood, gender, full name, height, weight, and date of birth

## Hints

### Saving Mood
<img src='https://i.imgur.com/qiufNvP.png' title='Video Walkthrough' width='' alt='Video Walkthrough' />

### Set image programatically**
<img src='http://i.imgur.com/NkWHpFi.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

### Working with UISegmentedControl
if segmentedControl.selectedSegmentIndex == 0, do something...

### Dismiss Keyboard
<img src='https://i.imgur.com/nGd0HJ4.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

### Formatting Date Object
let dateFormatter = DateFormatter()
dateFormatter.dateFormat = "MM/dd/yyyy"
let dateString = dateFormatter.string(from: DATE OBJECT GOES HERE) <---- THIS IS YOUR STRING
