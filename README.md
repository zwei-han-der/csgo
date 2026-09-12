# Zweihander's config

This is how to use my cfg

## Configuration

1. **Before starting the game**, add these parameters to the launch options

    ```
    -steam -tickrate 128 -novid -w 1280 -h 960 -fullscreen
    ```

2. Copy and paste the following files in the `~/csgo/cfg` folder:

    ```
    ├─ config/
    │  ├─ binds.cfg
    │  ├─ crosshair.cfg
    │  ├─ hud.cfg
    │  ├─ sensitivity.cfg
    │  └─ viewmodel.cfg
    ├─ autoexec.cfg
    ├─ practice.cfg
    └─ unpractice.cfg
    ```
3. Enter the game, enable the developer console
4. Run the following command:
    ```
    exec autoexec
    ```

### Practice game

After starting a casual or competitive match against bots, run the following command:

```
exec practice
```

Before exiting the game, run the following command to reset the configuration:

```
exec unpractice
```
## Zweihander's inventory

After downloading csgo_gc, copy and paste the `csgo_gc/inventory.txt` file in `csgo/csgo_gc/` folder
