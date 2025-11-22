# ![](https://github.com/miggtorr/ShinyFieldCatalogue/blob/main/resources/myIcon.iconset/icon_32x32.png) Shiny Field Catalogue ![](https://github.com/miggtorr/ShinyFieldCatalogue/blob/main/resources/myIcon.iconset/icon_32x32.png)
### A macOS app to Count, Track, and Catalogue your Pokémon Shiny Hunt

#### 🤖 AI Disclosure: 
This project began with me learning how to use some of the coding features in the ChatGPT workspace provided by my employer. Thus, I used AI to write a significant portion of the code in Python. 

That said, the code was tested, tweaked, and debugged by hand by a real human (me) on a handful of real MacBooks.

**NO AI** was used for ANY Art or Text (including this readme!). All custom art (e.g., the app icon, sprite placeholders, etc.) was made by hand in Adobe Illustrator (by me! ❤️). All Pokémon sprites are downloaded at runtime via the PokéAPI, as is the Alpha icon from Bulbapedia.

# ![](https://github.com/miggtorr/ShinyFieldCatalogue/blob/main/resources/myIcon.iconset/icon_32x32.png) Installation & Running the App ![](https://github.com/miggtorr/ShinyFieldCatalogue/blob/main/resources/myIcon.iconset/icon_32x32.png)

## Download & Installation

To download the app, get the latest version from [Releases](https://github.com/miggtorr/ShinyFieldCatalogue/releases).

To install the app, unzip the file, open up the DMG and drag the app into your /Applications folder.

### OS Requirements

This app has been tested on **macOS 14 Sonoma** and **macOS 26 Tahoe**. 
It will not run on Windows or Linux. Sorry!

## Running the App

I am not an official Apple Developer, so this app is not "signed" or "notarized." 
This means that your system will complain that it "could contain malware."

If you are getting this from my (miggtorr) GitHub, there is no malware, lol. I will try to get an Apple Developer Account soon so I can sign my apps. :)

In any case, TO BE ABLE TO USE THE APP, you must open **Terminal** and--as an admin user--type:

`sudo xattr -d com.apple.quarantine "/Applications/Shiny Field Catalogue.app"`

Then launch the app and it should run fine. :)

## Uninstalling the App

To uninstall the app you can just drag it to the trash. 
There are also config files that save to `/Users/[yourUsername]/Library/Application Support/Shiny Field Catalogue/`. 
Delete the "Shiny Field Catalogue" folder there and you're all set!

# ![](https://github.com/miggtorr/ShinyFieldCatalogue/blob/main/resources/myIcon.iconset/icon_32x32.png) Features ![](https://github.com/miggtorr/ShinyFieldCatalogue/blob/main/resources/myIcon.iconset/icon_32x32.png)

- Keep a record of EVERY shiny you've EVER found FOR AS LONG AS YOU EXIST.
  - Export/Import records as JSON for backup, transfer, sharing, and simple readabilty.
    - If this app ever dies, you'll STILL be able to read your hunt data because JSON is human-readable and easily parsed by many applications!
- Includes tools to hunt in real time!
  
## ![](https://github.com/miggtorr/ShinyFieldCatalogue/blob/main/resources/myIcon.iconset/icon_16x16.png) Detail-Rich Hunt Records
- Pokémon Name
– Method Used for Hunt (e.g., Random Encounters, Soft Resets, DexNav, etc.)
- Pokémon Game you hunted it in.
  - Included every main line Pokémon Game
  - Lets the user add custom games for future-proofing or RomHacks
    - Custom games will import with JSON data when you import a set of hunts!
- The Base Odds (8192, 4096, or 300 for DAs)
- Target gender
- Alpha status
- Date started/ended
- Number of Encounters
- Video Clip link field (e.g., for YouTube/Twitch clips, shiny reactions, etc.)
- Detailed Records for each Phase you encountered along the way.
  - Name, Gender, Alpha Status, Count when found, Time when found, Notes, Shiny Clip Link field.
- Shiny Charm Status
- Space for Notes (e.g., if you were going after a particular nature, if you were hunting with your eyes closed, part of a quest, etc.)

## ![](https://github.com/miggtorr/ShinyFieldCatalogue/blob/main/resources/myIcon.iconset/icon_16x16.png) Live Shiny Hunting Tools
- Customizable encounter counter
  - Can increase/decrease by any increment.
  - Arbitrary, customizable keybinds
  - Basic "Chance-You-Should-Have-Found-It-By-Now" Calculator
  - Adjust the number of shiny rolls per encounter
    
- Popout window for streaming or just to have while you're watching something.
  - Displays counter, sprite, +/- buttons
  - Always stays on top of other windows! :)

## ![](https://github.com/miggtorr/ShinyFieldCatalogue/blob/main/resources/myIcon.iconset/icon_16x16.png) Backup & Share Records
- Export all your hunts as JSON
  - Backup
  - Sharing
  - Transferring to a new device
    
- Import backed-up hunts as JSON
  - Custom games are automatically added to your list of games when importing!
    
- Human-readable data!
- Easy to handle/parse if this app ever dies.
  
- Share your hunts with others!
  
## ![](https://github.com/miggtorr/ShinyFieldCatalogue/blob/main/resources/myIcon.iconset/icon_16x16.png) Other Features
- Gorgeous, low file-size shiny sprites downloaded from PokéAPI and cached locally.
- Support for custom images (e.g., if you want an oldschool sprite)
  - no animated GIF support yet 🙏
    
- Autofill feature when adding a hunt so you know you're spelling a mon's name right.
  - It's still a little buggy:
    - Press "Enter" to complete the name, then "Tab" to deselect the textbox.







