## 1.2.1

- Added Sort Mode picker to the header. Launchie can now sort apps by name, newest, oldest, A-Z, Z-A, and most used.
- Added Spanish translations.
- Launchie now opens on the screen where the mouse is located, when using mulitple screens.
- Window size control is now a precise slider (40%–90%) for fine-grained adjustments.
- Added folder spacing controls to disable empty slots, instantly close gaps, and explain how free icon placement works.
- Fixed a bug where the app would crash when opening a folder with more than 52 apps.


## 1.2.0

- Added font customization for app and folder names in grid view (including Quick Access section) with three size options (Small, Normal, Large), three font styles (System, Rounded, Monospaced), and a bold text option.
- Added most used apps to the quick access section.
- Added Quit App button to the settings.
- Added General → Language selector with Auto (system), English, German, and Dutch options.
- Localized App (English, German, Dutch). Please report wrong translations or missing translations. If you want Launchie to support your language, please contact me.
- Inside of folders, apps can now freely arranged in the empty space.
- Improved drag scroll functionality
- New App Icon
- Added Backup and Restore functionality for settings, hidden apps, and custom directories.


## 1.1.5

- Fixed a bug where hidden apps would still show inside folders. Hidden apps are now properly filtered from folder contents and folder preview icons.
- Fixed a bug in List View where folder app counts showed double the correct number when folders contained hidden/uninstalled apps.
- Now the app launches on click on the app icon. Previously it would launch in the background and you would need to click on the app icon again to launch the app. Starts at Login without showing the overlay as before.
- Tinted Window Background slightly for better appearance.
- Added Appearance Mode setting to the settings.
- Moved Settings button to the header next to Add Folder button
- Moved Grant Access to User App Folder functionality from header to App Directories settings section
- Renamed "Custom Directories" to "App Directories" in settings
- Added view mode toggle button next to search bar for Grid/List view switching
- Improved search bar: now starts as a collapsed button, expands on click or when typing, auto-collapses when cleared
- Fixed search button sizing to match other header buttons
- Fixed header layout alignment to keep buttons properly positioned when search is collapsed or expanded
- Fixed a bug where you could type while in a folder and the folder content would be replaced by the global search results.

## 1.1.4

- Fixed a bug where the app would always show the get pro button in the footer of the window.

## 1.1.3

- Added Custom Directories section to the settings
- Improved Layout

## 1.1.2

- **Major UI Redesign for App Store Differentiation**
- Added left sidebar with view mode switcher (Grid/List)
- Added List View mode - new way to browse and launch apps in a vertical list
- Full-width search bar for better usability
- Settings button moved to sidebar
- Significantly differentiated UI from macOS Launchpad

## 1.1.1

- Added Quick Access section to the app, which shows the recently used and newest apps.

## 1.1.0

- Redesigned search bar: Now narrower and centered in the button row, like the original macOS Launchpad
- Added "Show Hotkey Display" setting to hide the keyboard shortcut reminder once you've learned it
- Added ability to drag and drop between apps and folders
- Added animations when items are moved
- Improved "Close on Background Click" behavior: Now closes only the currently open folder (if any) instead of the entire app
- Improved Esc key behavior: Now follows hierarchical closing (folder → modal → app) for more intuitive navigation
- Background clicks and Esc key now behave consistently with the same hierarchical priority
- Click on dock icon now closes Launchie if it is open
- Hide Settings button in folder and search mode
- Hide New Folder button in folder and search mode
- Improves the Layout of the header
- Fixed Keyboard Navigation
- Improved Settings Sidebar, prev. you would need to click exacly on the text to select it, now you can click on the whole row to select it
- Added Launchie Website to the settings
- Added Auto Refresh setting to the settings

- Added Pro Version with additional features, which is only available on the App Store Version. More features will be added in the future at no additional cost.

