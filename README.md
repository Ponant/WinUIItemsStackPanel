# ItemsStackPanelUWPBug
https://stackoverflow.com/questions/59850251/itemsstackpanel-extends-beyond-grid-container-for-a-large-source
This example for WinUI shows a worse behavior than for UWP, posted here https://github.com/Ponant/ItemsStackPanelUWPBug

The example shows how a ListView where Items extend beyond the Grid containing the ListView whenever
the number of items is too large (beyond 30000 items in our case).
Look at the ctor and increase or decrease the loop length.
In addition to the UWP case, in WinUI, scrolling is strongly affected.
