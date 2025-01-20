# Release Notes

## Version 1.0

### New Features
- **GlobalLinkPoc.gig**: A template that controls rackspace widgets from global rackspace.
  - [GP forum link for initial idea](https://community.gigperformer.com/t/one-hardware-controller-many-racks-dynamically-linked-template-gig/20563)
  - [GP forum link for current status]()

- **SyncWidgets.gig**: A template that programmatically creates widget groups.
  - [GP forum link](https://community.gigperformer.com/t/assignable-widget-groups-with-a-gig-file-and-examples/20754)

- **Overlay templates for controllers**:
  - [X-Touch Mini](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Overlays/X-Touch%20Mini)
  - [Korg Nanokontrol 2](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Overlays/Nanokontrol%202)

- **Controller settings**:
  - [.bin files for X-Touch Mini](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Settings/X-Touch%20Mini) that work with the Global Link scripts.

### Instructions
- Enable OSC in Gig Performer settings.
- Copy contents of [Scripts](https://github.com/vangrieg/Gig-Performer/tree/main/Scripts/) to your Gig Performer Scripts folder.
- Add the [Global Link Panel](https://github.com/vangrieg/Gig-Performer/blob/main/Panels/GlobalLink.gppanel) to your Global Rackspace for the GlobalLink scripts to work in your own gig file. Also add the [global rackspace script](https://github.com/vangrieg/Gig-Performer/blob/main/Scripts/gl_global_rack.gpscript).

For more details, refer to the [README.md](README.md) file.
