# Cybrid CocoaPods placeholders

These trunk names belong to Cybrid and hold inert placeholders so they cannot be registered by anyone else.
They contain no functionality and are deliberately macOS-only.

Cybrid's Swift API clients and iOS SDK are published from our own spec repo. Add it to your Podfile **before** the trunk CDN:

```ruby
source 'https://github.com/Cybrid-app/cybrid-podspecs.git'
source 'https://cdn.cocoapods.org/'
```
