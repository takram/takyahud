yahud-classic
=============

[![screenshot](http://i.imgur.com/gn9O0bv.jpg)](http://imgur.com/a/we1U2)


Floating health is not supported. Add these commands to console/autoexec  
`tf_hud_target_id_alpha 255`  
`tf_hud_target_id_disable_floating_health 1`  

To disable pulsing health bars (low/buffed, navigate to custom/FLV (BLU)/scripts/ and rename HudAnimations_tf-NOPULSE.txt to HudAnimations_tf.txt, overwriting/delete the other.

For the bonus health cross, rename resource/ui/HudPlayerHealth - CROSS.res to HudPlayerHealth.res (overwriting or placing the previous file elsewhere).

To regain the team-colored triangle in the bottom right corner, go to resource/ui/HudPlayerHealth.res, search for "tri" and set "visible" from 0 to 1.