- Pro Features:
- Change Window Size
- Hide Apps
- Send to Position Context Menu
- Folder Colors
- Custom Grid Columns (5-8 columns)
- Custom Icon Size (Small: 60px, Medium: 80px, Large: 100px, Extra Large: 120px)

## 1.0.13

- Fixed issue where FolderExitDropZone would remain visible after unsuccessful drag operations
- Fixed FolderExitDropZone: Now properly handles drops next to (not on) the drop zone
- Added visual feedback to FolderExitDropZone: Green border and icon when hovering over it
- Disabled drag and drop operations in search mode for better UX (search results are dynamically filtered)
- New folders now appear at the start instead of the end
- Fixed issue where you couldn't directly type in the search field after opening the window
- Added little subtext to "create folder" interface - clarifying that folders exist only in Launchie and not in Finder
- Added ability to disable the global keyboard shortcut completely via "Clear" button in settings
- When hotkey is disabled, app can still be opened via menu bar, dock, or automation tools like Keyboard Maestro
- Added Clear button to hotkey settings to disable the global keyboard shortcut
- Added new "Danger Zone" section in settings with ability to reset Apps folder permission
- Reset Apps folder permission allows you to clear the saved bookmark if you accidentally granted access to the wrong folder
- Added "Close on Background Click" setting to close Launchie when clicking empty space between icons (like classic Launchpad)
- "Close on Background Click" is disabled by default but useful for fullscreen mode users

## 1.0.12

- Better Settings UI
- Improved Startup Time
- Showing window and hiding window animations respect animations settings now
- Fixed Launch at Login: Now it's working as expected
- Improved Icon Animations

## 1.0.11

- Added Start at Login option in the settings.
- Refactored a lot of the codebase to be more modular and easier to maintain
- Added Animations when window is opened and closed
- Added Animations when items appear in the window
- Added Settings for Animation Level of the items

## 1.0.10

- Fixed an issue where the app order was not being saved when you create a new folder.
- Localized app names
- Mouse back button works now for going back from folder to root level
- fixed grant user appfolder permission button
- fixed an issue which causes the root level order to get scrambled when you dismissed the app while beeing in a folder.

## 1.0.9

- Fixed an issue that was causing the app order to be scrambled when you install or uninstall an app.
- Fixed an issue where the window couldn't be reopened when it was closed by clicking outside of it.
- Added a add to dock helper in the settings and the menu bar.
- Added "Open in Finder" to the app context menu.

## 1.0.8

- Fixed Folder Creation and Rename: Enter and Escape now work as expected
- Improved Global Search: Now shows all apps and folders with visual context indicators
- Added Search Restoration: Search query is preserved when entering and exiting folders
- Added App Reordering in Folders: Apps within folders can now be rearranged via drag and drop
- Fixed Folder Icon Preview: Folder icons now show apps in the correct custom order
- Added Folder Preview Settings: Choose between 4, 9, or 16 app icons in folder previews
- Redesigned Settings UI: More professional and unified appearance with better visual hierarchy
- Fixed Settings Layout: Larger window size and improved spacing to prevent text wrapping issues
- Improved Drag & Drop Targeting: Extended invisible hit areas to the left of icons for easier dropping, plus direct icon dropping still works
- Added Hover Indicators: A subtle visual indicator appears when hovering over items during drag and drop operations
- Added App Context Menu with Send to Folder function.

## 1.0.7

- Added drag scroll functionality
- Minor improvements

## 1.0.6

- Fixed Text Size under App Icons
- Added real Fullscreen Mode, now we got Windowed, Maximized and Fullscreen
- Icons fading out on top and bottom of the window
- Changed the Icon (Apple refused the old one, it looks to similar compared to their launchpad icon)
- Now shipping .dmg instead of .app
- Added Update Notifier in Settings

## 1.0.3

- Fixed a lot of issues with performance and some minor bugs.

## 1.0.0

### What's working

- CMD + Shift + Space to Open/Close
- Setting custom hotkey
- Esc to Close
- Drag and Drop to reorder apps
- Open Apps
- Folders
- Search
