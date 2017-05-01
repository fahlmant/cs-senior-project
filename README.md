Noctilucent VR combines Potree Viewer with WebVR to enable stereoscopic and VR view of point cloud data.
Lidar point clouds are a collection of points that are collected by bouncing light off objects to
determine its position in 3D space.  


With an OSVR-compatible device:

1) Download the following Chromium zip and unpack it:
https://drive.google.com/file/d/0BzudLt22BqGRRlVjSUZpV3ZsVzA/view?usp=drive_web

2)Select the "Enabled" option from the drop-down menu for the "Enable WebVR" flag (enter chrome://flags/#enable-webvr in the URL bar) and the "Gamepad Extensions" flag (enter chrome://flags/#enable-gamepad-extensions in the URL bar), or launch Chromium from the command line with the --enable-webvr and --enable-gamepad-extensions flags.


3) Download OSVR, and set up headset with OSVR (Needs more information)
4) Use some webserver (i.e. Apache, XAMPP, etc.) to server the VR site
5) Visit index.html, expand the sidebar, and select Other Settings > Enable VR
6) At the bottom of the page, select Start VR
7) Use your headset to view the point-cloud

Without device:

1) Follow steps 1 and 2 above
2) Install the following Chrome extension https://chrome.google.com/webstore/detail/webvr-api-emulation/gbdnpaebafagioggnhkacnaaahpiefil?hl=en
3) Follow steps 4 through 6 above
4) Your display in your browser should now be in stereoscopic view. 
