# PubNub 3.4 Web Data Push Cloud-Hosted API - C# Mono 2.10.9 
##PubNub C Sharp (MonoForAndroid Usage)

You can checkout the video overview here: https://vimeo.com/56720927

Open 3.4/PubNub-Messaging/Pubnub_Messaging/PubNub_Messaging.csproj. 
Run the project in the emulator to see a working example. The main functionality lies in the pubnub.cs file.

3.4/PubNub-Messaging/Andr.Unit contains the Unit test cases. Run the project to see the unit test results,

Please ensure that in order to run on Mono the constant in the pubnub.cs file should be set to "true"
overrideTcpKeepAlive = true;

When creating a new project or a new configuration please add a compiler flag by going into the "Options -> Compiler -> Define Symbols" and adding "MONODROID;" to it.

Dev environment setup:
- MAC OS X 10.7.4 (Lion)
- MonoTouch 4.41 Evaluation
- Mono Develop 3.0.5
- Mono 2.10.9 

Report an issue, or email us at support if there are any additional questions or comments.


