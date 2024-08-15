Thank you for purchase
_______________________________________

Follow me:
https://twitter.com/polygon_mc
https://www.instagram.com/polygony.std/
https://www.facebook.com/polygony.std
https://sketchfab.com/polygonymc
https://polygony.co/
https://docs.polygony.co
_______________________________________

Please do not resell or give away for free.
_______________________________________

Test on 1.20.2

Requirement
  • Itemsadder (with LoneLibs and ProtocolLibs) or Oraxen
  • MythicHUD-1.0.0
  • PlaceholderAPI

PAPI Setup
***papi_request***

ItemsAdder & MythicHUD Setup:
  • If you have an old 'MythicHUD' folder, please delete it and install the new one
  • Disable ItemsAdder Text Effects.
  • Disable ItemsAdder Hide Scoreboard Numbers.
  • In the MythicHUD config.yml set copy-resource-pack to enabled: true and make the path

    copy-resource-pack:
      enabled: true
      # The location to copy each namespace to. The parent path is your plugins directory.
      namespaces:
        minecraft: "ItemsAdder/contents"
        mythichud: "ItemsAdder/contents"
  • Run command /mythichud reload
  • If you are using a resource pack for client version 1.20.5+, follow the steps below:
    - Copy the files from MythicHUD/built-pack/mythichud-modern/assets/minecraft to ItemsAdder/contents
  • run command /iazip

Oraxen & MythicHUD Setup:
  • If you have an old 'MythicHUD' folder, please delete it and install the new one
  • Set action_bar: false and hide_scoreboard_numbers: false in your settings.yml file.
  • Delete Oraxen/pack/shaders/core/rendertype_text.json and rendertype_text.vsh if they exist.
  • In the MythicHUD config.yml set copy-resource-pack to enabled: true and make the path path: Oraxen/pack/assets.

    copy-resource-pack:
      enabled: true
      # The location to copy each namespace to. The parent path is your plugins directory.
      namespaces:
        minecraft: "Oraxen/pack/assets"
        mythichud: "Oraxen/pack/assets"
	
  • Run command /mythichud reload
  • If you are using a resource pack for client version 1.20.5+, follow the steps below:
    - Copy the files from MythicHUD/built-pack/mythichud-modern/assets/minecraft to Oraxen/pack/assets
  • run command /o reload all

Defualt Resoure pack:
  • If you have an old 'MythicHUD' folder, please delete it and install the new one
  • In the MythicHUD config.yml set copy-resource-pack to enabled: false
    copy-resource-pack:
      enabled: false
  • Run command /mythichud reload
  • If you are using a resource pack for client version 1.20.5+, follow the steps below:
    - Copy the files from MythicHUD/built-pack/mythichud-modern/assets/minecraft to MythicHUD/built-pack
  • Copy the files from "MythicHUD\built-pack" and paste them into the resource pack folder.
  • Put the resoure pack to Minecraft or Reload the Minecraft resoure pack

Read More: https://docs.polygony.co/getting-started/How-to-install-MythicHUD