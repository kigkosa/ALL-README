Test on 1.20.1

Requirement
  • Itemsadder (with LoneLibs and ProtocolLibs) or Oraxen
  • HappyHud-1.0.6
  • PlaceholderAPI


PAPI Setup
  • /papi ecloud download Player

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


Thankyou For Purchase
