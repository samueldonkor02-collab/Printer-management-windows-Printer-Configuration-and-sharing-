# Printer-management-windows-Printer-Configuration-and-sharing-
This section walks through configuring the “office canon” printer on Windows 11, setting it as default, scheduling it to only be available during work hours (08:00 to 17:00), and turning on network sharing so other users can print to it.

# Printer Management (Windows Printer Configuration and Sharing)

`Windows 11` `Printers & Scanners` `Printer Properties` `Network Sharing`

## Overview
This section covers configuring a shared local printer on a Windows 11 machine, including setting it as the default printer, scheduling its availability, and enabling network sharing so other users can print to it.

## Objective
Get comfortable with the printer configuration options in Windows, specifically setting availability windows and sharing settings, rather than leaving a printer wide open with default settings.

## Environment
* Machine: ASUS Vivobook laptop, Windows 11
* Printer: "office canon"

## What I Did

### Setting the Default Printer
Opened Settings, then Bluetooth & devices, then Printers & scanners, then office canon, and confirmed it was set as the default printer for the machine.

### Scheduling Printer Availability
Opened Printer Properties and went to the Advanced tab. Set the printer to only be available from 08:00 to 17:00 instead of always available, and left print jobs set to start printing immediately rather than waiting for the whole document to spool first.

### Enabling Network Sharing
Went to the Sharing tab in Printer Properties. Turned on Share this printer, set the share name to printer canon, and turned on Render print jobs on client computers so the work of rendering a print job happens on the client machine instead of the host.

## What's in This Section

```
screenshots/
01 printer advanced scheduling.png (Printer Properties, Advanced tab)
02 printer sharing settings.png (Printer Properties, Sharing tab)
```

## Skills I Picked Up
Scoping printer availability with scheduled hours instead of leaving a shared printer open at all times.
Understanding the difference between sharing a printer and just setting it as default.
Knowing what "render print jobs on client computers" actually controls.

## How This Applies in the Real World
This is a task a help desk or desktop support technician handles regularly, setting up a shared office printer so a team can use it, and making sure it is not available outside working hours for security and resource reasons.

## Limitations
This was configured on a single local machine rather than through a dedicated print server, which is how printer sharing is usually managed in a larger business environment.

## References
Windows Printer Sharing Documentation: https://support.microsoft.com/windows
Microsoft Print Management Overview: https://learn.microsoft.com/windows-server/administration/windows-commands/printer-management
