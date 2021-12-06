Allows openGL error detection using function instrumentation in GCC C++ compiler. Error checking happens
  1)after calling
  2)before exiting
functions.

Set -finstrument-functions and -rdynamic flags to enable.
  the -rdynamic flag allows displaying calling function names on the displayed callstack.
