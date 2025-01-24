<!-- markdownlint-disable MD007 -->
<!-- markdownlint-disable MD033 -->
# Gig-Performer

Scripts, rackspaces, panels, overlay templates and other [Gig Performer](https://gigperformer.com/) customizations. See GP forum links for descriptions and discussions.

## Gig files

- [**GlobalLinkPoc.gig**](bin/globallink_gig.zip) is a template that controls rackspace widgets from global rackspace. As a small little bonus, this also adds tap tempo capability to a footswitch and blinks a LED with tempo (on iRig BlueBoard Bluetooth)

    *Description:*

  - [GP forum link](https://community.gigperformer.com/t/20563)

  *Instructions:*

    - Enable OSC in Gig Performer settings.
    - Copy contents of [Scripts](Scripts/) to your Gig Performer Scripts folder. Here's a [zip archive](bin/globallink_scripts.zip) with all the files.
    - Upload the provided [.bin files](Controllers/Settings/X-Touch%20Mini) to your X-Touch Mini (use the [X-Touch Editor](https://www.behringer.com/product.html?modelCode=0808-AAF))
    - Map hardware knobs and buttons on X-Touch Mini to the widgets on the Global Rackspace.
    - If you want to adapt this to your actual gig file with rackspaces, you will also need to:
      - Add the provided [GolbalLink Panel](bin/globallink_panel.zip) to your Global Rackspace.
      - Add the [Global Rackspace scipt](Scripts/gl_global_rack.gpscript) to your Global Rackspace. You will need to adjust it to your actual effects there if you have any.
      - Add the [Gig script](Scripts/gl_gig.gpscript).
      - Add and adjust rackspace scripts. You can use the scripts in the gig file as examples and modify them, or use the [template](Scripts/templates/gl_rs_template.gpscript) from the Scripts/templates folder. If you have/know how to use tools like Github Copilot, after declaring the widgets it can be a 5 minute affair.

- [**SyncWidgets.gig**](bin/syncwidgets_gig.zip) is a template that programmatically creates widget groups. Check out the [GP forum link](https://community.gigperformer.com/t/assignable-widget-groups-with-a-gig-file-and-examples/20754) to see what this does.

## Rackspaces

- [NDSP Petrucci X](bin/petrucci_x_rack.zip)
<!-- - [NDSP Cory Wong X]() (coming soon)
- [NDSP Tom Morello]() (coming soon)
- [Global rackspace]() (coming soon) -->

## Panels

- [GlobalLink Panel](bin/globallink_panel.zip). Add this to your Global Rackspace for the GlobalLink scripts to work in your own gig file. Also copy the [required includes](Scripts/includes), add the [Global Rackspace script](Scripts/gl_global_rack.gpscript) and the [Gig Script](Scripts/gl_gig.gpscript).

## Scripts

- [Includes for GlobalLink](Scripts/includes), required for the GlobalLink script to work.
- [AutoLoad](Scripts/AutoLoad), required for most scripts to work.
- [Global rackspace script](Scripts/gl_global_rack.gpscript) saved separately if you want to adapt it for your gig.
- [Gig script](Scripts/gl_gig.gpscript) saved separately if you want to adapt it for your gig.
- [Rackspace script template](Scripts/templates/gl_rs_template.gpscript) to make configuration of your gig file easier.

## Overlay templates for controllers

There are editable Photoshop files, printable pdfs, and image files for reference. Also, Nanokontrol overlay doesn't fit on A4, so there's also a printable pdf where the overlay is split in 2 parts so you can print it at home.

- [X-Touch Mini](Controllers/Overlays/X-Touch%20Mini)

<div style="text-align: center">
<img src="./Controllers/Overlays/X-Touch%20Mini/gl%20overlay%20x-touch%20mini%204.png" alt="X-Touch Mini With Overlay" style="width: 50%">
</div>

- [Korg Nanokontrol 2](Controllers/Overlays/Nanokontrol%202)

<div style="text-align: center">
<img src ="./Controllers/Overlays/Nanokontrol%202/nanoKONTROL2-Skin-ver-10.png" alt = "Nanokontrol 2 With Overlay">
</div>

## Controller settings

- [.bin files for X-Touch Mini](Controllers/Settings/X-Touch%20Mini) that work with the Global Link scripts. Download the X-Touch Editor [here](https://www.behringer.com/product.html?modelCode=0808-AAF) and upload to your X-Touch Mini for the GlobalLink scripts to work with the controller.
- [.nktrl2_data file for Korg Nanokontrol 2](Controllers/Settings/Nanokontrol%202/nanokontrol2%20default.nktrl2_data). Download Kontrol Editor [here](https://www.korg.com/us/support/download/software/1/133/1355/).

### Release Notes

- [v1.0](RELEASE_NOTES.md)

### Credits

- The overlay template for X-Touch Mini is based on [this template for Lightroom](https://drive.google.com/uc?export=download&id=1ETpBydF9yPbNrgkYw7VU5eQ0otGsZAkH).
- The overlay template for Nanokontrol is based on [this template](https://community.gigperformer.com/t/nanokontrol-2-skin-template-for-you/13095) from GP forum.
- The implementation of dynamic widget sync was inspired by [this script by schamass](https://community.gigperformer.com/t/move-multiple-faders-relatively-with-one-single-knob-dca-like/10757).
