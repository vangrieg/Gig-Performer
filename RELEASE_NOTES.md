<!-- markdownlint-disable MD007 -->
<!-- markdownlint-disable MD033 -->
# Release Notes

## Version 1.0

### Initial Release

- **GlobalLinkPoc.gig**: A template that controls rackspace widgets from global rackspace.
  - [GP forum link]()

- **SyncWidgets.gig**: A template that programmatically creates widget groups.
  - [GP forum link](https://community.gigperformer.com/t/assignable-widget-groups-with-a-gig-file-and-examples/20754)

- **Overlay templates for controllers**:
  - [X-Touch Mini](Controllers/Overlays/X-Touch%20Mini)
  - [Korg Nanokontrol 2](Controllers/Overlays/Nanokontrol%202)

- **Controller settings**:
  - [.bin files for X-Touch Mini](Controllers/Settings/X-Touch%20Mini) that work with the Global Link scripts.
  - [.nktrl2_data file for Korg Nanokontrol 2](Controllers/Settings/Nanokontrol%202/nanokontrol2%20default.nktrl2_data). Download Kontrol Editor [here](https://www.korg.com/us/support/download/software/1/133/1355/).

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
