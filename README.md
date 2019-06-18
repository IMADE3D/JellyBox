| ⚠️ Warning: GitHub Mangles Zip Export ⚠️|
| --- |
|Do not download the project as a .zip if you want to use the 3mf Cura Project files. Github mangles the files and they will not work. Download the individual 3mf files from their pages or use git clone instead.|

# JellyBOX Files

Here you can find the JellyBox 3D Printer source files so you can **print spare parts**, or **modify the printer to your liking**!

## GCODE
- this is what you want it you want a **fast and easy spare part**
- **pre-sliced files ready to print** on your JellyBOX
- both cold and heated bed are fine
- depending on the filament and ambient temperature, heated bed is beneficial for some parts
- these are the gcodes we use for production
- well, we usually plate the parts many time (to print 16 clips at a time for example), but it's _equivalent gcode_

## STL
- STL files are the most common 3D exchange file
- pro: any slicer can process stl files
- con: stls are difficult to modify precisely - if you need to be changing the files, get STEP, IGES, or something like that...

## RLD
- rld files are used for laser cutting
- these are ready-to-lasercut

## State of the Art
- Update 2017-02-07
  - Several STLs and corresponding GCODEs have been updated. Left fan mount is re-inforced, feeder yoke and arm are smoother than ever, and there is a new mount for the flat proximity sensor without righ fan. Good things all around :cake: .
- Update 2016-11-21
  - GCODE, STL, RLD all published. The only parts missing are wire forms and native 3D files (step). We're working on it :-)
- Update 2016-10-01
  - JellyBox 1.3 is still in the stage of cleaning up the files. That's why you only find STLs here in the moment. Similarly, wire documentation is looking good, but it's not ready for public consumption. No worries; it's coming.


## License

  These files are licensed under *Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA 4.0)*. Read below and see “license.txt” more more information.

### Q: So is JellyBox open-source?
#### Contextual answer:
Yes!

We deeply and sincerely LOVE REMIX culture. We believe ideas are born out of other ideas, and being able to build on other people's projects is path to innovation. Similarly, we LOVE HACKING or, more specifically, making things do what we want the to do and modify them to suit our needs. Also, we LOVE REPAIRING our own devices.

Plus, we don't like to lock people into some sort of Orwellian proprietary system. After all, we are all children of RepRap. For all these reasons, we publish not only our production files (3D: stl and gcode, 2D: rld), but also source files that are way way easier to modify (3D: step).  We want you to play with the design! Make it better! See how it's done.


#### License specific answer:
CC BY-NC-SA 4.0 - now

We do love the remix culture, however, we do this for a living, and research and development of hardware AND of the build experience is incredibly arduous, resource intensive, and plainly expensive. We are building a network of licensed trainers and licensed manufacturers (Franchisees - interested? We strike good deals. Shoot us a message.), and we need to be able to guarantee our partners a competitive advantage at the beginning.

Thus, we publish the files under Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA 4.0) license. This allows anyone to print spare part to fix their printer, remix the parts, hack the heck out of it, even build a whole new project on top. Yet, this is not strictly Open-Source as the Open Source Hardware Association would tell you, but it is a common practice, it's within RepRap guidelines, and most people in fact do consider this open source. Even the original versions of GNU allowed non-commercial clause!
