# Gameplay preview

`fighter-rockets.gif` and `fighter-gau.gif` pair the pilot's view with a ground
observer at TEST-1 on Trijent. `fighter-weapons-clean.gif` contains the complete
12-second sequence. Each shows actual weapon releases and their corresponding
ground impacts, cropped together without captions, borders or added effects.

These recordings use the gameplay code from PR #2011's passing commit
`48dd169d62d60aa065223ea3de4f46e69d7c45d3`. Local capture staging selected the first
target, set near-stall speed, queued rockets followed by the GAU, and captured
both perspectives. Those staging edits are not part of the gameplay changes.
Frames are paired using game timestamps and encoded at 10 fps; the pilot's
capture has fewer unique frames than the ground recording.

## Earlier preview

`fighter-weapons.gif` pairs the pilot view with the WSO camera from actual Trijent
gameplay captures. Missile release and impact are followed by a GAU burst and its
impact site. Frames are cropped, resized and labelled, with no generated combat
imagery. Corresponding crew frames are paired by their recording sequence.

The footage was recorded before the final AO-motion and heading corrections.
No additional session was launched after the request to open the PR without tests.
