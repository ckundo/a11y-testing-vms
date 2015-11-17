# Test screen reader accessibility with IE on OS X
How to configure a VirtualBox Windows VM for testing accessibility on OS X

## Host machine setup

### VirtualBox

1. Download and run the [VirtualBox installer](http://download.virtualbox.org/virtualbox/5.0.10/VirtualBox-5.0.10-104061-OSX.dmg).

### Windows image

1. Download the latest version of Windows/IE from <https://dev.windows.com/en-us/microsoft-edge/tools/vms/mac/>.
2. Unarchive and open the VM image in VirtualBox.

## Virtual machine setup

### NVDA

1. Download and open the [NVDA screen reader installer](http://www.nvaccess.org/download/).
2. Change the default voice: 
  - Choose the NVDA item from the Notifications menu in the Windows taskbar and choose Preferences > Synthesizer > Microsoft Speech API <latest version>
3. Change the modifier key to capslock (by default it's numpad insert and extended insert):
  - Choose the NVDA item from the Notifications menu in the Windows taskbar and choose Preferences > Keyboard Settings
  - Select "laptop" from the keyboard layout dropdown
  - Check the box "Use CapsLock as an NVDA modifier key"
4. Review the user guide for [instructions on navigation](http://www.nvaccess.org/files/nvda/documentation/userGuide.html?#toc29) and start visiting content. (hint: capslock + down arrow will get the NVDA cursor focus moving about and announcing web content)

## Protips
- wear headphones when using screen readers.
- shift key pauses speech in NVDA.
- Save a snapshot of the VM to revert to when the Windows license expires.
