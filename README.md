# Trackpoint-windows-gestures

Short code used to add trackpad window gestures to trackpoint
Using AutoHotKey just the AHK script i use to add gestures in as i couldnt find any solution elsewhere.

Not planning to do anything with this as it works well for me.


Description
=== Holding Middle BUTTON GESTURES ===

ON DESKTOP (drag middle button):
→ Right: Next virtual desktop (Win+Ctrl+Right)

← Left: Previous virtual desktop (Win+Ctrl+Left)

↑ Up: Task View (Win+Tab)

↓ Down: Show Desktop (Win+D)

IN APPLICATIONS (drag middle button):
Vertical: Scroll up/down
Horizontal: Scroll left/right

HOTKEYS:
Win+Ctrl+±: Adjust scroll sensitivity
Win+Ctrl+0: Show current sensitivity
Win+Ctrl+G: Show gesture threshold
Win+Ctrl+T: Toggle debug mode
Win+Ctrl+S: Save settings
Win+Ctrl+R: Reload script
Esc: Cancel ongoing gesture

CURRENT SETTINGS:
Threshold: " gestureThreshold " pixels
Sensitivity: " Round(scrollMultiplier * 100) "%
Power: " powerStatus " (Polling: " pollingSpeed "ms)

TIPS:
• Drag slowly for precise scrolling
• Drag quickly for desktop gestures
• Settings auto-save on adjustment
