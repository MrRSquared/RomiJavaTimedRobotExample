# RomiJavaTimedRobotExample
This is a sample project for running a basic timed robot project for WPILib.

Most of the magic happens in [Robot.java](src/main/Java/frc/robot/Robot.java). 
The project could be entirely self-contained there, however, since the template used a seperate [Drivetrain](src/main/Java/frc/robot/RomiDrivetrain.java) class, we decided to utilize it as well.

There are a few methods in there (mostly for using the encoders) that we did not utilize quite yet.

Also, we did not remove the auto sendable chooser, because it could be useful in the future.
