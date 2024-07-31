# libprogressbar
[WIP]
A C++ library for a thead safe, non blocking, flexible and customizable progressbar for your C++ applications.

## Features
1. Application can set a custom progress logic 
2. Application can set a custom display logic
3. is thread safe. A thread should just do:
    - progress.update() // sets the current progress in a thread safe way
4. is async (i.e non blocking in a background thread till program finishes)
    - progress.display() // progress bar is displayed by the background thread
5. Should be configurable 
