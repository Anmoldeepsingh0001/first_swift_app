# first_swift_app
Download latest version 12.5 from app store of xcode
Three options will be there and select second option

Then select single view app option
It's important to name the Product while initiating the progarm
we have two language i.e swift and objective c
After that we can also upload our work on github
In identity option put dislay name e.g "Myfirstapp"

Once we have installed the application the GUI we see is as follows and processing time may be impactful based on the system.

![WhatsApp Image 2021-02-03 at 9 49 40 AM](https://user-images.githubusercontent.com/75639402/106835519-76745e80-6665-11eb-94ec-6b7b02d8ea36.jpeg)
In the right side we have "option launchscreen board" or Splash screen. its our first acitivity that shows when we start building application.
In the toolbar we have options like hierarchy,debugging,run,breakpoints etc.



Assests = resources in the android studio.
AppDelegate.swift is a application life cycle like in android Activiry life cycle.
we have label,buttons,scrollbar etc in the toolkit. By drag and drop on the controller screen we can use that.
In the xcode we have different type of coustom text styles like bold,italic.

Decalare variable e.g 

This is how the app looks while work on it. We have plenty of editing options on both sides of our workspace. However, the application we chose to build here is to change the text view upon click. Since we are writing a swift code we do not have extends and other keywords that were used in android studios, instead we have ":" symbols and many more that supports swift language.

![WhatsApp Image 2021-02-03 at 9 48 42 AM](https://user-images.githubusercontent.com/75639402/106776165-d0e3cf80-6611-11eb-9586-a495496ff4bf.jpeg)

Meanings
@IBOutlet is a way of connecting code to storyboard layouts
@IBAction is a way of making storyboard layouts trigger code. This method takes one parameter, called sender

![WhatsApp Image 2021-02-03 at 10 16 46 AM](https://user-images.githubusercontent.com/75639402/106839283-e4bc1f80-666b-11eb-8141-f837b41c9930.jpeg)

In the above example we can clearly see that we have plenty of design options. However, we have used a label, that says "Hello Cegep" and also used a button "Change the Text".
We have these options of adding labels and buttons under the view controller. We have all the styling tools on the right side of the screen where we can change the attributes of the buttons as well as the labels.

This is the output of our program. When we click on the button change the text, the message "Hello cegep" will change to "Hello Gaspe...".


![WhatsApp Image 2021-02-03 at 10 16 47 AM](https://user-images.githubusercontent.com/74370312/106837207-6c079400-6668-11eb-9c8c-5238abc7a8bd.jpeg)


_*Code highlights*_
@IbOutlet var lblhello :UILabel
@IbAtion  func sayHello(sender:Any){
lblHello.text="hello Gaspe..."

Here is the screenshot for reference of different sizes and models available for the emulators in iOS:
![WhatsApp Image 2021-02-03 at 10 17 10 AM](https://user-images.githubusercontent.com/74370241/106775856-855d1000-6669-11eb-8a25-5084027362f2.jpeg)




