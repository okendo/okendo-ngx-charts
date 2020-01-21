# @okendo/ngx-charts

Fork from [https://github.com/swimlane/ngx-charts]

## Install

`npm i @okendo/ngx-charts`

## Add-on Features

### Max width of each bar on bar chart

Use `barMaxWidth` attribute with default value 100px

#### Example

### Chart Types

- Horizontal & Vertical Bar Charts (Standard, Grouped, Stacked, Normalized)
- Line
- Area (Standard, Stacked, Normalized)
- Pie (Explodable, Grid, Custom legends)
- Bubble
- Donut
- Gauge (Linear & Radial)
- Heatmap
- Treemap
- Number Cards
- Sankey Diagram

### Customization

- Autoscaling
- Timeline Filtering
- Line Interpolation
- Configurable Axis Labels
- Legends (Labels & Gradient)
- Advanced Label Positioning
- Real-time data support
- Advanced Tooltips
- Data point Event Handlers
- Works with ngUpgrade

## Install

To use ngx-charts in your project install it via [npm](https://www.npmjs.com/package/@swimlane/ngx-charts):

```

## Potential features(bar-chart)

- center the chart

## Release

- Checkout master (`git checkout master`)
- Pull master (`git pull`)
- Refresh node modules (`yarn install --frozen-lockfile`)
- Run tests (`yarn test`)
- Examine log to determine next version (X.Y.Z)
- Run `git checkout -b release/X.Y.Z`
- Update version in `projects/swimlane/ngx-charts/package.json`
- Update changelog in `projects/docs/changelog.md`
- Run `git commit -am "(release): X.Y.Z"`
- Run `git tag X.Y.Z`
- Run `git push origin HEAD --tags`
- Run `yarn publish:lib`
- Submit PR

## Credits

- adjust padding for small amount of values
