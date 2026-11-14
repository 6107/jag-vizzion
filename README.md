# jag_vizzion

This project is an experiment to see how easy (or hard) it is to learn what
I have been able to do with OpenCV in python to be used in C++ and targeted
for a remote system (Raspberry Pi Compute Module 5 and others).  From
python, I learned some of the basics for simple AprilTag fundamentals.
This project is expected to go further and provide (in priority order).

 - Fast C++ 26 Support
 - Runs on Windows 11, Raspberry Pi 5 (compute module), and Raspberry Pi 2
 - Supports at least 2 cameras (all probably USB based)
 - Support import of an FRC Field (2D and 3D if available)
 - Basic Apriltag support for use in localization
 - Support Network Tables 4 (or other) for export to a robot and/or AdvantageScope

And the stretch Goals
 - Recognize field features (somewhat for localization)
 - Recognize game pieces (because we want something special during Autonomous Mode)
 - Recognize other stationary robots or obstacles (because we want to avoid running into them)
 - Provide dynamic path calculations to a 'location' on the field that avoids obstacles
 - Support obstacles that may be moving (other robots)
 - Support recognizing the alliance of a robot (friend or foe)
