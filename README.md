# Flutter-Cannot-run-with-sound-null-safety-because-dependencies-don-t-support-null-safety
--no-sound-null-safety 


First, you should read through the guide to understand unsound null safety.
If you are sure that you want to run your app with unsound null safety, you can use the following command:

flutter run --no-sound-null-safety

1. In Android Studio:

Run --> Edit Configurations --> Add Additional Run args --> add this and safe --no-sound-null-safety


2. If you are using VS Code

Then Goto

File => Preferences => Settings

Search for "Flutter run additional args"

then click Add Item

now type --no-sound-null-safety

click ok


3. IntelliJ IDE run args/configuration
To set this up in your IDE of choice, you can use:

In IntelliJ/Android Studio: "Edit Configurations" (in your run configurations) → "Additional run args".
