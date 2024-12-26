#===============================================================================================================
# NeverSink's Indepth Loot Filter - for Path of Exile
#===============================================================================================================
# VERSION:  0.1.1
# AUTHOR:   NeverSink
#
# This is a mini-filter designed for early PoE2 EA gameplay. I will eventually replace it with a full-fledged filter
# With FilterBlade.xyz support. This filter focuses more on highlighting loot, rather than hiding
#
# TWITTER: @NeverSinkDev
# DISCORD: https://discord.gg/mye6xhF
# TWITCH:  https://www.twitch.tv/neversink
# PATREON: https://www.patreon.com/Neversink

#--------------------------
# Overrides - Uniques, Valuables
#--------------------------

Show
Rarity Unique
SetTextColor 175 96 37 255
SetBorderColor 175 96 37 255
SetBackgroundColor 53 13 13 255
#PlayAlertSound 3 300
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
SetTextColor 20 240 240
SetBorderColor 20 240 240
ItemLevel < 19
PlayAlertSound 2 300
PlayEffect Cyan
#MinimapIcon 1 Cyan Triangle


Hide
BaseType "Uncut "
SetTextColor 200 140 240 
SetBorderColor 20 240 240
ItemLevel = 19
PlayEffect Cyan
#MinimapIcon 2 Brown Star

Show
BaseType "Uncut "
SetTextColor 240 100 100 
SetBorderColor 100 240 200
ItemLevel = 20
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
BaseType "Gemcutter's Prism" "Orb of Annulment" "Orb of Chance"
SetTextColor 255 255 255 255
SetBorderColor 255 255 255 255
SetBackgroundColor 240 90 35
#PlayAlertSound 1 300
CustomAlertSound "Tbongbong.wav" 300
PlayEffect White
MinimapIcon 1 White Circle
SetFontSize 40

# Currency Tier B: Vaal, Chaos, Exalt, Exotic
Show
Class "Currency"
BaseType "Vaal Orb" "Greater Jeweller's Orb" "Chaos Orb" "Lesser Jeweller's Orb" "Exotic" "Exalted Orb" "Regal Orb" "Artificer's Orb" "Glassblower's Bauble" "Orb of Alchemy" "Orb of Chance"
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

# Currency Tier C: Vaal, Chaos, Exalt, Exotic
Show
Class "Currency"
BaseType "Arcanist's Etcher" "Armourer's Scrap" "Blacksmith's Whetstone" "Orb of Augmentation" "Orb of Transmutation" "Regal Shard" "Chance Shard"
CustomAlertSound "Tbong.wav" 300
SetTextColor 255 207 132
SetBorderColor 255 207 132
MinimapIcon 2 Grey Circle

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
PlayAlertSound 2 300
PlayEffect White
MinimapIcon 1 White Square
SetFontSize 40

Hide
BaseType "Waystone"
Rarity <= Rare
DropLevel <= 74
SetTextColor 255 255 255
SetBorderColor 255 255 255
#PlayAlertSound 4 300
#CustomAlertSound "Tmexico.wav" 300
#PlayEffect White
#MinimapIcon 1 White Square
SetFontSize 40

Show
# T11-12
BaseType "Waystone"
Rarity <= Rare
DropLevel >= 75
DropLevel < 77
SetFontSize 45
SetTextColor 210 40 100 250
SetBorderColor 160 10 80 250
CustomAlertSound "Tmexico.wav" 300
PlayEffect White
MinimapIcon 1 White Square

Show
# T13
BaseType "Waystone"
Rarity <= Rare
DropLevel = 77
SetFontSize 45
SetTextColor 210 40 100 250
SetBorderColor 160 10 100 250
CustomAlertSound "Tchina.wav" 300
PlayEffect Yellow
MinimapIcon 2 Brown Star


Show
# T14
BaseType "Waystone"
Rarity <= Rare
DropLevel = 78
SetFontSize 45
SetTextColor 255 0 0 255
SetBorderColor 255 0 0 255
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
SetBorderColor 255 0 0 255
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


# Not working!
#Hide
#Sockets > 0
#Rarity Magic
#SetBorderColor 0 0 200
#SetFontSize 35

#Hide
#Quality > 0
#Rarity Magic
#SetBorderColor 0 0 200
#SetFontSize 35

#--------------------------
# OPTIONAL RULES
#--------------------------
# TO ENABLE RULES, REMOVE THE # AT THE START OF THE LINE

### OPTIONAL RULE: Hide random bases
# REMOVE THE BASES YOU --DO-- WANT TO SEE BEFORE SETTING TO HIDE

Hide
Rarity <= Magic
Class "Flask" "Body" "Helmet" "Boots" "Gloves" "Shields" "Quiver" "Mace" "Staff" "Quarter" "Bow" "Crossbow" "Wand" "Sceptre" "Focus"
AreaLevel >= 65

### OPTIONAL RULE: REDUCES BACKGROUND ON LOW LEVEL BASES

 Hide
 Rarity <= Magic
 Class "Flask" "Body" "Helmet" "Boots" "Gloves" "Shields" "Quiver" "Mace" "Staff" "Quarter" "Bow" "Crossbow" "Wand" "Sceptre"
 AreaLevel >= 65
 DropLevel <= 50
 SetBackgroundColor 0 0 0 125

#--------------------------
# Meta
#--------------------------

# If this thing crashes, time to update your filter!
# This is here to prevent people to use this filter for AGES. Expert items will get removed eventually
# Get a new filter from www.filterblade.xyz

Show
BaseType == "Expert Laced Boots"
