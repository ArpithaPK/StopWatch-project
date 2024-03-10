# StopWatch-project
Stop watch project using vanilla javascript and bootstrap framework.

The HTML structure consists of a container div to hold the stopwatch display and buttons. Inside the container, there's a display area (#display) to show the stopwatch time and a button group (btn-group) containing start, stop, and reset buttons.

The CSS styles (inside the <style> tag) are used to customize the appearance of the stopwatch display and buttons.

In the JavaScript code:
        Variables timer, hours, minutes, and seconds are declared to manage the stopwatch functionality.
        The startTimer(), stopTimer(), updateTime(), reset(), and pad() functions control the start, stop, update, reset, and formatting operations of the stopwatch, respectively.
        The startTimer() function disables the start button, enables the stop button, and starts the timer.
        The stopTimer() function stops the timer and enables the start button while disabling the stop button.
        The updateTime() function increments the seconds and updates the display with the new time, with proper padding for single-digit numbers.
        The reset() function stops the timer, resets the time variables, updates the display, and enables the start button.
        The pad() function adds leading zeros to single-digit numbers for proper formatting.

The buttons (Start, Stop, and Reset) are assigned onclick event handlers (startTimer(), stopTimer(), and reset() respectively) to trigger the corresponding functions when clicked.
