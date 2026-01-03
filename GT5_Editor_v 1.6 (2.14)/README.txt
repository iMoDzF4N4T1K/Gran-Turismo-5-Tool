Hi,

Welcome to my custom GT5 editor & hybrid maker.
Things PD didn't include in their version, is now available.
All modifications made by this software related to cars are sourced from NGU!
No secret information is used to change this savegame file.

This tool makes a .bak file in the game directory before modification.
Move this to a different place, so you can always restore the original file.

If your in need of credits or want to move gameday, these options are there for you!
You can also set licenses and special events to gold!
And of course much much more.....

This application works with the car you currently sit in (for hybrid creating).
You can easy body, engine, chassis, drivetrain and gearbox swap, and much more.

If more info is needed, this doc will be updated.

Cheers and enjoy!

Luca

// ---------------------------------------------------------------------------------------
//
// Changelog
// 
// ---------------------------------------------------------------------------------------

Version 1.6 :

- Fixed : False pop-up's when using the borrowglitch button (when saves are bigger then only GT5.0)
- Fixed : Double pop-up for loading suspension, transmission and LSD settings
- Fixed : Made loading custom paint codes from XML _working_ (listed at the end of the select box)
- Fixed : PSN not found issue has been solved.
- Added : OCD and UCD reset function. Current and permanent.
- Added : Racenumber and racenumber font type option for cars with numbers

Version 1.5a :

- Fixed : Positions, positions and more positions
- Fixed : X number of bugs
- Added : Selectable rim color (divided from car color)
- Added : 5722cc (Default Color) and 5722cc (Color shifting at track)
- Added : 2.14 compatibility hybrid building
- Added : New routine which makes encrypting/decrypting more efficient
- Added : Button to globally make all cars reset-proof (easy for upgrade 2.11 to 2.14)
- Added : Automaticly collecting PSN name from savegame

Version 1.5 :

- Fixed : X number of bugs (not announced due to leaked source)
- Added : A-spec level changer
- Added : B-spec level changer
- Added : Special Event golder
- Added : Licenses golder
- Added : A-spec event golder
- Added : B-spec event golder
- Added : Special options menu activater
- Added : Weight multiplier
- Added : Restore car to NCD/OCD status
- Change: Added showing color when pressing "load car info"
- Update: More car's to select added
- Update: More paints to select added
- Change: Source code removed, thanks Slim!

Version 1.4 Final:

- Fixed : Error catching and cleaned up code.
- Change: Removed unfinished options.
- Fixed : All dropdownboxes now able to enter HEX value.

Version 1.3j:

