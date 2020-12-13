## FS2020-flight_model.cfg-custom-files


# Introduction

You can download Microsoft Flight Simulator 2020 aircraft as "Plane Add-Ons" and customise the characteristics.


# How do I set this up?

You will need FS2020 installed and these Plane Add-ons downloaded:

https://flightsim-squadron.itch.io/flightsim-aircraft?download

Unzip the plane packages to **C:\Users\<YouUserName>\AppData\Local\Packages\Microsoft.FlightSimulator_8wekyb3d8bbwe\LocalCache\Packages\<edition>**, eg:

`C:\Users\<YouUserName>\AppData\Local\Packages\Microsoft.FlightSimulator_8wekyb3d8bbwe\LocalCache\Packages\Community\f22-raptor\SimObjects\Airplanes\f22`

Restart FS2020 and the Planes will be available to fly!

You can get the Star Wars Add-Ons from here: https://eggman28.itch.io/flight-sim-star-wars-ships


# How do I use it?

Next download (or clone) this repo and use the **flight_model.cfg** files to overwrite your local ones. You can always revert back by unzipping the packages again.


# How do I customise the files myself "on-the-fly"?

Here is how you can instantly see your flight model edits on the fly without restarting the whole sim:

1. Before your game turn on developer mode (Options Generatal > Developer > On). You will need to make sure you see the "Developer Black Menu Bar" at the top of the Window.

2. Pause the sim and do your tweak in the **flight_model.cfg** file.

3. Go to top Developer mode (black) menu and click "new project". Press ok.

4. Again go to top Developer mode (black) menu and select aircraft menu and click "Aircraft editor".

5. Now press select the "aircraft" menu and then press "resync".

6. Un-pause the sim.

7. You do not need to "save" the project. It is open anyway. DO NOT MOVE ANYTHING until the aircraft is fully reloaded (or you might get a crash).

REF: https://www.avsim.com/forums/topic/585357-fs2020-modifying-flight-model-cfg-without-restarting-sim/?do=findComment&comment=4354597


# How do I contribute?

To participate please create new unqiue folder names per mod as there maybe multiple config's for the same plane, eg "river racing" settings through to "realistic pilot experience" settings. 

Please create branches for updates to the trunk or for unique configs to add-on planes simply add the config file to a directory with a suffix and version, eg f22_TopGun_V1.


Please submit a Pull Request and we'll merge if there's no conflicts! Thanks!


# History 
2020-12-13
- Initial upload for the Raptor F22 orig and mod for the TopGun versions - including weight, yaw and lift, TO DO need to tweak roll settings for Top Gun style.

- Initial upload for the F16 and starwars-x-wing and TopGun versions with reduced the weight.




