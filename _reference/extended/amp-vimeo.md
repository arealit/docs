---
layout: page
title: amp-vimeo
order: 24
---

<!---
Copyright 2015 The AMP HTML Authors. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS-IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->



<table>
  <tr>
    <td width="40%"><strong>Description</strong></td>
    <td>Displays a Vimeo video.</td>
  </tr>
  <tr>
    <td width="40%"><strong>Availability</strong></td>
    <td>Stable, but no validation.</td>
  </tr>
  <tr>
    <td width="40%"><strong>Required Script</strong></td>
    <td><code>&lt;script async custom-element="amp-vimeo" src="https://cdn.ampproject.org/v0/amp-vimeo-0.1.js">&lt;/script></code></td>
  </tr>
  <tr>
    <td width="40%"><strong>Examples</strong></td>
    <td><a href="https://github.com/ampproject/amphtml/blob/master/examples/vimeo.amp.html">vimeo.amp.html</a></td>
  </tr>
</table>

**Note:** Currently, no validations apply to this tag.

#### Example

With responsive layout, the width and height from the example should yield correct layouts for 16:9 aspect ratio videos:

{% highlight html %}
<amp-vimeo
    data-videoid="27246366"
    layout="responsive"
    width="500" height="281"></amp-vimeo>
{% endhighlight %}

#### Attributes

**data-videoid**

The Vimeo video id found in every Vimeo video page URL

E.g. in https://vimeo.com/27246366 27246366 is the video id.