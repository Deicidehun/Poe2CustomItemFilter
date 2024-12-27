#===============================================================================================================
# Based on NeverSink's Indepth Loot Filter - for Path of Exile 2
#===============================================================================================================
# Strict 
# V3.2 - Qaurterstaff Meta drop removed
#      - Adjusted Salvagable visibility
#
# Install: copy filter and sound (wav) files to C:/User/My Games/Path of Exile 2/
# load filter in game (Options/Game/Item Filter - find file MakePoeGreatAgain-Strict.filter


#--------------------------
# Overrides - Uniques, Valuables
#--------------------------

Show
Rarity Unique
SetTextColor 175 96 37 255
SetBorderColor 175 96 37 255
SetBackgroundColor 53 13 13 255
CustomAlertSound "Tfakenews.wav" 300
PlayEffect Brown
MinimapIcon 2 Brown Star
SetFontSize 40

## Divine Orb Style
Show
Class "Currency"
BaseType "Mirror" "Divine" "Perfect Jeweller's Orb"
SetFontSize 45
SetTextColor 255 0 0 255
SetBorderColor 255 0 0 255
SetBackgroundColor 255 255 255 255
PlayAlertSound 6 300
PlayEffect Red
MinimapIcon 0 Red Star

#--------------------------
# Gold
#--------------------------

Show
StackSize >= 500
BaseType == "Gold"
SetTextColor 255 255 255
SetBorderColor 255 255 255
PlayEffect Orange Temp

Show
BaseType == "Gold"
CustomAlertSound "smw_coin.wav" 300
SetTextColor 180 180 180
SetBorderColor 0 0 0 255
SetBackgroundColor 0 0 0 180

#--------------------------
# Uncut Gems
#--------------------------

Hide
BaseType "Uncut "
ItemLevel < 20

Show
BaseType "Uncut "
SetTextColor 240 100 100 
SetBorderColor 100 240 200
ItemLevel >= 20
CustomAlertSound "Tlovemylife.wav" 300
PlayEffect Cyan
MinimapIcon 0 Red Star

#--------------------------
# Socketables and Special Character Equipment
#--------------------------

# Special A Tier - League specific socketables and jewels
Show 
BaseType "Soul Core" "Timeless"
CustomAlertSound "T300billion.wav" 300
SetTextColor 0 240 190
SetBorderColor 0 240 190
SetFontSize 40
MinimapIcon 2 Cyan Triangle
PlayEffect Cyan

# Special A Tier - Sanctum Relics
Show 
Class "Relic"
SetTextColor 0 240 190
SetBorderColor 0 240 190
SetFontSize 40
MinimapIcon 2 Cyan Triangle
PlayEffect Cyan

# Special A Tier - Rare Jewels
Show
Class "Jewel"
Rarity Rare
SetTextColor 0 240 190
SetBorderColor 0 240 190
CustomAlertSound "T300billion.wav" 300
SetFontSize 40
MinimapIcon 2 Cyan Triangle
PlayEffect Cyan

# Special B Tier - Any Jewels
Show
Class "Jewel"
Rarity Magic
SetTextColor 0 240 190
SetBorderColor 0 240 190
CustomAlertSound "T300billion.wav" 300
SetFontSize 40
PlayEffect Cyan Temp

# Special B Tier - Any Runes and Charms
Show
BaseType "Golden Charm"
SetTextColor 60 180 230
PlayEffect Yellow
SetBorderColor 210 210 80
SetBackgroundColor 20 80 80
CustomAlertSound "26f8b9_sonic_ring_sound_effect.wav" 300

Show 
BaseType " Rune" " Charm"
SetTextColor 40 140 190
PlayEffect Cyan Temp


#--------------------------
# Socketables and Special Character Equipment
#--------------------------

# Currency Tier A: Gemcutter, Annullment
Show
Class "Currency"
BaseType "Gemcutter's Prism" "Orb of Annulment" 
SetTextColor 255 255 255 255
SetBorderColor 255 255 255 255
SetBackgroundColor 240 90 35
CustomAlertSound "Tbongbong.wav" 300
PlayEffect White
MinimapIcon 1 White Circle
SetFontSize 40

# Currency Tier B: Vaal, Chaos, Exalt, Exotic
Show
Class "Currency"
BaseType "Orb of Chance" "Vaal Orb"
SetTextColor 255 255 255 255
SetBorderColor 255 255 255 255
SetBackgroundColor 240 90 35
CustomAlertSound "Tsoundsgood.wav" 300
PlayEffect White
MinimapIcon 1 White Circle
SetFontSize 40

Show
Class "Currency"
BaseType "Greater Jeweller's Orb" "Chaos Orb" "Lesser Jeweller's Orb" "Exotic" "Exalted Orb" "Regal Orb" "Artificer's Orb" "Glassblower's Bauble" "Orb of Alchemy"
SetTextColor 255 207 132
SetBorderColor 255 207 132
SetBackgroundColor 76 51 12
#PlayAlertSound 2 300
CustomAlertSound "Tbingbing.wav" 300
PlayEffect White
MinimapIcon 1 White Circle
SetFontSize 40

Show
Class "Currency"
BaseType "Distilled" "Catalyst" "Essence of" "Omen of"
SetTextColor 255 207 132
SetBorderColor 255 207 132
SetBackgroundColor 76 51 12
#PlayAlertSound 2 300
CustomAlertSound "Tthisguy.wav" 300
PlayEffect White
MinimapIcon 1 White Circle

