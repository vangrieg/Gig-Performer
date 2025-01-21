# Release Notes

## Version 1.0

### New Features

- **GlobalLinkPoc.gig**: A template that controls rackspace widgets from global rackspace.
  - [GP forum link]()

- **SyncWidgets.gig**: A template that programmatically creates widget groups.
  - [GP forum link](https://community.gigperformer.com/t/assignable-widget-groups-with-a-gig-file-and-examples/20754)

- **Overlay templates for controllers**:
  - [X-Touch Mini](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Overlays/X-Touch%20Mini)
  - [Korg Nanokontrol 2](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Overlays/Nanokontrol%202)

- **Controller settings**:
  - [.bin files for X-Touch Mini](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Settings/X-Touch%20Mini) that work with the Global Link scripts.

### Instructions
- Enable OSC in Gig Performer settings.
- Copy contents of [Scripts](https://github.com/vangrieg/Gig-Performer/tree/main/Scripts/) to your Gig Performer Scripts folder. Here's a [zip archive](https://github.com/vangrieg/Gig-Performer/blob/main/bin/globallink.zip) with all the files.
- If you want to adapt this to your actual gig file with rackspaces, you will need to:
  - Add the provided [GolbalLink Panel](https://github.com/vangrieg/Gig-Performer/blob/main/Panels/GlobalLink.gppanel)
  - Add rackspace scripts. You can use the scripts in the gig file as examples and modify them, or use the [template](https://github.com/vangrieg/Gig-Performer/blob/dev/Scripts/templates/gl_rs_template.gpscript) from the Scripts/templates folder. If you have/know how to use tools like Github Copilot, after declaring the widgets it can be a 5 minute affair.

For more details, refer to the [README.md](README.md) file and visit relevant forum links.
