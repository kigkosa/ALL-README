Terms of Use.
If you have used our products, it means you agree to the terms of service, which apply to our products.

1.You may alter the configuration or add-ons to fit your style or server needs, but under no circumstance make those changes available for purchase.
2.The products are created by 3bstudio, who is the copyright owner of the products.
3.You cannot put our products on sale anywhere and you cannot sell our products to anyone.
4.If there are any issues or bugs after modifying the configuration, we will not take any responsibility for them, and it will be solely your server's responsibility.

Test on 1.20.2

Requirement
  • Itemsadder (with LoneLibs and ProtocolLibs) or Oraxen
  • HappyHud-1.0.11
  • PlaceholderAPI


PAPI Setup
  • /papi ecloud download Player
  • /papi ecloud download Vault

ItemsAdder & HappyHUD Setup
  • Disable ItemsAdder Text Effects.
  • Disable ItemsAdder Hide Scoreboard Numbers.
  • In the HappyHud config.yml set copy-resource-pack to enabled: true and make the path

    copy-resource-pack:
      enabled: true
      # The location to copy each namespace to. The parent path is your plugins directory.
      namespaces:
        minecraft: "ItemsAdder/contents"
        happyhud: "ItemsAdder/contents"
  • run command /iazip

Oraxen & HappyHUD Setup
  • Set action_bar: false and hide_scoreboard_numbers: false in your settings.yml file.
  • Delete Oraxen/pack/shaders/core/rendertype_text.json and rendertype_text.vsh if they exist.
  • In the HappyHud config.yml set copy-resource-pack to enabled: true and make the path path: Oraxen/pack/assets.

    copy-resource-pack:
      enabled: true
      # The location to copy each namespace to. The parent path is your plugins directory.
      namespaces:
        minecraft: "Oraxen/pack/assets"
        happyhud: "Oraxen/pack/assets"

  • Copy ItemsAdder/contents/castle_hud/assets to Oraxen/pack/assets
  • run command /o reload all



--------------------------

Create by 3BSTUDIO

--------------------------

The channel to inquire about problems : https://discord.gg/4c2jvJXACQ

Thankyou For Purchase