# Currency Tier C: Shard
Show
Class "Currency"
BaseType "Arcanist's Etcher" "Armourer's Scrap" "Blacksmith's Whetstone" "Orb of Augmentation" "Orb of Transmutation" "Regal Shard" "Chance Shard"
CustomAlertSound "Tbong.wav" 300
SetTextColor 255 207 132
SetBorderColor 255 207 132
MinimapIcon 2 Grey Circle

# Currency Tier D: Splinter, Artifact
Show
Class "Currency"
BaseType "Simulacrum Splinter" "Breach Splinter" " Artifact" 
CustomAlertSound "Tbillions2.wav" 300
SetTextColor 255 207 132
SetBorderColor 255 207 132
MinimapIcon 2 Grey Circle

Show
Class "Currency"
BaseType "Wisdom" "Shard"

# Unknown currency
Show
Class "Currency"
SetTextColor 255 207 132
SetBorderColor 255 207 132
SetBackgroundColor 76 51 12
PlayAlertSound 2 300
PlayEffect Pink
MinimapIcon 1 White Circle

# Fragments
Show
BaseType "Simulacrum" " Tablet" "Breachstone" "Barya" "Ultimatum" " Fragment" "Cowardly Fate" "Deadly Fate" "Victorious Fate" "Expedition Logbook"
SetTextColor 255 207 255
SetBorderColor 255 207 255
SetBackgroundColor 65 20 80
CustomAlertSound "smw_1-up.wav" 300
PlayEffect White
MinimapIcon 1 White Square
SetFontSize 40

# Waystones
Hide
BaseType "Waystone"
DropLevel <= 74

# T11-12
Show
BaseType "Waystone"
DropLevel >= 75
DropLevel < 77
SetFontSize 45
SetTextColor 210 40 100 250
SetBorderColor 160 10 80 250
CustomAlertSound "Tmexico.wav" 300
PlayEffect White
MinimapIcon 1 White Square

# T13
Show
BaseType "Waystone"
Rarity <= Rare
DropLevel = 77
SetFontSize 45
SetTextColor 210 40 100 250
SetBorderColor 180 180 100 250
CustomAlertSound "Tchina.wav" 300
PlayEffect Yellow
MinimapIcon 2 Brown Star

# T14
Show
BaseType "Waystone"
Rarity <= Rare
DropLevel = 78
SetFontSize 45
SetTextColor 255 0 0 255
SetBorderColor 255 250 0 255
CustomAlertSound "Tchinabig.wav" 300
PlayEffect Red
MinimapIcon 0 Red Star

Show
# T15+
BaseType "Waystone"
Rarity <= Rare
DropLevel >= 79
SetFontSize 45
SetTextColor 255 0 0 255
SetBorderColor 0 10 250 255
SetBackgroundColor 240 240 240 255
CustomAlertSound "Tamerica.wav" 300
PlayEffect Red
MinimapIcon 0 Red Star

#--------------------------
# Value Rares
#--------------------------

Show
Class "Rings" "Amulets" "Belts"
Rarity Rare
SetFontSize 40
SetTextColor 233 206 75
SetBorderColor 233 206 75
PlayEffect Yellow
CustomAlertSound "Treallyrichfx.wav" 300
MinimapIcon 1 Yellow Diamond

#--------------------------
# Rings, Amulets, Belts
#--------------------------

Show
Rarity Normal
Class "Rings" "Amulets" "Belts"
SetFontSize 40
CustomAlertSound "26f8b9_sonic_ring_sound_effect.wav" 300

Show
Class "Rings" "Amulets" "Belts"
Rarity Magic
SetFontSize 40
CustomAlertSound "26f8b9_sonic_ring_sound_effect.wav" 300

#--------------------------
# Salvagable Items
#--------------------------

Show
Class "Helmet" "Boots" "Gloves" 
Sockets > 0
SetBorderColor 0 0 200
SetFontSize 35

Show
Class "Body" "Shields" 
Sockets > 1
SetBorderColor 0 0 200
SetFontSize 35

Show
Class "Body" "Helmet" "Boots" "Gloves" "Shields" "Mace" "Staff" "Wand" "Sceptre" "Focus"
Quality > 0
SetBorderColor 0 0 200
SetFontSize 35

#--------------------------
# OPTIONAL RULES
#--------------------------
# TO ENABLE RULES, REMOVE THE # AT THE START OF THE LINE
### OPTIONAL RULE: Hide random bases
# REMOVE THE BASES YOU --DO-- WANT TO SEE BEFORE SETTING TO HIDE

Hide
Rarity <= Rare
Class "Flask" "Body" "Helmet" "Boots" "Gloves" "Shields" "Quiver" "Mace" "Staff" "Bow" "Crossbow" "Wand" "Sceptre" "Focus"

#AreaLevel >= 77
### OPTIONAL RULE: REDUCES BACKGROUND ON LOW LEVEL BASES

Hide
Rarity <= Rare
Class "Flask" "Body" "Helmet" "Boots" "Gloves" "Shields" "Quiver" "Mace" "Staff" "Bow" "Crossbow" "Wand" "Quarterstaff" "Sceptre" "Focus"
AreaLevel >= 77
DropLevel <= 70


#--------------------------
# Meta
#--------------------------

#Show
#Class "Quarterstaff"
#DropLevel >= 77
#SetTextColor 250 207 132
#SetBorderColor 250 207 132
#SetBackgroundColor 76 51 12
#PlayAlertSound 2 300
#PlayEffect Pink
#MinimapIcon 1 White Circle