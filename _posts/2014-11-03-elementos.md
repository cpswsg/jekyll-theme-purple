---
layout: post
title: "Elementos"
tags: [tag1]
description: "Just an assorted selection of elements."
---

# Heading Level 1

## Heading Level 2

### Heading Level 3

#### Heading Level 4

##### Heading Level 5

###### Heading Level 6

---

### Text

This is __bold__ and this is **strong**. This is _italic_ and this is *emphasized*.

This is <sup>superscript</sup> text and this is <sub>subscript</sub> text.

This is <u>underlined</u> and this is code: ```for (;;) { ... }```.

Finally, [this is a link](#).

---

#### Blockquote
> Fringilla nisl. Donec accumsan interdum nisi, quis tincidunt felis sagittis eget tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan faucibus. Vestibulum ante ipsum primis in faucibus lorem ipsum dolor sit amet nullam adipiscing eu felis.

#### Preformatted

    i = 0;

		while (!deck.isInOrder()) {
    	print 'Iteration ' + i;
    	deck.shuffle();
    	i++;
		}

		print 'It took ' + i + ' iterations to sort the deck.';

---

#### Highlight

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

---

### Lists

#### Unordered
+ Dolor pulvinar etiam magna etiam.
+ Sagittis adipiscing lorem eleifend.
+ Felis enim feugiat dolore viverra.


#### Ordered

1. Dolor pulvinar etiam magna etiam.
1. Etiam vel felis at lorem sed viverra.
1. Felis enim feugiat dolore viverra.
1. Dolor pulvinar etiam magna etiam.
1. Etiam vel felis at lorem sed viverra.
1. Felis enim feugiat dolore viverra.