# stat

grafonnet.panel.stat

## Subpackages

* [fieldOverride](fieldOverride.md)
* [link](link.md)
* [thresholdStep](thresholdStep.md)
* [transformation](transformation.md)
* [valueMapping](valueMapping.md)

## Index

* [`fn new(title)`](#fn-new)
* [`obj datasource`](#obj-datasource)
  * [`fn withType(value)`](#fn-datasourcewithtype)
  * [`fn withUid(value)`](#fn-datasourcewithuid)
* [`obj gridPos`](#obj-gridpos)
  * [`fn withH(value=9)`](#fn-gridposwithh)
  * [`fn withStatic(value)`](#fn-gridposwithstatic)
  * [`fn withW(value=12)`](#fn-gridposwithw)
  * [`fn withX(value=0)`](#fn-gridposwithx)
  * [`fn withY(value=0)`](#fn-gridposwithy)
* [`obj libraryPanel`](#obj-librarypanel)
  * [`fn withName(value)`](#fn-librarypanelwithname)
  * [`fn withUid(value)`](#fn-librarypanelwithuid)
* [`obj options`](#obj-options)
  * [`fn withColorMode(value)`](#fn-optionswithcolormode)
  * [`fn withGraphMode(value)`](#fn-optionswithgraphmode)
  * [`fn withJustifyMode(value)`](#fn-optionswithjustifymode)
  * [`fn withOrientation(value)`](#fn-optionswithorientation)
  * [`fn withReduceOptions(value)`](#fn-optionswithreduceoptions)
  * [`fn withReduceOptionsMixin(value)`](#fn-optionswithreduceoptionsmixin)
  * [`fn withText(value)`](#fn-optionswithtext)
  * [`fn withTextMixin(value)`](#fn-optionswithtextmixin)
  * [`fn withTextMode(value)`](#fn-optionswithtextmode)
  * [`obj reduceOptions`](#obj-optionsreduceoptions)
    * [`fn withCalcs(value)`](#fn-optionsreduceoptionswithcalcs)
    * [`fn withCalcsMixin(value)`](#fn-optionsreduceoptionswithcalcsmixin)
    * [`fn withFields(value)`](#fn-optionsreduceoptionswithfields)
    * [`fn withLimit(value)`](#fn-optionsreduceoptionswithlimit)
    * [`fn withValues(value)`](#fn-optionsreduceoptionswithvalues)
  * [`obj text`](#obj-optionstext)
    * [`fn withTitleSize(value)`](#fn-optionstextwithtitlesize)
    * [`fn withValueSize(value)`](#fn-optionstextwithvaluesize)
* [`obj panelOptions`](#obj-paneloptions)
  * [`fn withDescription(value)`](#fn-paneloptionswithdescription)
  * [`fn withLinks(value)`](#fn-paneloptionswithlinks)
  * [`fn withLinksMixin(value)`](#fn-paneloptionswithlinksmixin)
  * [`fn withRepeat(value)`](#fn-paneloptionswithrepeat)
  * [`fn withRepeatDirection(value="h")`](#fn-paneloptionswithrepeatdirection)
  * [`fn withTitle(value)`](#fn-paneloptionswithtitle)
  * [`fn withTransparent(value=false)`](#fn-paneloptionswithtransparent)
* [`obj queryOptions`](#obj-queryoptions)
  * [`fn withDatasource(value)`](#fn-queryoptionswithdatasource)
  * [`fn withDatasourceMixin(value)`](#fn-queryoptionswithdatasourcemixin)
  * [`fn withInterval(value)`](#fn-queryoptionswithinterval)
  * [`fn withMaxDataPoints(value)`](#fn-queryoptionswithmaxdatapoints)
  * [`fn withTargets(value)`](#fn-queryoptionswithtargets)
  * [`fn withTargetsMixin(value)`](#fn-queryoptionswithtargetsmixin)
  * [`fn withTimeFrom(value)`](#fn-queryoptionswithtimefrom)
  * [`fn withTimeShift(value)`](#fn-queryoptionswithtimeshift)
  * [`fn withTransformations(value)`](#fn-queryoptionswithtransformations)
  * [`fn withTransformationsMixin(value)`](#fn-queryoptionswithtransformationsmixin)
* [`obj standardOptions`](#obj-standardoptions)
  * [`fn withDecimals(value)`](#fn-standardoptionswithdecimals)
  * [`fn withDisplayName(value)`](#fn-standardoptionswithdisplayname)
  * [`fn withLinks(value)`](#fn-standardoptionswithlinks)
  * [`fn withLinksMixin(value)`](#fn-standardoptionswithlinksmixin)
  * [`fn withMappings(value)`](#fn-standardoptionswithmappings)
  * [`fn withMappingsMixin(value)`](#fn-standardoptionswithmappingsmixin)
  * [`fn withMax(value)`](#fn-standardoptionswithmax)
  * [`fn withMin(value)`](#fn-standardoptionswithmin)
  * [`fn withNoValue(value)`](#fn-standardoptionswithnovalue)
  * [`fn withOverrides(value)`](#fn-standardoptionswithoverrides)
  * [`fn withOverridesMixin(value)`](#fn-standardoptionswithoverridesmixin)
  * [`fn withUnit(value)`](#fn-standardoptionswithunit)
  * [`obj color`](#obj-standardoptionscolor)
    * [`fn withFixedColor(value)`](#fn-standardoptionscolorwithfixedcolor)
    * [`fn withMode(value)`](#fn-standardoptionscolorwithmode)
    * [`fn withSeriesBy(value)`](#fn-standardoptionscolorwithseriesby)
  * [`obj tresholds`](#obj-standardoptionstresholds)
    * [`fn withMode(value)`](#fn-standardoptionstresholdswithmode)
    * [`fn withSteps(value)`](#fn-standardoptionstresholdswithsteps)
    * [`fn withStepsMixin(value)`](#fn-standardoptionstresholdswithstepsmixin)

## Fields

### fn new

```ts
new(title)
```

Creates a new stat panel with a title.

### obj datasource


#### fn datasource.withType

```ts
withType(value)
```



#### fn datasource.withUid

```ts
withUid(value)
```



### obj gridPos


#### fn gridPos.withH

```ts
withH(value=9)
```

Panel

#### fn gridPos.withStatic

```ts
withStatic(value)
```

true if fixed

#### fn gridPos.withW

```ts
withW(value=12)
```

Panel

#### fn gridPos.withX

```ts
withX(value=0)
```

Panel x

#### fn gridPos.withY

```ts
withY(value=0)
```

Panel y

### obj libraryPanel


#### fn libraryPanel.withName

```ts
withName(value)
```



#### fn libraryPanel.withUid

```ts
withUid(value)
```



### obj options


#### fn options.withColorMode

```ts
withColorMode(value)
```

TODO docs

Accepted values for `value` are "value", "background", "background_solid", "none"

#### fn options.withGraphMode

```ts
withGraphMode(value)
```

TODO docs

Accepted values for `value` are "none", "line", "area"

#### fn options.withJustifyMode

```ts
withJustifyMode(value)
```

TODO docs

Accepted values for `value` are "auto", "center"

#### fn options.withOrientation

```ts
withOrientation(value)
```

TODO docs

Accepted values for `value` are "auto", "vertical", "horizontal"

#### fn options.withReduceOptions

```ts
withReduceOptions(value)
```

TODO docs

#### fn options.withReduceOptionsMixin

```ts
withReduceOptionsMixin(value)
```

TODO docs

#### fn options.withText

```ts
withText(value)
```

TODO docs

#### fn options.withTextMixin

```ts
withTextMixin(value)
```

TODO docs

#### fn options.withTextMode

```ts
withTextMode(value)
```

TODO docs

Accepted values for `value` are "auto", "value", "value_and_name", "name", "none"

#### obj options.reduceOptions


##### fn options.reduceOptions.withCalcs

```ts
withCalcs(value)
```

When !values, pick one value for the whole field

##### fn options.reduceOptions.withCalcsMixin

```ts
withCalcsMixin(value)
```

When !values, pick one value for the whole field

##### fn options.reduceOptions.withFields

```ts
withFields(value)
```

Which fields to show.  By default this is only numeric fields

##### fn options.reduceOptions.withLimit

```ts
withLimit(value)
```

if showing all values limit

##### fn options.reduceOptions.withValues

```ts
withValues(value)
```

If true show each row value

#### obj options.text


##### fn options.text.withTitleSize

```ts
withTitleSize(value)
```

Explicit title text size

##### fn options.text.withValueSize

```ts
withValueSize(value)
```

Explicit value text size

### obj panelOptions


#### fn panelOptions.withDescription

```ts
withDescription(value)
```

Description.

#### fn panelOptions.withLinks

```ts
withLinks(value)
```

Panel links.
TODO fill this out - seems there are a couple variants?

#### fn panelOptions.withLinksMixin

```ts
withLinksMixin(value)
```

Panel links.
TODO fill this out - seems there are a couple variants?

#### fn panelOptions.withRepeat

```ts
withRepeat(value)
```

Name of template variable to repeat for.

#### fn panelOptions.withRepeatDirection

```ts
withRepeatDirection(value="h")
```

Direction to repeat in if 'repeat' is set.
"h" for horizontal, "v" for vertical.
TODO this is probably optional

Accepted values for `value` are "h", "v"

#### fn panelOptions.withTitle

```ts
withTitle(value)
```

Panel title.

#### fn panelOptions.withTransparent

```ts
withTransparent(value=false)
```

Whether to display the panel without a background.

### obj queryOptions


#### fn queryOptions.withDatasource

```ts
withDatasource(value)
```

The datasource used in all targets.

#### fn queryOptions.withDatasourceMixin

```ts
withDatasourceMixin(value)
```

The datasource used in all targets.

#### fn queryOptions.withInterval

```ts
withInterval(value)
```

TODO docs
TODO tighter constraint

#### fn queryOptions.withMaxDataPoints

```ts
withMaxDataPoints(value)
```

TODO docs

#### fn queryOptions.withTargets

```ts
withTargets(value)
```

TODO docs

#### fn queryOptions.withTargetsMixin

```ts
withTargetsMixin(value)
```

TODO docs

#### fn queryOptions.withTimeFrom

```ts
withTimeFrom(value)
```

TODO docs
TODO tighter constraint

#### fn queryOptions.withTimeShift

```ts
withTimeShift(value)
```

TODO docs
TODO tighter constraint

#### fn queryOptions.withTransformations

```ts
withTransformations(value)
```



#### fn queryOptions.withTransformationsMixin

```ts
withTransformationsMixin(value)
```



### obj standardOptions


#### fn standardOptions.withDecimals

```ts
withDecimals(value)
```

Significant digits (for display)

#### fn standardOptions.withDisplayName

```ts
withDisplayName(value)
```

The display value for this field.  This supports template variables blank is auto

#### fn standardOptions.withLinks

```ts
withLinks(value)
```

The behavior when clicking on a result

#### fn standardOptions.withLinksMixin

```ts
withLinksMixin(value)
```

The behavior when clicking on a result

#### fn standardOptions.withMappings

```ts
withMappings(value)
```

Convert input values into a display string

#### fn standardOptions.withMappingsMixin

```ts
withMappingsMixin(value)
```

Convert input values into a display string

#### fn standardOptions.withMax

```ts
withMax(value)
```



#### fn standardOptions.withMin

```ts
withMin(value)
```



#### fn standardOptions.withNoValue

```ts
withNoValue(value)
```

Alternative to empty string

#### fn standardOptions.withOverrides

```ts
withOverrides(value)
```



#### fn standardOptions.withOverridesMixin

```ts
withOverridesMixin(value)
```



#### fn standardOptions.withUnit

```ts
withUnit(value)
```

Numeric Options

#### obj standardOptions.color


##### fn standardOptions.color.withFixedColor

```ts
withFixedColor(value)
```

Stores the fixed color value if mode is fixed

##### fn standardOptions.color.withMode

```ts
withMode(value)
```

The main color scheme mode

##### fn standardOptions.color.withSeriesBy

```ts
withSeriesBy(value)
```

TODO docs

Accepted values for `value` are "min", "max", "last"

#### obj standardOptions.tresholds


##### fn standardOptions.tresholds.withMode

```ts
withMode(value)
```



Accepted values for `value` are "absolute", "percentage"

##### fn standardOptions.tresholds.withSteps

```ts
withSteps(value)
```

Must be sorted by 'value', first value is always -Infinity

##### fn standardOptions.tresholds.withStepsMixin

```ts
withStepsMixin(value)
```

Must be sorted by 'value', first value is always -Infinity
