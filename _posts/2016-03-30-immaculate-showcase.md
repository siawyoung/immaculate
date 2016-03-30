---
layout: post
title: Immaculate Showcase
---

This is an example post showcasing the various features of [Immaculate](https://github.com/siawyoung/immaculate) and [Tufte CSS](https://github.com/edwardtufte/tufte-css). Refer to the Markdown source of this post for a better understanding!

And please feel free to modify Immaculate's template files to your liking. Immaculate is extremely minimal as far as usual blogging features are concerned.

# This is a H1.

## This is a H2.

### And this is a H3. Lower levels are not supported.

Here is a **bold**, an *italic*, and a [hyperlink](/#).

Now, presenting to you a block quote with a Tufte-styled footer:

{% blockquote Friedrich Nietzsche, Thus Spoke Zarathustra %}
But say, my brothers, what can the child do that even the lion could not do? Why must the preying lion still become a child? The child is innocence and forgetting, a new beginning, a game, a self-propelled wheel, a first movement, a sacred "Yes." For the game of creation, my brothers, a sacred "Yes" is needed: the spirit now wills his own will, and he who had been lost to the world now conquers the world.
{% endblockquote %}

This is a normal-sized image.

{% image /assets/images/sushi.jpg 600 400 %}

This is a full-width image.

{% image /assets/images/sf.jpg 1400 933 fw %}

(All images mine.)

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