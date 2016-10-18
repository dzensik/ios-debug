# ios-debug

Here is the list of some useful information about the debugging of the iOS Apps

* [The LLDB Debugger Commands](http://lldb.llvm.org/lldb-gdb.html)
* libimobiledevice. A very handy command line tool to connect to  iOS devices to read the device info or output the device log directly to console.
`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null`
`brew install libimobiledevice`
* App Transport Security (ATS) diagnosing tool for command line: `/usr/bin/nscurl --ats-diagnostics https://www.example.com`
* CFNetwork diagnostic logging. [From Apple docs](https://developer.apple.com/library/content/qa/qa1887/_index.html): When you enable this feature CFNetwork will log a lot of useful information about its progress to a file, which you can then examine to help debug any networking problems you encounter. This feature is supported on both iOS and OS X. Example: `setenv("CFNETWORK_DIAGNOSTICS", "3", 1)`