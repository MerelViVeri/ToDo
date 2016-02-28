# ToDo

For some reason the saving of the app's state and resuming after closing works on my emulator but not on my actual phone.
Due to time constraints (and a certain amount of "screw this I'm so done with this stuff") I left it this way.
Saving state on orientation change works however.
The striking through of items is not fully implemented yet (but also a healthy amount of "screw this" was involved):
it does strike items through on simple click, but upon removing an item above, it accidentally strikes through the item
that takes its place on the list. Upon removal of all items, sometimes the top item is striked through when added anew.
The striking through is not (yet) undoable, since I didn't have any energy left to find out how I could add booleans to
individual items.
