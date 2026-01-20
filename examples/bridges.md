# bridges

![bridges](/assets/trmt_v0_6_0_bridges_example.webp)

### Config
```toml
[simulation]
heads = 4
rule = "LLRU"
speed_ms = 50.0
trail_length = 16
color_cells = true
seed = "29e'dje"

[display]
colors = [
    "#BBBBFF",
    "#CCCCFF",
    "#DDDDFF",
]
fade_trail_color = ""
state_based_colors = false
live_colors = true
randomize_heads = false
randomize_trails = false
head_char = ["󰝤"]
trail_char = ["󰝤"]
cell_char = "󰝤"
```
