---
title: "Habbatussauda Cair"
excerpt: "Foo Bar design system including logo mark, website design, and branding applications."
categories:
  - Portfolio
tags:
  - portfolio
  - image
header:
  image: foo-bar-identity.jpg
  teaser: produk/herbal/thumb/habatussauda-cair-thumb.jpg
gallery:
  - url: unsplash-gallery-image-1.jpg
    image_path: unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
  - url: unsplash-gallery-image-2.jpg
    image_path: unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
  - url: unsplash-gallery-image-3.jpg
    image_path: unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
categories : portfolio
layout: single
author_profile: true
---

The preferred way of using images is placing them in the `/images/` directory and referencing them with an absolute path. Prepending the filename with `{% raw %}{{ site.url }}{{ site.baseurl }}/images/{% endraw %}` will make sure your images display properly in feeds and such.

Standard image with no width modifier classes applied.

**HTML:**

```html
{% raw %}<img src="{{ site.url }}{{ site.baseurl }}/images/filename.jpg" alt="">{% endraw %}
```

**or Kramdown:**

```markdown
{% raw %}![alt]({{ site.url }}{{ site.baseurl }}/images/filename.jpg){% endraw %}
```

![Unsplash image 9]({{ site.url }}{{ site.baseurl }}/images/unsplash-image-9.jpg)

Image that fills page content container by adding the `.full` class with:

**HTML:**

```html
{% raw %}<img src="{{ site.url }}{{ site.baseurl }}/images/filename.jpg" alt="" class="full">{% endraw %}
```

**or Kramdown:**

```markdown
{% raw %}![alt]({{ site.url }}{{ site.baseurl }}/images/filename.jpg)
{: .full}{% endraw %}
```

![Unsplash image 10]({{ site.url }}{{ site.baseurl }}/images/unsplash-image-10.jpg)
{: .full}