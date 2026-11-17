1ASSETS FOLDER  (flat: every file sits directly inside "Assets", no sub-folders)
Names are exact and case-sensitive. Use .png (transparent background recommended).
Anything missing is shown as a magenta placeholder labelled with its file name.

BanSimulator2000.html
Assets/
|-- roblox_logo.png               splash screen logo                       ~560x220
|-- menu_character.png            character on the main menu               300x480
|-- bg_room.png                   full room background (optional)          1280x720
|-- desk.png                      desk strip in front (optional)           1280x170
|-- button_ban.png                red button                               300x130
|-- button_unban.png              green button                             300x130
|-- david_body.png                David standing in the background         150x270
|-- david_icon_calm.png           right thermometer icon, low              64x64
|-- david_icon_mad.png            right thermometer icon, medium           64x64
|-- david_icon_furious.png        right thermometer icon, high             64x64
|-- community_icon_happy.png      left thermometer icon, low               64x64
|-- community_icon_meh.png        left thermometer icon, medium            64x64
|-- community_icon_angry.png      left thermometer icon, high              64x64
|-- helpy.png                     Helpy avatar on the tips panel           100x100
|-- tips_panel.png                tips panel frame (optional)              700x360
|-- paper.png                     ban reason paper (optional)              420x520
|-- hands_paper_left.png          left hand holding the paper              120x240
|-- hands_paper_right.png         right hand holding the paper             120x240
|-- david_gameover.png            David game-over image, zooms from the    300x420
|                                 centre until it fills the screen
|-- game_over_irregularity.png    full-screen "An irregularity has been    1280x720
|                                 detected" game-over screen
|-- player_1.png                  banned player avatars (rise from the     320x360
|-- player_2.png                  desk, centred)
|-- player_3.png
|-- player_4.png
|-- player_5.png
`-- player_6.png

"(optional)" = the game draws a CSS fallback (sky/desk/dome buttons/paper/panel)
if the file is missing, and swaps it out as soon as the file exists.
