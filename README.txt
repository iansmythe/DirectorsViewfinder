ROOM 155 — DIRECTOR'S VIEWFINDER

FILES
  index.html            the app (everything in one file)
  manifest.webmanifest  lets Chrome install it as a full-screen landscape app
  sw.js                 offline cache
  icon-192.png, icon-512.png

GALAXY S25
The camera only works over HTTPS, so host the folder once:
  Option A (fastest): app.netlify.com/drop → drag the room155 folder in → open the https:// link on the phone.
  Option B: new GitHub repo → upload the files → Settings → Pages → deploy from main.
On the phone, open the link in Chrome → ⋮ → Add to home screen → Install.
Launch from the icon, tap Start viewfinder, allow the camera. It opens full screen in landscape.

FIRST-TIME CALIBRATION (do once per camera lens)
Panel → Calibrate field of view. Stand square to a wall at e.g. 2.00 m, mark where the
yellow edge markers fall, measure between the marks, enter both numbers, Apply.
The S25 main-lens preset (72.5° horizontal) is used until you do this.
For focal lengths wider than ~24 mm, switch the camera to the ultrawide in Calibrate
and pick or measure its preset.

WINDOWS PC
Double-click index.html (Chrome or Edge). Tap "PC test" (top right) and choose:
  Webcam      – live webcam, calibrate it like the phone
  Test scene  – synthetic 72.5° view with an angle scale; frame edges land on the true half-angle
  Load photo  – a still shot on the phone's main camera

CONTROLS
  Swipe left/right on the image to change focal length continuously.
  Capture frame saves the framed crop (with optional burned-in slate).
  Save frame + notes saves, then advances the shot letter and clears notes.
  Saved frames → tap a frame → Share (gallery, WhatsApp, Drive) or Download.
  Frames and settings stay on the device that captured them.
