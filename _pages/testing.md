---
permalink: /testing/
title: "Testing"
# author_profile: true
redirect_from: 
  - /testing.html
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
![Karate Certificate]({{ site.baseurl }}/simple/images/IMG_4124.jpeg){:width="100%"}

![Karate Certificate](/simple/images/IMG_4124.jpeg){:width="100%"}

![Karate Certificate]({{"/simple/images/IMG_4124.jpeg" | relative_url}}){:width="100%"}
```

Preview:
![Karate Certificate]({{ site.baseurl }}/simple/images/IMG_4124.jpeg){:width="100%"}

![Karate Certificate](/simple/images/IMG_4124.jpeg){:width="100%"}

![Karate Certificate]({{"/simple/images/IMG_4124.jpeg" | relative_url}}){:width="100%"}

# Videos (using html snippet)

```
{% raw %}
  {% include youtube.html id="oH0TWLY-OvQ" %}
{% endraw %}
```

which evaluates to 

```
{% include youtube.html id="oH0TWLY-OvQ" %}
```

Preview:
{% include youtube.html id="oH0TWLY-OvQ" %}




