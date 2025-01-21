# Gig-Performer

Scripts, rackspaces, panels, overlay templates and other [Gig Performer](https://gigperformer.com/) customizations. See GP forum links for descriptions and discussions.

## Gig files

- **GlobalLinkPoc.gig** is a template that controls rackspace widgets from global rackspace.

    *Descriptions:*

  - [GP forum link for the full version]()
  - [GP forum link for initial idea](https://community.gigperformer.com/t/one-hardware-controller-many-racks-dynamically-linked-template-gig/20563)

  *Instructions:*

    - Enable OSC in Gig Performer settings.
    - Copy contents of [Scripts](https://github.com/vangrieg/Gig-Performer/tree/main/Scripts/) to your Gig Performer Scripts folder. Here's a [zip archive](https://github.com/vangrieg/Gig-Performer/blob/main/bin/globallink.zip) with all the files.
    - If you want to adapt this to your actual gig file with rackspaces, you will need to:
      - Add the provided [GolbalLink Panel](https://github.com/vangrieg/Gig-Performer/blob/main/Panels/GlobalLink.gppanel)
      - Add rackspace scripts. You can use the scripts in the gig file as examples and modify them, or use the [template](https://github.com/vangrieg/Gig-Performer/blob/dev/Scripts/templates/gl_rs_template.gpscript) from the Scripts/templates folder. If you have/know how to use tools like Github Copilot, after declaring the widgets it can be a 5 minute affair.

- **SyncWidgets.gig** is a template that programmatically creates widget groups. Check out the [GP forum link](https://community.gigperformer.com/t/assignable-widget-groups-with-a-gig-file-and-examples/20754) to see what this does.

<!-- ## Rackspaces

- [NDSP Cory Wong X]() (coming soon)
- [NDSP Petrucci X]() (coming soon)
- [NDSP Tom Morello]() (coming soon)
- [Global rackspace]() (coming soon) -->

## Panels

- [GlobalLink Panel](https://github.com/vangrieg/Gig-Performer/blob/main/Panels/GlobalLink.gppanel). Add this to your Global Rackspace for the GlobalLink scripts to work in your own gig file. Also add the [global rackspace script](https://github.com/vangrieg/Gig-Performer/blob/main/Scripts/gl_global_rack.gpscript).

## Scripts

- [Includes for GlobalLink](https://github.com/vangrieg/Gig-Performer/tree/main/Scripts/includes), required for the GlobalLink script to work.
- [AutoLoad](https://github.com/vangrieg/Gig-Performer/tree/main/Scripts/AutoLoad), required for most scripts to work.
- [Global rackspace script](https://github.com/vangrieg/Gig-Performer/blob/main/Scripts/gl_global_rack.gpscript) saved separately if you want to adapt it for your gig.
- [Gig script](https://github.com/vangrieg/Gig-Performer/blob/main/Scripts/gl_gig.gpscript) saved separately if you want to adapt it for your gig.
- [Rackspace script template](https://github.com/vangrieg/Gig-Performer/blob/main/Scripts/templates/global%20link%20rack%20template2.tmp) to make configuration of your gig file easier.

## Overlay templates for controllers

There are editable Photoshop files, printable pdfs, and image files for reference. Also, Nanokontrol overlay doesn't fit on A4, so there's also a printable pdf where the overlay is split in 2 parts so you can print it at home.

- [X-Touch Mini](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Overlays/X-Touch%20Mini)
- [Korg Nanokontrol 2](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Overlays/Nanokontrol%202)

## Controller settings

- [.bin files for X-Touch Mini](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Settings/X-Touch%20Mini) that work with the Global Link scripts. Download the X-Touch Editor [here](https://www.behringer.com/product.html?modelCode=0808-AAF) and upload to your X-Touch Mini for the GlobalLink scripts to work with the controller.
- [.nktrl2_data file for Korg Nanokontrol 2](https://github.com/vangrieg/Gig-Performer/blob/main/Controllers/Settings/Nanokontrol%202/nanokontrol2%20default.nktrl2_data). Download Kontrol Editor [here](https://www.korg.com/us/support/download/software/1/133/1355/).

### Credits

- The overlay template for X-Touch Mini is based on [this template for Lightroom](https://drive.google.com/uc?export=download&id=1ETpBydF9yPbNrgkYw7VU5eQ0otGsZAkH) I found on the internet.
- The overlay template for Nanokontrol is based on [this template](https://community.gigperformer.com/t/nanokontrol-2-skin-template-for-you/13095) from GP forum.
