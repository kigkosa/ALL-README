Terms of Use.
If you have used our products, it means you agree to the terms of service, which apply to our products.

1.You may alter the configuration or add-ons to fit your style or server needs, but under no circumstance make those changes available for purchase.
2.The products are created by 3bstudio, who is the copyright owner of the products.
3.You cannot put our products on sale anywhere and you cannot sell our products to anyone.
4.If there are any issues or bugs after modifying the configuration, we will not take any responsibility for them, and it will be solely your server's responsibility.

Test on 1.20.2

Requirement
  • Itemsadder (with LoneLibs and ProtocolLibs) or Oraxen
  • BetterHud
  • PlaceholderAPI


PAPI Setup
  • /papi ecloud download Player
  • /papi ecloud download Vault
  • /papi ecloud download LocalTime

ItemsAdder & BetterHud Setup
  • Disable ItemsAdder Text Effects (https://itemsadder.devs.beer/plugin-usage/text-effects-1.17+).
  • Disable ItemsAdder Hide Scoreboard Numbers (https://itemsadder.devs.beer/plugin-usage/hide-scoreboard-numbers-1.17+).
  • In the ItemsAdder/config.yml

    merge_other_plugins_resourcepacks_folders:
    - ModelEngine/resource pack
    - BetterHud/build
    
  • run command /iazip

Oraxen & BetterHud Setup
  • Set action_bar: false and hide_scoreboard_numbers: false in your settings.yml file.
  • Delete Oraxen/pack/shaders/core/rendertype_text.json and rendertype_text.vsh if they exist.
  • Copy BetterHud/build to Oraxen/pack/assets
  • run command /o reload all



--------------------------

Create by 3BSTUDIO

--------------------------

The channel to inquire about problems : https://discord.gg/4c2jvJXACQ

Thankyou For Purchase
