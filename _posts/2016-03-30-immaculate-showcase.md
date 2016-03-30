---
layout: post
title: Immaculate Showcase
---

This is an example post featuring the various features of Immaculate and Tuftes CSS. Please refer to the Markdown source for this post for a better understanding.

Please feel free to modify Immaculate's template files to your liking. I have kept them as terse as possible for this express purpose.

# This is a H1.

## This is a H2.

### And this is a H3. Lower levels are not supported.

Here is a **bold**, an *italic*, and a [hyperlink](/#).

This is a normal-sized image.

{% image /assets/images/sushi.jpg 600 400 %}

This is a full-width image.

{% image /assets/images/sf.jpg 1400 933 fw %}

This is a Youtube video.

{% youtube lBTCB7yLs8Y 600 300 %}

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod{% sidenote side1 This is a sidenote. %} tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur{% sidenote side2 This is another sidenote. %} sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% marginnote margin1 %}
This is a margin note.
{% endmarginnote %}

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% marginnote margin2 %}
Yet another margin note.
{% endmarginnote %}

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Here is a code block{% sidenote side3 I have not turned on syntax highlighting. Frankly, it can be distracting in this minimalistic environment. %}:

```ruby
class beautiful_ruby_class
  def initialize
    do_some_magical_stuff
  end

  def beautiful_method
    change_the_world
  end
end
```