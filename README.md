# 99kr-burglary

>This is a simple script for doing a burglary in a house, there isn't a way to sell the items so you have to fix it yourself. Also a lotteryticket item where you can scrape it and have a chance to win money.

If you want to have it non-esx you can just delete the ESX lines and make it for another framework if you want to.
 
 You can find the configuration and locales in the client or server file, [burglary_client.lua] [burglary_server.lua]. 
 
 # Configurable
  - Positions and locations
  - Locales
  - Lottery ticket
  - Enable interactsound and/or esx-qalle-camerasystem
  - Enable Blip
  - The chance the cops get notified of the burglary

 # Requirements
  - ESX
  - esx_policejob
  - ( OPTIONAL ) esx-qalle-camerasystem ( https://github.com/qalle-fivem/esx-qalle-camerasystem )
  - ( OPTIONAL ) InteractSound ( https://github.com/plunkettscott/FiveM-Scripts )
  - esx_phone/esx_phone3 ( you can edit the event to gcphone if you use that )
  
  # Video
  - https://streamable.com/v8gky
  
  # Installation
  - Download and put it into your resources
  - Import the SQL
  - put `start 99kr-burglary` in your server.cfg
  
  ## Tutorial for InteractSound
   - Place the lockpick.ogg inside InteractSound/client/html/sounds
   - Open the __resource.lua
   - Put `'client/html/sounds/lockpick.ogg',` under the `'client/html/sounds/demo.ogg',`
   - Done
