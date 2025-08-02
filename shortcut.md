You can use the Shortcuts app on macOS to create a shortcut that launches League of Legends — and then pin it to your Dock with a custom icon. It’s a cleaner, more visual method 

✅ Here's how to do it:

1. Open the Shortcuts app
  Press Cmd + Space, search “Shortcuts”, and open it.

2. Create a new shortcut
  Click the + button to create a new shortcut.
  
  Name it something like Launch LoL.

3. Add an action
  In the right-hand search bar, type: Run Shell Script
  
  Drag “Run Shell Script” into the shortcut editor.

4. Paste this command into the shell script:
```bash
  cd "/Applications/League of Legends.app/Contents/LoL"
  /Applications/League\ of\ Legends.app/Contents/LoL/LeagueClient.app/Contents/MacOS/LeagueClient
```
5. Test it
  Click the ▶️ Run button at the top to make sure it works.

6. Add to Dock
  Go back to the Shortcuts main screen.
  
  Right-click your new shortcut → Add to Dock.

7. Optional: Change the icon
  Right-click the shortcut in Dock → Options → Show in Finder
  
  Then Cmd + I (Get Info), and paste a custom icon in the top-left corner (drag an image there).

🔥 Why this is awesome:
  No file management.
  Looks cleaner in Dock.
  Supports icons.

You can record it for your YouTube video — looks modern and beginner-friendly!
