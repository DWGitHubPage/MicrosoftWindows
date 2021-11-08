## Windows Problem Step Recorder.

[Problem Step Recorder Step-by-Step Guide](https://social.technet.microsoft.com/wiki/contents/articles/51722.windows-problem-steps-recorder-psr-quick-and-easy-documenting-of-your-steps-and-procedures.aspx)


- Command-line syntax:

/start        Start Recording. (Outputpath flag SHOULD be specified)
/stop         Stop Recording.
/sc           Capture screenshots for recorded steps.
/maxsc        Maximum number of recent screen captures.
/maxlogsize   Maximum log file size (in MB) before wrapping occurs.
/gui          Display control GUI.
/arcetl       Include raw ETW file in archive output.
/arcxml       Include MHT file in archive output.
/recordpid    Record all actions associated with given PID.
/sketch       Sketch UI if no screenshot was saved.
/slides       Create slide show HTML pages.
/output       Store output of record session in given path.
/stopevent    Event to signal after output files are generated.
 
- PSR Usage Examples:
- 
psr.exe
psr.exe /start /output fullfilepath.zip /sc1 /gui 0 /record <PID>
 /stopevent <eventname> /arcetl 1
 
psr.exe /start /output fullfilepath.xml /gui 0 /recordpid <PID>
 /stopevent <eventname>
 
psr.exe /start /output fullfilepath.xml /gui 0 /sc 1 /maxsc <number>
 /maxlogsize <value> /stopevent <eventname>
psr.exe /start /output %temp%\%computername%_PSR.zip /sc 1 /gui 1 /arcetl 1 /arcxml 1 /sketch 1 /slides 1 

psr.exe /stop  
