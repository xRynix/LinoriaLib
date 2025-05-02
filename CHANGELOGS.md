### 27.4.2025
```diff
+ Fixed an issue where clicking on the UI would click on in-game UI
+ You can now move the UI in first person
```

### 10.3.2025
```diff
+ Callback (OnChanged) in ColorPickers now return the color and transparency (PR #31 - ty RectangularObject)
```

### 14.2.2025
```diff
+ Fixed AddValues and AddDisabledValues missing in certain Dropdowns
+ Fixed certain issues with Tooltips, Notifications and unloading (ty RectangularObject for the PR)
```

### 12.02.2025
```diff
+ Added Notification:ChangeTitle, Notification:ChangeDescription
```

### 31.01.2025
```diff
+ Added AddDropdown as an Addon
```

### 18.01.2025
```diff
+ Added ReturnInstanceInstead for Dropdowns (Will return Team/Player instance with SpecialType dropdowns if set to true)
+ Better Library:SafeCallback error messages (thanks deivid)
```

### 03.01.2025
```diff
+ Added FormatDisplayValue option for Dropdowns
+ Added MaxVisibleDropdownItems option for Dropdowns
+ Fixed Searchable dropdowns not closing properly
+ Improved Example.lua dropdowns
```

### 30.12.2024
```diff
+ Added Prefix and Suffix to Sliders (Slider:SetPrefix, Slider:SetSuffix)
+ Added Searchable Dropdowns
+ Added SubButton:SetText
+ Added Visible, Disabled, SetVisible and SetDisabled to Inputs
+ Added ExcludeLocalPlayer for Dropdowns (Player type)
+ Enabled RichText for labels
+ Fixed 'Team' type (Dropdowns) not being updated
+ Fixed 'AddTooltip' typo to 'AddToolTip'
+ OnChanged now uses SafeCallback
```
