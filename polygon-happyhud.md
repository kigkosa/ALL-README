Thank you for purchase
_______________________________________

Follow me:
https://twitter.com/polygon_mc
https://www.instagram.com/polygony.std/
https://www.facebook.com/polygony.std
https://sketchfab.com/polygonymc

_______________________________________

Please do not resell or give away for free.
_______________________________________

Test on 1.20.2

Requirement
  • Itemsadder (with LoneLibs and ProtocolLibs) or Oraxen
  • HappyHUD-1.0.13-RELEASE
  • PlaceholderAPI
  • ProtocolLib



PAPI Setup
***papi_request***

ItemsAdder & HappyHUD Setup:
  • If you have an old 'HappyHUD' folder, please delete it and install the new one
  • Disable ItemsAdder Text Effects.
  • Disable ItemsAdder Hide Scoreboard Numbers.
  • In the HappyHud config.yml set copy-resource-pack to enabled: true and make the path

    copy-resource-pack:
      enabled: true
      # The location to copy each namespace to. The parent path is your plugins directory.
      namespaces:
        minecraft: "ItemsAdder/contents"
        happyhud: "ItemsAdder/contents"
  • Run command /happyhud reload
  • run command /iazip

Oraxen & HappyHUD Setup:
  • If you have an old 'HappyHUD' folder, please delete it and install the new one
  • Set action_bar: false and hide_scoreboard_numbers: false in your settings.yml file.
  • Delete Oraxen/pack/shaders/core/rendertype_text.json and rendertype_text.vsh if they exist.
  • In the HappyHud config.yml set copy-resource-pack to enabled: true and make the path path: Oraxen/pack/assets.

    copy-resource-pack:
      enabled: true
      # The location to copy each namespace to. The parent path is your plugins directory.
      namespaces:
        minecraft: "Oraxen/pack/assets"
        happyhud: "Oraxen/pack/assets"
	
  • Run command /happyhud reload
  • run command /o reload all

Defualt Resoure pack:
  • If you have an old 'HappyHUD' folder, please delete it and install the new one
  • In the HappyHud config.yml set copy-resource-pack to enabled: false
    copy-resource-pack:
      enabled: false
  • Run command /happyhud reload
  • Copy the files from "HappyHUD\built-pack" and paste them into the resource pack folder.
  • Put the resoure pack to Minecraft or Reload the Minecraft resoure pack
