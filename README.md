# Original 

```sh
[burner@desktop format_perf]$ /usr/bin/time -v dub test --compiler=ldc --force
     Warning 
     Warning ## Warning for package format_perf ##
     Warning 
     Warning The following compiler flags have been specified in the package description
     Warning file. They are handled by DUB and direct use in packages is discouraged.
     Warning Alternatively, you can set the DFLAGS environment variable to pass custom flags
     Warning to the compiler, or use one of the suggestions below:
     Warning 
     Warning -d: Use the "buildRequirements" field to control deprecation behavior
     Warning 
             Generating test runner configuration 'format_perf-test-library' for 'library' (library).
    Starting Performing "unittest" build using ldc for x86_64.
    Building format_perf ~master: building configuration [format_perf-test-library]
     Linking format_perf-test-library
     Running format_perf-test-library 
6 modules passed unittests
	Command being timed: "dub test --compiler=ldc --force"
	User time (seconds): 27.10
	System time (seconds): 0.54
	Percent of CPU this job got: 99%
	Elapsed (wall clock) time (h:mm:ss or m:ss): 0:27.67
	Average shared text size (kbytes): 0
	Average unshared data size (kbytes): 0
	Average stack size (kbytes): 0
	Average total size (kbytes): 0
	Maximum resident set size (kbytes): 1861944
	Average resident set size (kbytes): 0
	Major (requiring I/O) page faults: 0
	Minor (reclaiming a frame) page faults: 414073
	Voluntary context switches: 58
	Involuntary context switches: 69
	Swaps: 0
	File system inputs: 0
	File system outputs: 40304
	Socket messages sent: 0
	Socket messages received: 0
	Signals delivered: 0
	Page size (bytes): 4096
	Exit status: 0
```
