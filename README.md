# Custom Electronics Enclosure — Build Log 01

A hands-on project: a 3D-printed housing for a repurposed Bluetooth tracker module, wired and assembled by hand.

## What's in the repo

```
.
├── index.html        # GitHub Pages site
├── images/           # Compressed build photos (all under 200 KB)
│   ├── image.jpg     # CAD — box body in Shapr3D
│   ├── image2.jpg    # CAD — component layout (lid, trays, rings)
│   ├── image3.jpg    # Wiring — battery holders connected to BLE module
│   ├── image4.jpg    # PCB — crescent board seated in printed tray
│   ├── image5.jpg    # Assembly — internals fit into shell
│   ├── image6.jpg    # Soldering — iron and finished base
│   └── image7.jpg    # Final — assembled enclosure, closed up
└── README.md
```

## The project

The idea was to give a small BLE tracker PCB a real enclosure. The original housing was disposable plastic; this one is designed to last and be opened again if needed.

**Design** was done in Shapr3D on an iPad — a box body with 2 mm walls, a lid with a friction-fit lip, and a front slot for the module's reset button and LED.

**Wiring** connects two AA battery holders in parallel to the PCB's power pads. Brown and green leads, soldered directly at 320°C with flux.

**Assembly** uses hot glue to keep the battery trays in place before the lid goes on.

## How to view the site

The site is live at: `https://<your-username>.github.io/<repo-name>/`

To enable GitHub Pages:
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Wait ~60 seconds, then visit the URL above

## Image sizes

All photos are under 200 KB. GitHub Pages has a 1 GB repo limit and a 100 MB per-file limit; these images are well within both. The originals were resized to a max width of 1200 px and re-exported at 80–85% JPEG quality.

## Tools used

- Shapr3D (iPad)
- FDM 3D Printer + PLA
- Soldering iron (temperature-controlled)
- Hot glue gun
- BLE tracker PCB (crescent-shaped board)
- AA battery holders ×2
- 22 AWG wire
