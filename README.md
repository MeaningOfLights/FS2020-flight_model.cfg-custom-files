## FS2020-flight_model.cfg-custom-files


# Introduction

You can download icrosoft Flight Simulator 2020 aircraft as "Plane Add-Ons" and customise the characteristics and behaviour.


# How do I set this up?

You will need FS2020 and to download these Plane Add-ons:

https://flightsim-squadron.itch.io/flightsim-aircraft?download

Unzip the plane packages to **C:\Users\<YouUserName>\AppData\Local\Packages\Microsoft.FlightSimulator_8wekyb3d8bbwe\LocalCache\Packages\<edition>**, eg:

`C:\Users\<YouUserName>\AppData\Local\Packages\Microsoft.FlightSimulator_8wekyb3d8bbwe\LocalCache\Packages\Community\f22-raptor\SimObjects\Airplanes\f22`


# How do I use it?

Next download (or clone this repo) and use the **flight_model.cfg** files in this repo to overwrite your local ones. You can always revert back by unzipping the package again.


# How do I customise the files myself on-the-fly?

Here is how you can instantly see your flight model edits on the fly without restarting the whole sim:

It is as explained above but with some very important extra steps:

1. Before your game turn on developer mode (Options Generatal > Developer > On). You will need to make sure you see the "Developer Black Menu Bar" at the top of the Window.

2. Pause the sim and do your tweak in the **flight_model.cfg** file.

3. Go to top Developer mode (black) menu and click "new project". Press ok.

4. Again go to top Developer mode (black) menu and select aircraft menu and click "Aircraft editor".

5. Now press select the "aircraft" menu and then press "resync"

6. Un-pause the sim.

7. You do not need to "save" the project. It is open anyway. DO NOT MOVE ANYTHING until the aircraft is fully reloaded (or you might get a crash).

REF: https://www.avsim.com/forums/topic/585357-fs2020-modifying-flight-model-cfg-without-restarting-sim/?do=findComment&comment=4354597


# How do I contribute?

To participate please create new unqiue folder names per mod as there maybe multiple config's for the same plane, eg "river racing" settings through to "realistic pilot experience" settings. Please create branches for updates to the truck or for new folders with unique configs.


Submit a Pull Request and we'll merge if there's no conflicts! Thanks!

