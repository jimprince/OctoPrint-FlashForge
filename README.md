# OctoPrint-FlashForge

Support communication with closed source FlashForge printers such as Finder, Dreamer and rebranded printers such as the PowerSpec Ultra, Dremel Idea Builder.

Based on work by [Noneus](https://github.com/Noneus)

## Setup

Install via the bundled [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager)
or manually using this URL:

    https://github.com/Mrnt/OctoPrint-FlashForge/archive/master.zip

Plugin requires the libusb1 library:
https://pypi.org/project/libusb1/

## Configuration

### Settings

Under OctoPrint > Settings > Serial Connection > Intervals & Timeouts:
Change all settings under "Query Intervals" to 1s.

Under OctoPrint > Settings > Serial Connection > Firmware & Protocol:
Disable "Enable automatic firmware detection"
Change "Send a checksum with the command" to "Never"

Under OctoPrint > Settings > Printer Profiles:
Edit the default printer profile or create a new to reflect the number of extruders, build volume, etc.

### Connection

Under the main interface select "Auto" for "Serial Port".
