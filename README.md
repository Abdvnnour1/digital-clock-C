# digital-clock-C

A digital clock that runs in the terminal, written in C. One of my first projects as a 2nd year IT student.

## Features
- Displays the current time (HH:MM:SS), updated every second
- Clears the screen each tick so the time updates in place

## How to run
```bash
gcc clock.c -o clock
./clock
```
Press `Ctrl+C` to stop.

## Tested on
- Windows, clion with MinGW

## What I learned
- Using `time.h` to get the system time
- Infinite loops with `while (1)`
- Output buffering with `fflush(stdout)`

## Possible improvements
- 12/24-hour toggle
- Date display
- Colors
