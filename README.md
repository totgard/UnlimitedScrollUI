# Unlimited Scroll UI

## Summary
A plugin in Unity that let you easily create scroll views with unlimited items. See in [asset store](http://u3d.as/2z2a).

## Quick Setup
**Step 1:** Add “UI/Scroll View” from Add GameObject menu.  
<img src="./Tools~/DocFx/images/1.png" width=400>

**Step 2:** Add UnlimitedScroller with your desired auto layout type.  
<img src="./Tools~/DocFx/images/3.png" width=400>

**Step 3:** Drag and drop the scroll view to `Scroll Rect` field. Set initial cell cache count.  
If you use grid scroller, you can also change its alignment.  
<img src="./Tools~/DocFx/images/4.png" width=400>

**Step 4:** Prepare a cell prefab that has the `RegularCell` script or your custom script that implements the `ICell` interface.  
<img src="./Tools~/DocFx/images/5.png" width=400>

**Step 5:** To test it out immediately, add a `ScrollerTest` script below `Unlimited Scroller`, reference to your cell and set total count.  

