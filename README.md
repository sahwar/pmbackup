# Pale Moon backup tool

This is the Pale Moon profile backup tool as available on the Pale Moon website:
http://www.palemoon.org/backuptool.shtml

## Included in this repository

This repository includes everything you need to build and modify the backup tool, with the exception of the RAB this was created in.

It also includes 2 third-party components for convenience. Please not that these components do not fall under the MIT license of this application:

- third party\7za.exe: stand-alone 7-zip archiver windows executable ©Igor Pavlov
used to provide compressed archives
- plugins\hpwUtility[nnn].zip: NeoBook plugin required by the application ©H.P.Wickern
(See the license file inside the zip for more details)
used to read/handle .ini files

## Building

To build this application:

- Install [NeoBook 5](http://neosoftware.com/nbw.html)
- Install the hpwUtility plugin (.nbp) inside NeoBook
- Load the .pub project file
- Check your path for embedded files to point to the correct path for 7za.exe
- Run or Compile from within NeoBook

Please note that a registered version of the RAB is required to make an application without a trial message.