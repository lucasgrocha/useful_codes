### SVG Icon Generator

```ruby
require "icodi"

print 'Type some text: '
text = gets.chomp

icon = Icodi.new text, pixels: 5, density: 0.5, mirror: :x

icon.save 'icon'
```
