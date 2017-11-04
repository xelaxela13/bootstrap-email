---
layout: docs
title:  "Container"
bs-compatable: true
color-classes: false
---
{% include post-header.html %}

Wrap you page content in a container to bring the content in tighter and center align in the page

You can use a card with out without a <code>.card-body</code>. Just like in Bootstrap a <code>.card-body</code> is just used to give padding to the card.

### Container
{% highlight html %}
<div class="container">
  <!-- Content here -->
</div>
{% endhighlight %}

<div class="container">
  <!-- Content here -->
</div>

### Container fluid

A fluid container is unlike a container in that it doesn't have it's max-width set. It does however still have padding on the edges to make the content bad better space towards the edge of the email.

{% highlight html %}
<div class="container-fluid">
  <!-- Content here -->
</div>
{% endhighlight %}

<div class="container-fluid">
  <!-- Content here -->
</div>
