# UltimateArsenal
Ultimate Overhaul's weapon expansion
================================================================================
	Binding Keys
================================================================================

Ultimate Arsenal adds the following optional functions to bind:

	"call AmmoToggle" - Swaps primary/alt ammo
	"call SpAtk"  - Perform special action

You can set up new keybinds by entering the following into the console (~ key
in-game) or adding it to your config.cfg file in the game's root directory:

	bind <key> "<command>"

For example, this will bind the ammo toggle function to the right mouse button:

	bind mouse_right "call ToggleMode"

To unbind a key, you can simply remove it from your config.cfg file, or enter
the following into the game's console:

	unbind <key> "<command>"

	------------------------------------

Here are some common key/button names the engine recognizes:

Keyboard
	0-9
	a-z  (must be lower-case)
	f1-f12
	up, down, left, right  (arrow keys)
	lctrl, rctrl
	lshift, rshift
	lalt, ralt
	tab, space, enter

Mouse
	mouse_left, mouse_right, mouse_middle
	mouse_misc1, mouse_misc2  (thumb buttons)
	mouse_wheel_up, mouse_wheel_down

XBox 360 Controller
	joy_0, joy_1, joy_2, joy_3     - A, B, X, Y
	joy_4, joy_5, joy_6            - back, guide, start
	joy_7, joy_8                   - LS, RS
	joy_9, joy_10                  - LB, RB
	joy_11, joy_12, joy_13, joy_14 - dpad up, down, left, right
	joy_15, joy_16                 - LT, RT

For anything I don't have listed here, you can use the in-game menu to bind a
normal function to the desired key, then exit the game and modify the entry in
your config.cfg file to use the new command.
Written by smoke39
Stolen and edited by FairInHeight
