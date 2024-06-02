# Blenderbase

Blenderbase is a utility app for Blender 3D (supporting versions 3.1.0+) that manages installed Blender versions, community and official addons and blend files.

It was inspired by similar apps, such as `Blender launcher` and owes its success to all forerunners, who, like Blenderbase, tried to improve the user experience for Blender.

Blenderbase is the property of `Physical Addons` and has no legal binding to `Blender Foundation`, unless further specified. All Blender Foundation resources are used in good faith and with the utmost care, so as to not slow down, damage or misuse `Blender Foundation` online resources, those being the official and mirror download pages, hosting the `Stable`, `LTS`, `Daily` and `Patched` Blender version releases. 

Currently there exists no formal agreement between `Physical Addons` and `Blender Foundation` regarding the use of their online resources.

Blenderbase was built using the Tauri framework, and its backend is written in Rust. Its frontend is written using ReactJS. For specialized tasks inside of a Blender instance, Python and BPY is used.

![image](https://github.com/PhysicalAddons/blenderbase-public/assets/60788469/c8ddb72a-3b2b-4260-aef7-3644fa3821d1)

## As of `v1.0.26`, Blenderbase can:
- Run on Windows 10/11 (x64),
- Receive new version of the app via an auto-updater,
- Manage up to 3 modifiable Blender parent installation directories,
- Register installed Blender versions, their addons, recent blend files and the most recent downloadable Blender versions,
- Download and install portable Blender versions from publicly accessible Blender foundation resources (Stable and LTS versions are currently taken from the European mirror website),
- Uninstall both portable and installer installed (.msi) Blender versions,
- Launch selected Blender versions,
- Enable and disable addons when launching a Blender instance through Blenderbase,
- Enable/disable addons outside of a Blender instance,
- Install community addons via .zip or .py,
- Semantic link addon directories (meant for easier addon development),
- Uninstall (or delete the semantic link of) community addons,
- Open recently saved .blend files in any selected Blender version (provided the specific Blender version works for the .blend file).

Blenderbase is currently free (closed source) and allowed to be used in any projects involving Blender use, addon development or Blender project management, Whether for hobby, educational or commercial reasons.
