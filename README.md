# Pic Plane

[Pic Plane][app] is an augmented reality app for iOS that lets you explore a unique take on photography. You can use Pic Plane to compose spatial collages from your environment or as a photographic tool that lets you manipulate perspective in a new way. The app is [available for free in the app store][app].

This repo provides documentation on using Pic Plane. If you run into any issues or have a feature requests, you can also [file an issue][issues] here.

![Pic Plane in action](images/overview.gif)

## Using Pic Plane

### Placing a photo plane

Pic Plane works a little differently than your typical camera app. To get started, you first to place a photo plane in the world using augmented reality. This photo plane will be used to both take photos and display the captured images.

When the app starts, you should already be in plane placement mode. Position the purple plane in your environment using the provided controls. Once you position the plane where you want to, hit the checkmark. You can always return to reposition the plane again later.

Use the following controls to position the plane (left-to-right):

![Placement controls](images/placement-controls.png)

- Tracking mode. When enabled, the plane will follow your current view. Tap again to disable.

- Translate. Tap and drag to move the plane from side to side and forward and back. Use two fingers to move the plane up and down.

- Rotate. Tap and drag to rotate the plane in space. Use two fingers to spin the plane. 

You can also pinch to scale the plane up and down.

> 💡 **Suggestion**: Try using tracking mode to quickly position the plane, then refine its position using the translate and rotate tools.

### Capturing images to the photo plane

After placing the photo plane, now it's time to capture images using it. When you take a photo, Pic Plane will save the view through the current picture plane. 

Using your placed plane, frame a good looking shot using it and then tap the camera button in the bottom bar to capture an image.

![Camera button](images/camera-button.png)

If you stand still, the plane should now perfectly blend into the scene. Step to the side to see that the image has in fact been saved to the plane.

> 💡 **Suggestion**: After capturing an image, you can always return to edit mode to move the plane about. The captured image will stay on the plane until you reset the plane or take another photo.

Try experimenting with capturing images of the plane from different angles. You can also explore perspective. Notice how if you capture the plane from a heavy angle for example, the plane image will look heavily distorted when viewed head-on.

![Images captured at an angle will look distorted when viewed head-on](images/distortion.png)

> 🎵 **Note**: Remember that the captured image depends on your phone's view of the plane. If the plane is very small on your display, the captured image will be quite low resolution. 

> 🎵 **Note**: Any areas of the plane that are not visible when you take a photo will be transparent.

### Working with multiple planes

To place additional planes, just tap the plus button. This lets you place a new plane in the scene using transform mode.

> 🎵 **Note**: The free version of the app lets you place up to three photo planes in the world. The pro version lets you place an unlimited number of planes.

The currently active plane is always highlighted in purple. Transforms and camera operations will only effect the active plane. To change active planes, simply tap the plane you wish to switch to.

### Taking Screenshots

After putting together fun collage, tap the circular photo button to capture a screenshot. This screenshot hides all UI elements so that you only see the current scene and your placed planes.

![The photo button](images/photo-button.png)

Tap and hold the camera button to start recording a video. This starts a countdown, with recording starting after three seconds. Tap the camera button again to stop recording. 

After taking a video or screenshot, you can download it to your photos or share it using the standard iOS share sheet.

![Sharing a screenshot](images/sharing.png)

### Export Plane Image

You can also export the image from a captured plane. To do this, go to the advanced menu in the far right of the control bar and select `Export Plane Image`.

![Exporting a plane image](images/export-plane-image.png)

Again keep in mind that resolution of the image originally captured to the plane may be limited. This is especially true for highly distorted images.

> 🎵 **Note**: The free version of the app is limited to fairly low resolution images. The pro version of the app supports exporting plane images up to 4048x4048px


## Pro Upgrade

I try to release free iOS apps that have a lot functionality and don't have ads or other BS. You can support this by upgrading to the Pro version of Pic Plane. The pro upgrade also unlocks some additional benefits: 

- Place an unlimited number of photo planes.

- Export plane images up to 4096x4096px in size (note that this becomes rather slow on older phones)

## Feedback

Enjoy using Pic Plane? Be sure to tell your friends about it and share anything content you create using the app. If you are feeling especially generous, please also write an App Store review. This really helps other people find the app.

Run into a bug or want to request a new feature? Just [file an issue][issues]!

[app]: https://apps.apple.com/us/app/pic-plane/id1550562229
[issues]: https://github.com/mattbierner/pic-plane-support/issues
