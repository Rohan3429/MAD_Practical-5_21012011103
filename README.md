# MAD_Practical-5_21012011103

Study: Intent, types of Intent, types of Intent Action, Intent.setData() method, Intent.setType() method, TextInputEditText, TextInputLayout, Button, ConstraintLayout, CoordinatorLayout, startActivity() method, ActivityResultContracts.StartActivityForResult() method, registerForActivityResult() method, Permission in manifest, ContextCompat.checkSelfPermission(), ActivityCompat.requestPermissions() method, Uri.parse() method,

ContactsContract.Contacts.CONTENT_TYPE

CallLog.Calls.CONTENT_TYPE

"image/*"

"tel:"

AIM: What is Intent? Write down types of Intent and types of Intent Action. Create an application which demonstrates implicit Intent for following features.

Make call to specific number

Open specific URL

Open Call Log

Open Gallery

Set Alarm

Open Camera

Ans:

An Intent is a messaging object used to request an action from another app component in Android. It is mostly used to start an activity, send a broadcast receiver, start services, and send messages between two activities1.

There are two types of Intents in Android:

Implicit Intent: Using implicit Intent, components can’t be specified. An action to be performed is declared by implicit intent. Then the Android operating system will filter out components that will respond to the action. For example, opening a webpage. The user does not name a specific component but declares a general action to perform

ex:When you tap the share button in any app you can see the Gmail, Bluetooth, and other sharing app options.

Explicit Intent: Explicit Intent specifies the component. In such a case, intent provides the external class to be invoked. For example, moving from one activity to another within your app. The user has a clear vision and knows exactly which activity can handle the requests

ex:Suppose you have two activities in your application: MainActivity and SecondActivity. You want to navigate from MainActivity to SecondActivity when a button is clicked.

Types of Intent Actions:

Browser Intent: Action: Open browser for search specific things.
Call Intent: Action: Initiate a phone call to John Smith's phone number.
Call Log Intent: Action: Retrieve and display the user's call log entries for the specified time period (in this case, today).
Gallery Intent: Action: Retrieve and display photos from the user's photo gallery that are tagged or identified as being from their vacation.
Camera Intent: Action: Activate the device's camera and prompt the user to capture a picture of the sunset.
Alarm Intent: Action: Schedule an alarm to trigger at 7:30 AM the next day.

![image](https://github.com/Rohan3429/MAD_Practical-5_21012011103/assets/98172369/5a73f4ae-5b95-4426-b6e4-42641e195bb3)
