The user enters the room and switches on his/her app through a button on the Pebble.
The app checks to see which other people have the same app and identifies them.
Then, when the Pebble makes a handshaking movement, it sends a signal to its app, and if at least one another identified app is within a certain radius and it also has these two conditions true, then the app sends data aka LinkedIn request to the closest app.

FEATURES:
Check to make sure the person is not already a LinkedIn contact.
Handle arbitration of request sending: who sends? Random?

COMPROMISE:
There are only two Android devices in the world.
Pair manually to Yusaira's phone using Bluetooth. Establish connection using app, and once connection is made, send a LinkedIn request.

KEEP IN MIND:
createInsecureRfcommSocketToServiceRecord() & listenUsingInsecureRfcommWithServiceRecord() for information transfer that doesn't need human approval

You can also just use WiFi, setup parallel server/client threads on each device, and send whatever you want.
http://stackoverflow.com/questions/6494006/how-to-send-and-receive-data-in-android-programming-using-bluetooth-without-pair
