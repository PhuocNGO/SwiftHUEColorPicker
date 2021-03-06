## SwiftHUEColorPicker

[![Version](https://img.shields.io/cocoapods/v/SwiftHUEColorPicker.svg?style=flat)](http://cocoadocs.org/docsets/SwiftHUEColorPicker)
[![License](https://img.shields.io/cocoapods/l/SwiftHUEColorPicker.svg?style=flat)](http://cocoadocs.org/docsets/SwiftHUEColorPicker)
[![Platform](https://img.shields.io/cocoapods/p/SwiftHUEColorPicker.svg?style=flat)](http://cocoadocs.org/docsets/SwiftHUEColorPicker)

Simple iOS HUE color picker.</br>
![alt tag](https://raw.github.com/maximbilan/SwiftHUEColorPicker/master/img/img1.png)
## Installation
<b>CocoaPods:</b>
<pre>
Swift 2.2:
pod 'SwiftHUEColorPicker', '~> 0.1.7'

Swift 2.3:
pod 'SwiftHUEColorPicker', '~> 0.2.3'

Swift 3.0:
pod 'SwiftHUEColorPicker', '~> 0.3.0'
</pre>
<b>Manual:</b>
<pre>
Copy <i>SwiftHUEColorPicker.swift</i> to your project.
</pre>

## Description
Supports two modes: <i>horizontal</i> and <i>vertical</i>.</br>
![alt tag](https://raw.github.com/maximbilan/SwiftHUEColorPicker/master/img/img2.png)
</br>Also you can change <i>saturation</i>, <i>brightness</i> and <i>alpha</i> values.
</br>And control has customization. You can customize the label:</br>
![alt tag](https://raw.github.com/maximbilan/SwiftHUEColorPicker/master/img/img3.png)
</br>Or appearance:</br>
</br>
![alt tag](https://raw.github.com/maximbilan/SwiftHUEColorPicker/master/img/img4.png)
## Using
You can create from <i>Storyboard</i> or <i>XIB</i>. Or create manually:
<pre>
let picker = SwiftHUEColorPicker()
</pre>

For handling changing of values you should implement protocol <i>SwiftHUEColorPickerDelegate</i>:
<pre>
picker.delegate = self

func valuePicked(color: UIColor, type: SwiftHUEColorPicker.PickerType) {
}
</pre>

Direction:
<pre>
picker.direction = SwiftHUEColorPicker.PickerDirection.Vertical // Vertical, Horizontal
</pre>

Type:
<pre>
picker.type = SwiftHUEColorPicker.PickerType.Color // Color, Saturation, Brightness, Alpha
</pre>

Please see example for using <i>SwiftHUEColorPicker</i> in this repository.

## License

SwiftHUEColorPicker is available under the MIT license. See the LICENSE file for more info.
