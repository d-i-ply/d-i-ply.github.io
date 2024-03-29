---
title: "Layout: Header Video"
header:
  teaser: "assets/images/markup-syntax-highlighting-teaser.jpg"
  video:
    id: XsxDH4HcOWA
    provider: youtube
categories:
  - Layout
  - Uncategorized
tags:
  - video
  - layout
author: Cameron Stewart
---

This post should display a **header with a responsive video**, if the theme supports it.

## Settings

| Parameter  | Required     | Description |
|----------  |---------     | ----------- |
| `id`       | **Required** | ID of the video |
| `provider` | **Required** | Hosting provider of the video, either `youtube` or `vimeo` |


<iframe src="https://captures.lumalabs.ai/embed/rewarding-spellbinding-3d-156805?mode=slf&background=%23ffffff&color=%23000000&showTitle=false&loadBg=false&logoPosition=bottom-left&infoPosition=bottom-right&cinematicVideo=undefined&showMenu=false" width="375" height="500" frameborder="0" title="luma embed" style="border: none;"></iframe>


### YouTube

To embed the following YouTube video at url `https://www.youtube.com/watch?v=XsxDH4HcOWA` (long version) or `https://youtu.be/XsxDH4HcOWA` (short version) into a post or page's main content you'd use: 

```liquid
{% raw %}{% include video id="XsxDH4HcOWA" provider="youtube" %}{% endraw %}
```

{% include video id="XsxDH4HcOWA" provider="youtube" %}

To embed it as a video header you'd use the following YAML Front Matter

```yaml
header:
  video:
    id: XsxDH4HcOWA
    provider: youtube
```

### Vimeo

To embed the following Vimeo video at url `https://vimeo.com/212731897` into a post or page's main content you'd use: 

```liquid
{% raw %}{% include video id="212731897" provider="vimeo" %}{% endraw %}
```

{% include video id="212731897" provider="vimeo" %}

To embed it as a video header you'd use the following YAML Front Matter

```yaml
header:
  video:
    id: 212731897
    provider: vimeo
```
