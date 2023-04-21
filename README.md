# HarryExtensionsSPM

## Installation

To install this package, import `https://github.com/pewepw/HarryExtensionsSPM` in SPM.

## Usage Example

```swift
let pointStackView = VerticalStackView(arrangedSubviews: [
            availableTitleLabel,
            pointLabel
        ])
addSubview(pointStackView)
pointStackView.anchor(top: topAnchor, leading: leadingAnchor, bottom: nil, trailing: nil, padding: .init(top: 10, left: 15, bottom: 0, right: 0), size: .init(width: 0, height: 40))
        
let profileStackView = HorizontalStackView(arrangedSubviews: [
      nameLabel,
      profileImage
    ], spacing: 10)
addSubview(profileStackView)
profileStackView.anchor(top: topAnchor, leading: pointStackView.trailingAnchor, bottom: nil, trailing: trailingAnchor, padding: .init(top: 10, left: 15, bottom: 0, right: 15), size: .init(width: 0, height: 40))
```