- Added : Suspension & LSD swap option added
- Added : Also optional to load LSD/Suspension settings of default car you choose parts from.
- Added : Torque Front/rear level
- Fixed : Car database optimised, added year's to ALL cars!
- Change: Layout structure changed for more friendly overall-view design
- Fixed : When swapping body, move default color number back to 0 (GT5 lookup can fail if number doesn't exist)


Version 1.3i:

- Added : more cars to select from!

Verion 1.3h:

- Fixed : Sometimes the wing would not remove, this is now 99.99% fixed.
          If the wing can go off (if GT5 permits) it WILL go off!
- Fixed : Gear ratios could fail the gearbox to work properly. Now you have
          the option to also swap default gear-ratios from the selected gearbox.
- Added : LSD (Init, Acceleration, Brake)
- Added : Dampers (front/rear/left/right) (Ext. & Comp.) & Anti-Rollbar
- Added : Enable all tires (no need to buy them anymore)
- Added : You can now add your own colors to the default.xml :
          <Color>DefaultColor</Color>
          <Color>FFFFFFFF</Color>
          <Color>DefaultColor 2</Color>
          <Color>2FFFFFFF</Color>

// ---------------------------------------------------------------------------------------
//
// Tool layout and functions:
// 
// ---------------------------------------------------------------------------------------

[Select backup]

You get a pop-up to select any directory that leads to your backup.
This could be \PS3\ or anything inside where your GT5.0 (GT5.1/GT5.2) is located.

[PSN]

Here you fill in your PSN name, some unregular structure sometimes gives your XMB username.

[Gameday] + [FIX DAY]

You can switch your current gameday.
Now you can find your wanted car using the UCD sheet from GTPlanet, thanks to Famine and Duck for building that up.
If you use the sheet to find your offset in ML1 or ML2, you can move gameday to buy
the car you always wanted in a specific color.
You can download it from here: 
http://www.gtplanet.net/forum/showthread.php?t=134403

[Credits] + [FIX CR]

No more grinding, up to (999.999.999) credits so you can buy every X2010 at once!

[Special Events] / [Licenses]

Now you can select one of the events/licenses and set it to gold!
No more struggle to get Sebastian Vettel! Your rescue is here.
If that was your last to get platinum...it's within reach today.

[Current Car] / [LOAD CAR INFO]

This is informational only, no need to press the [LOAD CAR INFO] button, but if you want
to check which car your about to MOD, check it out!

[HP Multiplier]

You can multiply your car's HP, any value between 0 and 255.
I can tell you, a 30000HP car doesn't make as much fun as a 1200 GT-R!
Be wise when changing it, I suggest any value between 5 and 20.

[Engine Multiplier]

You can multiply your car's Engine, any value between 0 and 255.

[Grip Multiplier]

You can multiply your car's grip, any value between 0 and 255.
Original grip value is 100 so all over it is more grip.
Be aware, making grip 255, will result in a permanent wheelie.
Every gear switch you will go back up...and brake takes 100meter+!

[Height]

You can change the ride height front/Rear by entering any value between 0 and 255.
Make your slammed car today!

[Camber]

You can change the camber front/Rear by entering any value between 0 and 255.
Example if you type 152, you have then 15.2 camber.

[Drivetrain]

Select here the drivetrain you want to install on your currently in use car!
Not all combinations will work between body/chassis/Engine/Drivetrain and gearbox!

[Engine]

Select here the Engine you want to install on your currently in use car!
Not all combinations will work between body/chassis/Engine/Drivetrain and gearbox!

[Body]

Select here the body you want to install on your currently in use car!
Not all combinations will work between body/chassis/Engine/Drivetrain and gearbox!

[Chassis]

Select here the Chassis you want to install on your currently in use car!
Not all combinations will work between body/chassis/Engine/Drivetrain and gearbox!

[Gearbox]

Select here the gearbox you want to install on your currently in use car!
Not all combinations will work between body/chassis/Engine/Drivetrain and gearbox!
Also remember, when swapping gearbox, set some proper gear ratios!

[Color]

Select one of the pre-defined color scheme's or add yourself a 8digit HEX value.

[Weight]

Weigth is added for you to manipulate. You have to add Weight reduction from the
dropdown box in order to use the weight tool.

[Weight multiplier]

Multiply up to 155 times weight. 
Sample: Weight = 1000kg (100%)
Filling in 1 makes your car weight 10kg (1%), filling in 255 makes your car weight 2550kg (255%)

[Toe]

You can change the toe front/Rear by entering any value between 0 and 255.

[Spring rate]

You can change the spring rate front/Rear by entering any value between 0 and 255.
Example if you add 205 then you have 20.5 (kgf/mm)

[Remove wing]

You have the option to remove the wing from a default car.
You first have to upgrade the wing to the highest stage available in GT Auto!!
This is still in semi-experimental stage, not all wings (but most) gets removed this way.

[Enable tires]

Select this to enable all car tires for the car.
From practice mode, you can select Racing Super Soft and other non-PD selectable tire compounds.
Once equipped from practice mode, you can use them in GT Life until you change tires again.

[Downforce]

Set front and rear downforce, value from 0 to 255.

[HYBRID CAR]

After pressing this button, all above options are installed on the car!

[DISCONNECT BORROWED CAR]

This button disconnects the borrowed car, like you always owned it.

[Torque]

To make the car a real 4WD/RWD etc you need to set the torque split.
You can adjust the front and the rear will be set automaticly.

[A-spec level changer]

Change your A-spec level up/down.

[B-spec level changer]

Change your B-spec level up/down.

[Special Events]

You can set one or more (all) to gold, good if your stuck at Vettel challenge for reaching Platinum.

[Licenses]

You can set one or more (all) licenses to gold. (come'on, learn to drive)

[A-spec Events]

Set one or more events to gold, and cash in your prizes.

[B-spec Events]

Set one or more events to gold, and cash in your prizes.

[Change Car]

Change the car your currently in, into NCD/OCD 000!
To not leave a switch, it could be easy to be in Setup-B before processing this.
And be aware, miles are reset as soon as you leave the car!

[ENABLE Special Menu]

To enable the special menu where you have the opportunity to create races with pre-selected cars.
Change other stuff (you see for yourself)


//-- That's it! Take it or leave it!
//-- One tip, buy DLC, support PD with their great quest to GT6!~
//-- We all can't wait.
