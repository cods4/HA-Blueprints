Blueprints I made for Home Assistant

## IKEA

- `IKEA/IKEA_Bilresa_Dual_Button_Wall_Switch.yaml` — 2-button BILRESA, with an optional wall switch.
- `IKEA/IKEA_Bilresa_Scroll_Wheel_Wall_Switch.yaml` — 3-channel BILRESA scroll wheel (Matter) and an optional Shelly wall switch.

The scroll-wheel blueprint description is the setup guide: which Matter entities to enable, relaxed versus instant scrolling, and the wall-switch gestures. Leave the wall-switch event list empty to use the remote on its own.

Scroll-wheel event handling follows [jhol-byte's blueprint](https://gist.github.com/jhol-byte/b2731a4d2476f530d76b9ff409f7f3a4).
