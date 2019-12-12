# NavigationView
NavigationView for Android with similar attributes to UWP NavigationView. Properties are similar in name.

Properties:<br />
**paneDisplayMode** defaults to "Auto". Can be {"Top", "Left", "LeftCompact", "LeftMinimal", "Auto"}<br />
**compactModeThresholdWidth** defaults to 480dp<br />
**expandedModeThresholdWidth** defaults to 840dp<br />
**compactModeWidth** defaults to 60dp. TODO: should be 56dp or 64dp same as Toolbar size.<br />
**expandedModeWidth** default is 5 * compactModeWidth.<br /><br />

# Simple Example<br />
BottomNavigationView enabled for < w600dp<br />
NavigationView paneDisplayMode="Auto" for >= w600dp<br /><br />
Phone
<p align="left">
  <img src="screenshots/phone_portrait_bottomnavigationview.png" width="200"/>
  <img src="screenshots/phone_landscape_navigationview.png" height="200"/><br />
</p>

Small Tablet
<p align="left">
  <img src="screenshots/tablet_small_portrait.png" width="200"/>
  <img src="screenshots/tablet_small_landscape.png" height="200"/><br />
</p>

Large Tablet
<p align="left">
  <img src="screenshots/tablet_large_portrait.png" width="200"/>
  <img src="screenshots/tablet_large_landscape.png" height="200"/><br />
</p>
