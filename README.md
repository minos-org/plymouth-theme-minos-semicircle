## About

[Plymouth](http://en.wikipedia.org/wiki/Plymouth_(software)) is the application which provides the graphical "splash" screen when booting and shutting down a Minos system. 

<p align="center">
<img src="https://raw.githubusercontent.com/minos-org/plymouth-theme-minos-semicircle/master/plymouth-minos-semicircle.gif" alt="minos-semicircle-theme"/>
</p>

## Quick start

### On Ubuntu (only LTS releases)

1. Set up the minos archive:

   ```
   $ sudo add-apt-repository ppa:minos-archive/main
   ```

2. Install:

   ```
   $ sudo apt-get update && sudo apt-get install plymouth-theme-minos-semicircle
   ```

3. Enjoy ☺!


### On other Linux distributions

1. Type `sudo mkdir -p /lib/plymouth/themes/minos-semicircle/`

2. Copy files `sudo cp *png *.plymouth *.script /lib/plymouth/themes/minos-semicircle/`

3. Set the default theme and rebuild the initramfs file `plymouth-set-default-theme -R minos-semicircle`

## Feedback

Please drop me an [email](mailto:m@javier.io) with your suggestions or open [an issue](https://github.com/minos-org/plymouth-theme-minos-semicircle/issues) with your comments.
