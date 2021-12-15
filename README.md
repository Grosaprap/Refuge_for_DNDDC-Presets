# Refuge_for_DNDDC-Presets
This is a download archive of the presets that were shared on the now defunct Dungeons and Deviousness - Director's Cut Presets Discord channel

If one of your files was uploaded here and you don't wish it to be, please contact me and I'll remove it. This was created soley because the annoucement of the removeal of the channels gave only 24 hours for people to find out about and archive the stuff they wanted, no disrepect of creators rights was intended.

Attribution has been added based on Discord username, if it was clear the uploader was claiming ownership the attribution reads "by author" if it was unclear that the uploader was claming ownership the attribution reads "uploaded by". Corrections are welcome either via submitting an issue or a pull request to correct the file names directly.

--- From the channel's pinned messages --

Some racemenu presets may use more overlay slots than are provided by default, which will result in an incomplete display for a preset that exceeds them. 

To use these presets (like many of sweinen's), the overlay slots need to be expanded in the racemenu ini to accommodate (mods\RaceMenu\SKSE\Plugins\skee64.ini). Please note that modifying this file is not a Rule 11 violation, but you do so at your OWN RISK and is not supported (if done correctly, there is no danger, but please be careful). 

Look for the iNumOverlays var under the headings

[Overlays/Body] ; "Body [Ovl#]" and "Body [SOvl#]"
; Determines how many body overlays there should be
iNumOverlays=9 ; Default[6]
iSpellOverlays=1 ; Default[1]


[Overlays/Hands] ; "Hands [Ovl#]" and "Hands [SOvl#]"
; Determines how many hand overlays there should be
iNumOverlays=6 ; Default[3]
iSpellOverlays=1 ; Default[1]


[Overlays/Feet] ; "Feet [Ovl#]" and "Feet [SOvl#]"
; Determines how many feet overlays there should be
iNumOverlays=6 ; Default[3]
iSpellOverlays=1 ; Default[1]


[Overlays/Face] ; "Face [Ovl#]" and "Face [SOvl#]"
; Determines how many face overlays there should be
iNumOverlays=6 ; Default[3]
iSpellOverlays=0 ; Default[1] 
