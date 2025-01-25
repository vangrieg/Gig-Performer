<!-- markdownlint-disable MD007 -->
<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD024 -->
# Release Notes

## Version 1.3

- **New Feature**
  - Added new rackspace `NDSP Tom Morello`

## Version 1.2

### Feature Update

- **New Feature**
  - Added new rackspace `NDSP Cory Wong X`

- **Fixes**
  - Several small fixes and updates

## Version 1.1

- **New Feature**
  - Added new rackspace `NDSP Petrucci X`.

- **Fixes**
  - Replaced the Global Link panel with more up-to-date version

## Version 1.0

### Initial Release

- **GlobalLinkPoc.gig**: A template that controls rackspace widgets from global rackspace.
- **SyncWidgets.gig**: A template that helps adapt the scripts to your rackspaces.
- **Overlay templates for controllers**:
  - X-Touch Mini
  - Korg Nanokontrol 2
- **Controller settings**

### Instructions

- Enable OSC in Gig Performer settings.
- Copy contents of [Scripts](Scripts/) to your Gig Performer Scripts folder. Here's a [zip archive](bin/globallink_scripts.zip) with all the files.
- Upload the provided [.bin files](Controllers/Settings/X-Touch%20Mini) to your X-Touch Mini (use the [X-Touch Editor](https://www.behringer.com/product.html?modelCode=0808-AAF))
- Map hardware knobs and buttons on X-Touch Mini to the widgets on the Global Rackspace.
- If you want to adapt this to your actual gig file with rackspaces, you will also need to:
  - Add the provided [GolbalLink Panel](bin/globallink_panel.zip) to your Global Rackspace.
  - Add the [Global Rackspace script](Scripts/gl_global_rack.gpscript) to your Global Rackspace. You will need to adjust it to your actual effects there if you have any.
  - Add the [Gig script](Scripts/gl_gig.gpscript).
  - Add and adjust rackspace scripts. You can use the scripts in the gig file as examples and modify them, or use the [template](Scripts/templates/gl_rs_template.gpscript) from the Scripts/templates folder. If you have/know how to use tools like Github Copilot, after declaring the widgets it can be a 5 minute affair.

For more details, refer to the [README.md](README.md) file and visit relevant forum links.
