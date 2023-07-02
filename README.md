# filter-log-tools

filter-log is flexible, minimalistic event-bus style logging

These tools make it easier to process the log entries

## Log Post-processing

The pattern with JSON based logging is to save a gross amount of data and filter that down to what you want to see. Filter Log contains a command line utility `filter-log` which can do some basic filtering and formatting. You can check out its man page for exact capabilities. Basic usage is:

```
filter-log -h
```
or

```
cat my-log.json | filter-log > my-log.txt
```

Anything complicated though, and it may be much easier to write your own tiny program to process the entries. `exmaples/process-1.js` is a simple example. The source for `filter-log-command.js` may also serve as an example.





