video-conferencing by animating selfie pictures on live camera

This is an upgraded version of Avatarify Python created by Ali Aliev(alievk) which can be used on whatsapp, instagram, telegram, and the defualt apps the previous version worked for which requires manually downloading and installing some dependencies, and is therefore best suited for users who have some experience with command line applications. To use kit caller, follow the instruction below

go to this google drive link to download and install the apps except the vox-adv-cpk.pth.tar file( you dont have to install the vox-adv-cpk.pth.tar cause its a file, not a software) https://drive.google.com/drive/folders/1JNqA8H82iiLJjSa6dV7Ci8VfKRHCTLnd?usp=share_link NOTE: while installing obs virtual cam, Choose Install and register only 1 virtual camera.

After you've installed the softwares, Press Windows button and type "miniconda". Run suggested Anaconda Prompt Then copy-paste these commands into your miniconda

   git clone https://github.com/Kitopvibe1/kit-caller.git && cd kit-caller && scripts\install_windows.bat

then wait for some minutes for it to finish installing after its done, move vox-adv-cpk.pth.tar file in the kit-caller directory (don't unpack it).

Go back to miniconda and pastes this command" run_windows.bat " If installation was successful, If installation was successful, four cameras will appear, choose camera 0...then another one camera will appear again, press x on your keyboard.....then two windows "cam" and "avatarify" will appear. Leave these windows open for the next installation steps will appear. Leave these windows open for the next installation steps.

Run OBS Studio. In the Sources section, press on Add button ("+" sign), select Windows Capture and press OK. In the appeared window, choose "[python.exe]: avatarify" in Window drop-down menu and press OK. Then select Edit -> Transform -> Fit to screen.

In OBS Studio, go to Tools -> VirtualCam. Check AutoStart, set Buffered Frames to 0 and press Start. Now OBS-Camera camera should be available in Zoom (or other videoconferencing software)