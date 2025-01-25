# Uncommon HTML Bug: Incorrect Event Listener Attachment

This repository demonstrates a subtle bug in HTML related to event listener attachment.  While the provided code works in many browsers, it's not the standard or recommended approach. This can lead to inconsistencies or difficulties in more complex scenarios. The solution showcases the proper usage of `addEventListener`.

**Bug:** The original code incorrectly uses direct assignment (`onclick = function() { ... }`) instead of `addEventListener`.  While functional, this method is less flexible and can overwrite existing listeners.