# Pomodoro-Timer-Project

The Pomodoro technique is a time management method developed by Francesco Cirillo in the late 1980s.
The technique uses a timer to break down work into intervals, traditionally 25 minutes in length, separated by short breaks. Each interval is known as a pomodoro, from the Italian word for tomato, after the tomato-shaped kitchen timer that Cirillo used as a university student.

This application allows the user to:

- Set the focus duration (default to 25 minutes, no less than 5, no more than 60)
- Set the break duration (default to 5 minutes, no less than 1, no more than 15)
- When the focus time expires, an alarm plays and then the break timer starts.
- When the break time expires, an alarm plays and then the focus timer starts.

This was developed as an assignment for the Thinkful.com software engineering course. It was developed using React.js, Bootstrap 4 for styling, and Open-iconic icons for icons.

The initial screen lets the user set the length of the focus and break sessions:

![Initial Screen](https://res.cloudinary.com/strive/image/upload/w_1000,h_1000,c_limit/06ddc6bb0f6b5add9db441447000e59c-o-initial-screen.png)

After the user clicks the Play button, the buttons to change the focus and break duration are disabled, and the session timer appears.

![Active Session Screen](https://res.cloudinary.com/strive/image/upload/w_1000,h_1000,c_limit/517bceae35a5acf63fb3d20cb04733cf-ro-active-sesson.png)

The session timer shows the type of session, either "Focusing" or "On Break", the total duration of the session, the time remaining, and a progress bar showing how much of the session is complete.

If the user clicks the Pause button, "paused" appears below the time remaining.

![Paused Session Screen](https://res.cloudinary.com/strive/image/upload/w_1000,h_1000,c_limit/e179e707512486a110fbdb155a7897b4-o-paused-session.png)

Stopping a session returns the application to the initial screen and the user is able to change the focus and break duration.

## About Me

* [LinkedIn Profile](https://www.linkedin.com/in/david-arvidson/)
* [GitHub Profile](https://github.com/DavidxArvidson)

## Special Thanks

Special thanks to Thinkful for the excellent training I received and my mentor Stephen Hall.
