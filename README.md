# node_wrangler_octane
This is the same node_wrangler like in your blender, but with little changes to support octane shaders instead of blenders.

Features so far..:

- viewer node / cntrl+shft+click on any node to add viewer node
- full transform&uwp projectile / select texture node and ctrl+t
- switch-type-to / select node and shift+s
- shader's texture setup for octane / ctrl+shift+t on shader node - https://youtu.be/SON0bUczSf0
- mix shader/textures with hotkeys / ctrl+shift+rmb / ctrl+numpad 0/ etc..

this plugin behave as octane one __only if your renderer set to octane__, you can change renderer to eevee/cycle to work as default one.

Be free to leave any feedback or feature request.

This plugin still can be used with cycle/eevee, it doesn't override any of default methods.

# Installation
__Important: please, disable your node_wrangler before instaling this one.__
Just uncheck it so no conflict will happen.
Install in blender just like any other plugin.

Video example: 
https://www.youtube.com/watch?v=UCu5GEpEkL0

You can download the latest release here(you will need to unzip it to install or just download .py file):
https://github.com/AiSatan/node_wrangler_octane/releases


# Support
Please, let me know if you notice any unexpected behavior/feedback, be free to create an issue, I will try to figure out. 

# Support+
If you feel like spending money to help, any donations are appreciated by this link and will literally make our lives better: https://www.blender.org/foundation/donation-payment/

# Tests
✅ Octane [26.3] - with nw_octane [1.1.6]

✅ Octane [26.4] - with nw_octane [1.2.0]

✅ Octane [26.5] - with nw_octane [1.2.1]

✅ Octane [28.5][TEST] - with nw_octane [1.3.1]
