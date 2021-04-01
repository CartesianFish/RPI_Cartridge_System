# RPI_Cartridge_System
Using a RPI 4 to USB host a USB device RPI 0W


This project is simple in theory, but a little harder in pracice.
I want to make a Cartridge era, Nintendo sytle, RetroPie system. Instead of having a seperate game for each cartridge, I want to have a seperate user for each cartridge. This
isn't meant to be expensive and wasteful, which is why I have gone this route. The Raspberry Pi 0W based cartridges are to hold a users roms, which they own and can legally have a
single digital copy, and have said ROMS and save files backup via a home GIT server. This is so multiple devices can have the same user cartidge and have it backed up to said GIT
server. The main exmple is having a 'desktop' RetroPie system and a handheld system to have the same progress and roms you own without the need to be in the same place. So if I
get stuck on a certain gym in Pokemon Yellow, I can tell the RPI 0W cart to push the the git server and my Significant Other or Childhood Friend could pull from the server, finish
off the gym for me, push to the server, and I can pull fron the server and continue playing as usual.


The extent of what is being pushed and pulled to and from the server is up to the users. The two main possibilities are to have the entire system drive on the USB portion of the
cartridge and have the host RPI boot off of USB, or have only the directory that contains the roms and save files on the cartridge and have the Host RPI look for said ROMS and
savefiles on the USB attached RPI 0W. I will try to make system images of both and provide the installer to the offical Raspberry Pi Imager as well as the host website.


I will be making CAD files to 3D print, and upon request I will provide source CAD files. I will also be providing a list of printer settings that are specific to this project's 
prints. All CAD files will be made to be printed natively on my modified Ender 3 Pro, so SLA printing will not be supported unless I get one for myself/family. Post processing
such as painting, sanding, actetone smoothing, and ironing(Cura feature to smooth the top of prints) may not be natively supported unless specifically noted.


All ROMs be acuired legally and on your own. I will not be responsible for the ROMs any user has and how they got them. This project is intended to use ROMs you can legally own.
For instance, if I own Super Mario 64, I can own a digital ROM copy to use by myself. If I were to ask a friend for help, they to would need to own Super Mario 64 so that they can
legally pull from my home GIT server and help me get past a certain point in the game. This is not my rules, but the law as of the moment of typing this. I can't be repsonsible
for it being different in your home region and different over time. Please check that you ar obeying the law in your location and time.


I ask that you be patient with me as I work on this project. This is my first public project and I also have a multitude of responsibilities that I have to tend to, so progress
may be slow or often delayed.
