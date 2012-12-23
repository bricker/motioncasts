## #4 – SugarCube and Geomotion

<http://motioncasts.tv/4-sugarcube-and-geomotion/>

Note that there seems to be some misinformation in the screencast (perhaps
caused by a newer version of iOS or something), so be sure to look at the
[source code for this screencast](https://github.com/michael-erasmus/motioncasts-geomotion-sugarcube)
while you're working on it.

Specifically, I had an `ArgumentError` on this line from the screencast:

```ruby
scroll.contentSize = CGRect.make(scroll_frame.width * 3, scroll_frame.height)
```

It's weird, because he actually types in `CGSizeMake()` instead of `CGRect.make()`,
but then there's a weird edit or something and it switches to the code which caused 
an error.

Keep in mind that I don't know WTF I'm doing so it's probably my fault.

:thumbsup: :sushi:
