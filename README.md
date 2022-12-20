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
| ![#4e79a7](https://placehold.co/15x15/4e79a7/4e79a7.png) | `#4e79a7` |
| ![#59a14f](https://placehold.co/15x15/59a14f/59a14f.png) | `#59a14f` | 
| ![#edc948](https://placehold.co/15x15/edc948/edc948.png) | `#edc948` |
| ![#e15759](https://placehold.co/15x15/e15759/e15759.png) | `#e15759` |
| ![#b07aa1](https://placehold.co/15x15/b07aa1/b07aa1.png) | `#b07aa1` |
| ![#ff9da7](https://placehold.co/15x15/ff9da7/ff9da7.png) | `#ff9da7` |

# Sequential

## [Colorbrewer2 YlGnBu (4)](https://colorbrewer2.org/#type=sequential&scheme=YlGnBu&n=4)

| Color | Hex |
|-------|-----|
| ![#ffffcc](https://placehold.co/15x15/ffffcc/ffffcc.png) | `#ffffcc` |
| ![#a1dab4](https://placehold.co/15x15/a1dab4/a1dab4.png) | `#a1dab4` | 
| ![#41b6c4](https://placehold.co/15x15/41b6c4/41b6c4.png) | `#41b6c4` |
| ![#225ea8](https://placehold.co/15x15/225ea8/225ea8.png) | `#225ea8` |


## [Colorbrewer2 PuRd (6)](https://colorbrewer2.org/#type=sequential&scheme=PuRd&n=6)

| Color | Hex |
|-------|-----|
| ![#f1eef6](https://placehold.co/15x15/f1eef6/f1eef6.png) | `#f1eef6` |
| ![#d4b9da](https://placehold.co/15x15/d4b9da/d4b9da.png) | `#d4b9da` | 
| ![#c994c7](https://placehold.co/15x15/c994c7/c994c7.png) | `#c994c7` |
| ![#df65b0](https://placehold.co/15x15/df65b0/df65b0.png) | `#df65b0` |
| ![#dd1c77](https://placehold.co/15x15/dd1c77/dd1c77.png) | `#dd1c77` |
| ![#980043](https://placehold.co/15x15/980043/980043.png) | `#980043` |


## [Colorbrewer2 GnBu (6)](https://colorbrewer2.org/#type=sequential&scheme=GnBu&n=6)

| Color | Hex |
|-------|-----|
| ![#f0f9e8](https://placehold.co/15x15/f0f9e8/f0f9e8.png) | `#f0f9e8` |
| ![#ccebc5](https://placehold.co/15x15/ccebc5/ccebc5.png) | `#ccebc5` | 
| ![#a8ddb5](https://placehold.co/15x15/a8ddb5/a8ddb5.png) | `#a8ddb5` |
| ![#7bccc4](https://placehold.co/15x15/7bccc4/7bccc4.png) | `#7bccc4` |
| ![#43a2ca](https://placehold.co/15x15/43a2ca/43a2ca.png) | `#43a2ca` |
| ![#0868ac](https://placehold.co/15x15/0868ac/0868ac.png) | `#0868ac` |


## [Munsell system (7)](http://projects.kumpf.cc/projects/MunsellForDesigners/index.html) with Baltimore Ravens purple (`#241773`)

| Color | Hex |
|-------|-----|
| ![#686a73](https://placehold.co/15x15/686a73/686a73.png) | `#686a73` |
| ![#606173](https://placehold.co/15x15/606173/606173.png) | `#606173` | 
| ![#575773](https://placehold.co/15x15/575773/575773.png) | `#575773` |
| ![#4d4c73](https://placehold.co/15x15/4d4c73/4d4c73.png) | `#4d4c73` |
| ![#424073](https://placehold.co/15x15/424073/424073.png) | `#424073` |
| ![#353073](https://placehold.co/15x15/353073/353073.png) | `#353073` |
| ![#241773](https://placehold.co/15x15/241773/241773.png) | `#241773` |


