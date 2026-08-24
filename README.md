# DnD Effects Board Setup

For our DnD or other Table Top games we have automated some lighting and sound effects to enhance our game play and a stop towards total emersion. 

**Requirements:**
    - Philips Hue for lighting Scenes
    - Doppler local MP3 player
    - Saved mp3 files
    - Apple Shortcuts

1. Lighting:
    - Setup scene for Downstairs in Hue app
    - save as DnD - * so we know what it is for. 

**2. Download sound effects or background ambience**
    - Mainly found via YouTube
    - https://y2mate.gs/
    - File folder: “On My iPhone⁩ ▸ ⁨DnD⁩”

**3. Doppler MP3 Player**
    - Download if not already installed.
    - Add songs to Doppler
        - Go to Files app. 
        - Select all songs that need to be played.
        - Share and select Doppler app.
    - Create a Playlist - this can be one song sequenced sound effects etc. 
    - Once created you have to play it once to be able to select it in next step. 

**4. Create an Apple Shortcut for your lighting and sound emersion.**
    - Name it DnD-* with no spaces. 
    - Build what you want but here are some tips:
        - To add Doppler playlist: 
            - Search Doppler in actions
            - Select the App
            - Then you will see Playlists below. 
            - BUT only if you have played them already. 
        - Audio is played last - it takes time to activate the song and come back to next command leaving a delay. 
        - For your Hue scenes, Doppler audio playlists there is a little down arrow for extra config. Uncheck “Show when run”. With this on it pauses and gives you a pop up that it triggered.
        - Play with it and get creative. Some will work right others won’t. But that’s the fun. 
    - Save and create them all and of course test your hem as you go on.

**5. Web App UI:**
    - Created this html page with AI. A lot of trial and error. 
    - html file is hosted in my GitHub.com account. 
    - Page is hosted for free in GitHub pages
    - in the code there are blocks for each effect. It basically calls a he Apple Shortcut you just created. 
    - To add another effect:
        - Copy a block and place it under the proper category. 
        - Ensure the Apple shortcut name is properly updated. 
        - Update the data-cat in the href link so that it is associated to the proper category drop down. 
        - Update the div class TAG as this affects how the tile looks. 
        - Commit changes and wait for about a minute. 

**6. Creating the Web App icon.**
    - This has to run within Safari browser due to how it is able to interface with Apple iPhone security. 
        - Note this does not effect your Default browser
    - Open the link in the Safari browser:
        - https://midwaymonster.github.io/DnD-Effects
    - Click Share > Add to Home Screen
        - Edit Name
        - Ensure “Open as Web App” is selected
    - Now you can click it from Home Screen like a mobile app and it is all contained in there running through Safari. 
    - You will see it flash to Shortcuts briefly and first time each shortcut will ask if it can be run. Choose Always Allow
