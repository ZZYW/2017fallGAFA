## AR Workshop

### 1. Create new unity project

### 2. Build Settings==> Player Settings to activate Vuforia AR support under the "XR Settings" section

### 3. Build AR Scene integration

0. Import the Vuforia plugin and your image database into Unity.

1. In the Vuforia folder, click and drag the ARCamera prefab into the hierarchy.

2. Find the imageTarget prefab in the same folder and drag it into the hierarchy as well.

3. Pick an image target. Printable target PDFs can be found in /Editor/Vuforia/ForPrint

4. Create a simple 3D shape.

5. Drag it onto the ARCamera prefab (making it a child).

6. Play your scene and you should see the 3D shape showing up on top of the image tracker. 


### 4. Adding your own target

0. Register as a Vuforia developer

1. Get an app License Key and add it to your project at ARCamera==>Open Vuforia Configuration==>App License Key

2. Upload images to the Target Manager

3. Download Image Database

4. Load image database into Unity

5. Switch to your custom database and image target


### 5. Export your AR experience into an Android or IOS application. 