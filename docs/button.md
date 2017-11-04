---
layout: docs
title:  "Button"
themeable: true
responsive: false
---
{% include doc-header.html %}

Use a button on an anchor tag to link out of an email.

**Note:** Only to be used with anchor <code>&lt;a&gt;</code> tag.

<span class="text-danger">Warning:</span> you must supply a url in the href. Using just pound sign is not enough for some emails to render an anchor tag correctly.

{% highlight html %}
<a href="https://bootstrapemail.com" class="btn btn-primary">Primary</a>
<a href="https://bootstrapemail.com" class="btn btn-secondary">Secondary</a>
<a href="https://bootstrapemail.com" class="btn btn-success">Success</a>
<a href="https://bootstrapemail.com" class="btn btn-danger">Danger</a>
<a href="https://bootstrapemail.com" class="btn btn-warning">Warning</a>
<a href="https://bootstrapemail.com" class="btn btn-info">Info</a>
<a href="https://bootstrapemail.com" class="btn btn-light">Light</a>
<a href="https://bootstrapemail.com" class="btn btn-dark">Dark</a>
{% endhighlight %}

<a href="#" class="btn btn-primary">Primary</a>
<a href="#" class="btn btn-secondary">Secondary</a>
<a href="#" class="btn btn-success">Success</a>
<a href="#" class="btn btn-danger">Danger</a>
<a href="#" class="btn btn-warning">Warning</a>
<a href="#" class="btn btn-info">Info</a>
<a href="#" class="btn btn-light">Light</a>
<a href="#" class="btn btn-dark">Dark</a>

## Sizes
{% highlight html %}
<a href="https://bootstrapemail.com" class="btn btn-primary btn-lg">Large button</a>
<a href="https://bootstrapemail.com" class="btn btn-secondary btn-lg">Large button</a>
{% endhighlight %}

<a href="#" class="btn btn-primary btn-lg">Large button</a>
<a href="#" class="btn btn-secondary btn-lg">Large button</a>
