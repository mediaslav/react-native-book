# react-native-book

Random stuff found in sources

Valid color formats are
```
  - '#f0f' (#rgb)
  - '#f0fc' (#rgba)
  - '#ff00ff' (#rrggbb)
  - '#ff00ff00' (#rrggbbaa)
  - 'rgb(255, 255, 255)'
  - 'rgba(255, 255, 255, 1.0)'
  - 'hsl(360, 100%, 100%)'
  - 'hsla(360, 100%, 100%, 1.0)'
  - 'transparent'
  - 'red'
  - 0xff00ff00 (0xrrggbbaa)
```
#### Flexbox style
```
alignItems enum('flex-start', 'flex-end', 'center', 'stretch') 
alignSelf enum('auto', 'flex-start', 'flex-end', 'center', 'stretch') 

borderBottomWidth number 
borderLeftWidth number 
borderRightWidth number 
borderTopWidth number 
borderWidth number 
bottom number 

flex number 
flexDirection enum('row', 'column') 
flexWrap enum('wrap', 'nowrap') 

height number 

justifyContent enum('flex-start', 'flex-end', 'center', 'space-between', 'space-around') 

left number 

margin number 
marginBottom number 
marginHorizontal number 
marginLeft number 
marginRight number 
marginTop number 
marginVertical number 

padding number 
paddingBottom number 
paddingHorizontal number 
paddingLeft number 
paddingRight number 
paddingTop number 
paddingVertical number 
position enum('absolute', 'relative') 

right number 

top number 

width number 
```
#### View styles:
```
Flexbox...
ShadowPropTypesIOS#style...
Transforms...
backfaceVisibility enum('visible', 'hidden')
backgroundColor color
borderBottomColor color
borderBottomLeftRadius number
borderBottomRightRadius number
borderBottomWidth number
borderColor color
borderLeftColor color
borderLeftWidth number
borderRadius number
borderRightColor color
borderRightWidth number
borderStyle enum('solid', 'dotted', 'dashed')
borderTopColor color
borderTopLeftRadius number
borderTopRightRadius number
borderTopWidth number
borderWidth number
opacity number
overflow enum('visible', 'hidden')
[android] elevation number (Android-only) Sets the elevation of a view, using Android's underlying elevation API. 
  This adds a drop shadow to the item and affects z-order for overlapping views. 
  Only supported on Android 5.0+, has no effect on earlier versions.
```
#### Text style
```
View#style...

color color
fontFamily string
fontSize number
fontStyle enum('normal', 'italic')
fontWeight enum('normal', 'bold', '100', '200', '300', '400', '500', '600', '700', '800', '900')
  Specifies font weight. The values 'normal' and 'bold' are supported for most fonts. 
  Not all fonts have a variant for each of the numeric values, in that case the closest one is chosen.

lineHeight number
textAlign enum('auto', 'left', 'right', 'center', 'justify')
  Specifies text alignment. The value 'justify' is only supported on iOS.

textShadowColor color
textShadowOffset {width: number, height: number}
textShadowRadius number
android textAlignVertical enum('auto', 'top', 'bottom', 'center')
ios letterSpacing number
ios textDecorationColor color
ios textDecorationLine enum('none', 'underline', 'line-through', 'underline line-through')
ios textDecorationStyle enum('solid', 'double', 'dotted', 'dashed')
ios writingDirection enum('auto', 'ltr', 'rtl')
```
