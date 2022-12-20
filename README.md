# Colors
John's color style guide. You can visualize a custom color map using the [online tool here](https://share.streamlit.io/dhaitz/colormap-creator/main/app.py), or by using the following:

```python
from matplotlib.colors import LinearSegmentedColormap

c0, c1, c2, c3, c4 = '#003f5c', '#58508d', '#bc5090', '#ff6361', '#ffa600'

cmap = LinearSegmentedColormap.from_list(
    'jw_cmap', 
    [c0, c1, c2, c3, c4, c5], 
    N=15
)
```

You also should be using [`cmasher`](https://github.com/1313e/CMasher), which gives you a way to convert colormaps into discrete color intervals ([example](https://cmasher.readthedocs.io/user/usage.html#taking-colormap-colors)):
```python
import cmasher as cmr

colors = cmr.take_cmap_colors(
    'cmr.rainforest', 
    5, 
    cmap_range=(0.15, 0.85), 
    return_fmt='hex'
)
```


# Qualitative

## [Data Viz Color Palette (5)](https://learnui.design/tools/data-color-picker.html)

| Color | Hex |
|-------|-----|
| ![#003f5c](https://placehold.co/15x15/003f5c/003f5c.png) | `#003f5c` |
| ![#58508d](https://placehold.co/15x15/58508d/58508d.png) | `#58508d` | 
| ![#bc5090](https://placehold.co/15x15/bc5090/bc5090.png) | `#bc5090` |
| ![#ff6361](https://placehold.co/15x15/ff6361/ff6361.png) | `#ff6361` |
| ![#ffa600](https://placehold.co/15x15/ffa600/ffa600.png) | `#ffa600` |

## [Viz palette by Elijah Meeks & Susie Lu (6)](https://projects.susielu.com/viz-palette?colors=[%22#4e79a7%22,%22#59a14f%22,%22#edc948%22,%22#e15759%22,%22#b07aa1%22,%22#ff9da7%22]&backgroundColor=%22#f2f7eb%22&fontColor=%22black%22&mode=%22normal%22)

| Color | Hex |
|-------|-----|
| ![#4e79a7](https://via.placeholder.com/40/4e79a7/000000?text=+) | `#4e79a7` |
| ![#59a14f](https://via.placeholder.com/40/59a14f/000000?text=+) | `#59a14f` | 
| ![#edc948](https://via.placeholder.com/40/edc948/000000?text=+) | `#edc948` |
| ![#e15759](https://via.placeholder.com/40/e15759/000000?text=+) | `#e15759` |
| ![#b07aa1](https://via.placeholder.com/40/b07aa1/000000?text=+) | `#b07aa1` |
| ![#ff9da7](https://via.placeholder.com/40/ff9da7/000000?text=+) | `#ff9da7` |


# Sequential

## [Colorbrewer2 YlGnBu (4)](https://colorbrewer2.org/#type=sequential&scheme=YlGnBu&n=4)

| Color | Hex |
|-------|-----|
| ![#ffffcc](https://via.placeholder.com/40/ffffcc/000000?text=+) | `#ffffcc` |
| ![#a1dab4](https://via.placeholder.com/40/a1dab4/000000?text=+) | `#a1dab4` | 
| ![#41b6c4](https://via.placeholder.com/40/41b6c4/000000?text=+) | `#41b6c4` |
| ![#225ea8](https://via.placeholder.com/40/225ea8/000000?text=+) | `#225ea8` |


## [Colorbrewer2 PuRd (6)](https://colorbrewer2.org/#type=sequential&scheme=PuRd&n=6)

| Color | Hex |
|-------|-----|
| ![#f1eef6](https://via.placeholder.com/40/f1eef6/000000?text=+) | `#f1eef6` |
| ![#d4b9da](https://via.placeholder.com/40/d4b9da/000000?text=+) | `#d4b9da` | 
| ![#c994c7](https://via.placeholder.com/40/c994c7/000000?text=+) | `#c994c7` |
| ![#df65b0](https://via.placeholder.com/40/df65b0/000000?text=+) | `#df65b0` |
| ![#dd1c77](https://via.placeholder.com/40/dd1c77/000000?text=+) | `#dd1c77` |
| ![#980043](https://via.placeholder.com/40/980043/000000?text=+) | `#980043` |


## [Colorbrewer2 GnBu (6)](https://colorbrewer2.org/#type=sequential&scheme=GnBu&n=6)

| Color | Hex |
|-------|-----|
| ![#f0f9e8](https://via.placeholder.com/40/f0f9e8/000000?text=+) | `#f0f9e8` |
| ![#ccebc5](https://via.placeholder.com/40/ccebc5/000000?text=+) | `#ccebc5` | 
| ![#a8ddb5](https://via.placeholder.com/40/a8ddb5/000000?text=+) | `#a8ddb5` |
| ![#7bccc4](https://via.placeholder.com/40/7bccc4/000000?text=+) | `#7bccc4` |
| ![#43a2ca](https://via.placeholder.com/40/43a2ca/000000?text=+) | `#43a2ca` |
| ![#0868ac](https://via.placeholder.com/40/0868ac/000000?text=+) | `#0868ac` |


## [Munsell system (7)](http://projects.kumpf.cc/projects/MunsellForDesigners/index.html) with Baltimore Ravens purple (`#241773`)

| Color | Hex |
|-------|-----|
| ![#686a73](https://via.placeholder.com/40/686a73/000000?text=+) | `#686a73` |
| ![#606173](https://via.placeholder.com/40/606173/000000?text=+) | `#606173` | 
| ![#575773](https://via.placeholder.com/40/575773/000000?text=+) | `#575773` |
| ![#4d4c73](https://via.placeholder.com/40/4d4c73/000000?text=+) | `#4d4c73` |
| ![#424073](https://via.placeholder.com/40/424073/000000?text=+) | `#424073` |
| ![#353073](https://via.placeholder.com/40/353073/000000?text=+) | `#353073` |
| ![#241773](https://via.placeholder.com/40/241773/000000?text=+) | `#241773` |


