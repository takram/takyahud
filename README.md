yahud-classic
=============

[![screenshot](http://i.imgur.com/wKNLOvE.png)](http://imgur.com/a/we1U2)


Add these commands to console/autoexec if you play without floating health
`tf_hud_target_id_alpha 255`  
`tf_hud_target_id_disable_floating_health 1`  

If you choose to use floating health, I still recommend typing `tf_hud_target_id_alpha 255` in console. To center the names, open resource/ui/TargetID.res, find "TargetNameLabel" and change "textinsetx" "1" to "textinsetx" "10"

To disable pulsing health bars (low/buffed, navigate to custom/FLV (BLU)/scripts/ and rename HudAnimations_tf-NOPULSE.txt to HudAnimations_tf.txt, overwriting/delete the other.

For the bonus health cross, rename resource/ui/HudPlayerHealth - CROSS.res to HudPlayerHealth.res (overwriting or placing the previous file elsewhere).

To regain the team-colored triangle in the bottom right corner, go to resource/ui/HudPlayerHealth.res, search for "tri" and set "visible" from 0 to 1.
