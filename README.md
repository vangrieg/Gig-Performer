# Gig-Performer

Scripts, rackspaces, panels, overlay templates and other [Gig Performer](https://gigperformer.com/) customizations. See GP forum links for descriptions and discussions.

## Gig files

- **GlobalLinkPoc.gig** is a template that controls rackspace widgets from global rackspace.

    *Descriptions:*

  - [GP forum link for the full version]()
  - [GP forum link for initial idea](https://community.gigperformer.com/t/one-hardware-controller-many-racks-dynamically-linked-template-gig/20563)

  *Instructions:*

    - Enable OSC in Gig Performer settings
    - Copy contents of [Scripts](https://github.com/vangrieg/Gig-Performer/tree/main/Scripts/) to your Gig Performer Scripts folder

- **SyncWidgets.gig** is a template that programmatically creates widget groups. Check out the [GP forum link](https://community.gigperformer.com/t/assignable-widget-groups-with-a-gig-file-and-examples/20754) to see what this does.

## Rackspaces

- [NDSP Cory Wong X]() (coming soon)
- [NDSP Petrucci X]() (coming soon)
- [NDSP Tom Morello]() (coming soon)
- [Global rackspace]() (coming soon)

## Panels

- [Global Link Panel](https://github.com/vangrieg/Gig-Performer/blob/main/Panels/GlobalLink.gppanel). Add this to your Global Rackspace for the GlobalLink scripts to work in your own gig file. Also add the [global rackspace script](https://github.com/vangrieg/Gig-Performer/blob/main/Scripts/gl_global_rack.gpscript).

## Scripts

- [Includes for GlobalLink](https://github.com/vangrieg/Gig-Performer/tree/main/Scripts/includes), required for the GlobalLink script to work.
- [OSC settings](https://github.com/vangrieg/Gig-Performer/blob/main/Scripts/includes/osc.gpscript), , required for the OSC enabled scripts to work.
- [System script](https://github.com/vangrieg/Gig-Performer/blob/main/Scripts/gl_global_rack.gpscript), required for most scripts to work.
- [AutoLoad](https://github.com/vangrieg/Gig-Performer/tree/main/Scripts/AutoLoad), required for most scripts to work.
- [Rackspace script template](https://github.com/vangrieg/Gig-Performer/blob/main/Scripts/templates/global%20link%20rack%20template2.tmp) to make configuration of your gig file easier.

## Overlay templates for controllers

- [X-Touch Mini](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Overlays/X-Touch%20Mini)
- [Korg Nanokontrol 2](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Overlays/Nanokontrol%202)

## Controller settings

- [.bin files for X-Touch Mini](https://github.com/vangrieg/Gig-Performer/tree/main/Controllers/Settings/X-Touch%20Mini) that work with the Global Link scripts. Download the X-Touch Editor [here](https://www.behringer.com/product.html?modelCode=0808-AAF) and upload to your X-Touch Mini for the GlobalLink scripts to work with the controller.
