# Thronglets

Interface snapshot settings.

## General Settings

- Theme: Light
- Screen resolution: 1920x1080

- **Turn off Night Light mode**!
- Resize the window (see *Window Size* settings)
- Only vertical scrollbar
- Command center: closed
- No `nls` script visible
- *View updates* enabled
- Maintain default settings

## Window Size

1. Install `wmctrl` to manage windows (if not already installed).
2. Run:

```bash
# gravity, x, y, width, and height
wmctrl -r NetLogo -e 0,70,100,1781,790
```

## GIF Settings

### Sequences

- **Ticks**: 0:9

```netlogo
go
```

### Render

1. Install `ImageMagick` (if not already installed).
2. Run:

```bash
magick -delay 60 -loop 0 *.png output.gif
```
