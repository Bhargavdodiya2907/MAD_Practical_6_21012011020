# MAD_Practical_6_21012011020
AIM: What is Service? Write down types of Service. Create an MP3 player application by using service by following below instructions.
1.Create MainActivity and design according to shown in below image. 
2.Create Service Class and implement MediaPlayer Object
What is Service?
->A Service is not a separate process. The Service object itself does not imply it is running in its own process; unless otherwise specified, it runs in the same process as the application it is part of.
->A Service is not a thread. It is not a means itself to do work off of the main thread (to avoid Application Not Responding errors).
->Thus a Service itself is actually very simple, providing two main features:
->A facility for the application to tell the system about something it wants to be doing in the background (even when the user is not directly interacting with the application). This corresponds to calls to Context.startService(), which ask the system to schedule work for the service, to be run until the service or someone else explicitly stop it.
->A facility for an application to expose some of its functionality to other applications. This corresponds to calls to Context.bindService(), which allows a long-standing connection to be made to the service in order to interact with it.
->Types of Service:
->These are the three different types of services:
  (1)Foreground
  (2)Background
  (3)Bound
  Output:
  ![Screenshot 2023-10-01 112058](https://github.com/Bhargavdodiya2907/MAD_Practical_6_21012011020/assets/139693303/f2110853-ca50-476f-b027-5f593c583ef5)
