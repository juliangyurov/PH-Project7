## [Project 7: Whitehouse Petitions](https://www.hackingwithswift.com/read/7/overview)
Written by [Paul Hudson](https://www.hackingwithswift.com/about)  ![twitter16](https://github.com/juliangyurov/PH-Project6a/assets/13259596/445c8ea0-65c4-4dba-8e1f-3f2750f0ef51)
  [@twostraws](https://twitter.com/twostraws)

**Description:** Make an app to parse Whitehouse petitions using JSON and a tab bar.

- Setting up

- Creating the basic UI: UITabBarController

- Parsing JSON using the Codable protocol

- Rendering a petition: loadHTMLString

- Finishing touches: didFinishLaunchingWithOptions

- Wrap up

[Review what you learned ](https://www.hackingwithswift.com/review/hws/project-7-whitehouse-petitions)

**Challenge**

1. Add a Credits button to the top-right corner using UIBarButtonItem. When this is tapped, show an alert telling users the data comes from the We The People API of the Whitehouse.
   
2. Let users filter the petitions they see. This involves creating a second array of filtered items that contains only petitions matching a string the user entered. Use a UIAlertController with a text 
field to let them enter that string. This is a tough one, so I’ve included some hints below if you get stuck.

3. Experiment with the HTML – this isn’t a HTML or CSS tutorial, but you can find lots of resources online to give you enough knowledge to tinker with the layout a little.
