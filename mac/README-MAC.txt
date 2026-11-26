Miri Launcher Beta Mac
======================
Made by @9lo.l on Discord.

Install
-------
1. Double-click the Mac download (Miri-Launcher-Beta-Mac.zip) if your Mac hasn't unzipped it already.
2. Drag "Miri Launcher.app" into your Applications folder.
3. Open it once the way described below. After that it opens like any other app.

"Miri Launcher can't be opened" / "Apple could not verify..."
--------------------------------------------------------------
macOS shows this for any app that isn't signed with a paid Apple developer certificate. It
doesn't mean anything is wrong with Miri (see WHAT-MIRI-DOES.txt). To open it:

  1. Double-click Miri Launcher. When the warning appears, click "Done" (or "OK").
  2. Open System Settings > Privacy & Security.
  3. Scroll down to the message about Miri Launcher and click "Open Anyway".
  4. Confirm with your password or Touch ID, then click "Open Anyway" again.

On older macOS versions you can also right-click (Control-click) the app, choose Open, then
click Open in the box that appears.

If macOS says the app "is damaged", open Terminal and run this once, then open Miri again:

  xattr -dr com.apple.quarantine "/Applications/Miri Launcher.app"

Apple Silicon Macs (M1 and newer)
---------------------------------
Miri runs through Rosetta 2 on Apple Silicon. If your Mac asks to install Rosetta the first
time, click Install. This works on every Mac from 2020 on.

Allow Miri to change Roblox (once)
----------------------------------
Visuals and FastFlags are written into the Roblox app. The first time, macOS may say Miri
"was prevented from modifying apps". Open System Settings > Privacy & Security > App
Management, turn on Miri Launcher, quit Miri and open it again.

Adding an account
-----------------
Roblox tab > the + bubble. Miri shows a code. On a phone, tablet or browser where you're signed
in to Roblox (on the same internet connection), go to roblox.com/crossdevicelogin, or in the
Roblox app open Settings > Quick Log In, and enter the code. Then confirm. That's it: Miri never
sees your password. The first time, macOS may ask whether Miri can use your Keychain: click
Always Allow.

What's the same as on Windows
-----------------------------
Accounts with avatars on the ring, PLAY, Studio, Visuals, 30 skyboxes, dark textures, cursor
packs, emote wheels, fonts with live previews, FastFlags, the FastFlag editor with profiles,
Roblox's global settings, and Launcher settings (background, falling snow/leaves/flowers/beach
toys, amount, colours, title bar).

What's different on a Mac
-------------------------
- Sign-in uses a Roblox sign-in code instead of the login window.
- No strap module: Bloxstrap and the other straps are Windows-only.
- The MIRI LAUNCHER title is drawn in flat glass (the throwable 3D letters are Windows-only).
- Roblox updates itself; Miri puts your visuals back afterwards.

This is the first Mac build and it hasn't been tried on a real Mac yet, so please report
anything that doesn't work to @9lo.l on Discord.

Privacy: see PRIVACY-POLICY.txt. Nothing is sent anywhere except Roblox.
