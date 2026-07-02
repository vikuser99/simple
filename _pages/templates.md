---
permalink: /templates/
title: "Templates"
# author_profile: true
redirect_from: 
  - /testing.html
  - /templates.html
  - /testing/
---

# Images

## Not Recommended Way (Absolute Path)

```
![Karate Certificate](https://vikuser99.github.io/simple/images/IMG_4124.jpeg){:width="100%"}
```

Preview:
![Karate Certificate](https://vikuser99.github.io/simple/images/IMG_4124.jpeg){:width="100%"}

## Recommended Way (Relative Paths)

```
{% raw %}![Karate Certificate]({{ site.baseurl }}/simple/images/IMG_4124.jpeg){:width="100%"}

![Karate Certificate](/simple/images/IMG_4124.jpeg){:width="100%"}

![Karate Certificate]({{"/simple/images/IMG_4124.jpeg" | relative_url}}){:width="100%"}{% endraw %}
```

which all evaluate to 

```
![Karate Certificate](/simple/images/IMG_4124.jpeg){:width="100%"}
```

Preview:
![Karate Certificate]({{ site.baseurl }}/simple/images/IMG_4124.jpeg){:width="100%"}

![Karate Certificate](/simple/images/IMG_4124.jpeg){:width="100%"}

![Karate Certificate]({{"/simple/images/IMG_4124.jpeg" | relative_url}}){:width="100%"}

# Videos (using html snippet)

```
{% raw %}{% include youtube.html id="oH0TWLY-OvQ" %}{% endraw %}
```

which evaluates to 

```
{% include youtube.html id="oH0TWLY-OvQ" %}
```

Preview:
{% include youtube.html id="oH0TWLY-OvQ" %}

# Audio

```
<audio controls>
  <source src="{{ '/simple/assets/bageshree.m4a' | relative_url }}" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

Preview:
<audio controls>
  <source src="{{ '/simple/assets/bageshree.m4a' | relative_url }}" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>




