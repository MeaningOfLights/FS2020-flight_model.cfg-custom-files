## FS2020 custom flight_model aircraft (cfg-files)


# Introduction

You can download Microsoft Flight Simulator 2020 **Plane Add-Ons** and customise the aircraft characteristics.

![River Racing an F22-Raptor behind-Airport-VKPQ - Caro](https://github.com/MeaningOfLights/FS2020-flight_model.cfg-custom-files/blob/main/media/behind-Airport-VKPQ.png)


# How do I set this up?

You will need FS2020 installed and these plane add-ons downloaded:

https://flightsim-squadron.itch.io/flightsim-aircraft?download

Unzip the plane add-on packages to **C:\Users\YouUserName\AppData\Local\Packages\Microsoft.FlightSimulator_8wekyb3d8bbwe\LocalCache\Packages\<edition>**, eg:

`C:\Users\<YouUserName>\AppData\Local\Packages\Microsoft.FlightSimulator_8wekyb3d8bbwe\LocalCache\Packages\Community\f22-raptor\SimObjects\Airplanes\f22`

Restart FS2020 and the plane add-ons will be available to fly!

You can get the Star Wars add-ons from here: https://eggman28.itch.io/flight-sim-star-wars-ships


# How do I use it?

Next download (or clone) this repo and use the **flight_model.cfg** files to overwrite your local ones. You can always revert back by unzipping the packages again.


# How do I customise the files myself "on-the-fly"?

You can instantly see your flight model edits on the fly without restarting the whole sim:

1. Before your game, turn on the developer mode (Options > General > Developer > On). Make sure you see the "Developer Menu Bar" at the top of the Window as shown above.

2. Pause the sim during flight and tweak the **flight_model.cfg** file. Save file.

3. Go to top Developer mode menu and click "new project". Press ok.

4. Again go to top Developer mode menu and select aircraft menu and click "Aircraft editor".

5. Now select the "aircraft" menu and then press "resync".

6. Un-pause the sim.

7. You "don't need to save" the project. It is open anyway. DO NOT MOVE ANYTHING until the aircraft is fully reloaded (or you might get a crash).

REF: https://www.avsim.com/forums/topic/585357-fs2020-modifying-flight-model-cfg-without-restarting-sim/?do=findComment&comment=4354597


# How do I contribute?

Starring this project would be much appreciated.

To participate please create new unqiue folder names per mod as there maybe multiple config's for the same plane, 
eg "river racing" settings through to "realistic pilot experience" settings. 

Please create branches for updates to the trunk or add config file to a directory with a suffix and version, 
eg f22_TopGun_V1.


Please submit a Pull Request and we'll merge if there's no conflicts! Thanks!


# History 
2020-12-13
- Initial upload for the Raptor F22 orig and mod for the TopGun version - including weight, yaw and lift, 

- TO DO f22 need to tweak roll settings for Top Gun style.

- Initial upload for the F16 and starwars-x-wing and TopGun versions with reduced weight.


# How do I compare changes?

Using VsCode is an easy way and this will allow you to contribute to GitHub as well.

![Vs Code Compare](https://github.com/MeaningOfLights/FS2020-flight_model.cfg-custom-files/blob/main/media/VsCodeCompare.png)



