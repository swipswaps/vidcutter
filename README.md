<div style="width:100%; height:120px; position:relative;">
    <div style="float:left; position:absolute; left:10px;">
        <p><img src="https://travis-ci.org/ozmartian/vidcutter.svg?branch=master" /></p>
        <p><b>Homepage:</b> <a href="http://vidcutter.ozmartians.com" target="_blank">http://vidcutter.ozmartians.com</a></p>
    </div>
    <div style="float:right; right:10px; position:absolute;">
        <img src="https://raw.githubusercontent.com/ozmartian/vidcutter/master/data/icons/vidcutter.png" width="120" height="120" />
    </div>
</div>

<hr noshade size="1" />

### Windows Users

Native installers for Windows are available on the releases page with every new version, or just click the button below. 

<p style="text-align:center;"><a href="https://github.com/ozmartian/vidcutter/releases/latest"><img alt="Latest Release" src="http://tvlinker.ozmartians.com/images/button-latest-release.png" style="max-width:100%;"></a></p>

### Linux Users

Arch Linux users can install directly from AUR, package is available in both stable and git-latest versions:

    AUR: vidcutter, vidcutter-git

Ubuntu/Mint and all other Ubuntu derivatives (basically any distributtion supporting Ubuntu PPAs) can install the latest release via:

    ppa:ozmartian/apps

If you are new to PPAs then just issue the following commands in a terminal:

    sudo add-apt-repository ppa:ozmartian/apps
    sudo apt-get update
    sudo apt-get install vidcutter
    
An AppImage version is also available on the releases page to help all other Linux users.

If you're familiar with Python and PyPi then you can always try that option too but avoid installing PyQt5 from through pip and instead run with your distributions own PyQt5 offering. PyQt5 is known as some of the following names under various distros: python-pyqt5, python3-pyqt5, python3-qt5 etc. Using your distro's version ensures a more seamless look & feel with the app integrating with your distro's look & feel + widget sets. Installing all via PyPi will still work, but won't look as nice..

If installing via PyPi, be aware to also ensure you have the following tools also installed via your package manager or any other means it doesn't matter so long as they are installed:

    - libmpv (Arch: mpv, Ubuntu: libmpv1, Fedora: mpv-libs via RPMFusion, openSUSE: libmpv1)
    - FFmpeg (ffmpeg in all places, if on older Linux then you may have libav-tools instead which will also work)
    - mediainfo (mediainfo in all/most places. mainly needs to be the CLI version)

Fedora and RedHat users need to enable the RPMFusion repository in order to access mpv packages and just about anything multimedia-wise. Chances are you know what I'm talking about here but if not here are some simple steps to get VidCutter working in Fedora 25, the same should apply for any other RPM based distro... until I get off my lazy butt and try to learn RPM packaging (oh how horrible it looks though).... if anyone wants to help in this area by all means do!

## Fedora 25 Installation Walkthrough

 
