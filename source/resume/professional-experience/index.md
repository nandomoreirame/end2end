---
layout: page
title: Professional experience
permalink: /resume/professional-experience/
---

{% highlight js %}
function request(file) {
  fetch(file).then(function(response) {
    return response.json().then(function(json) {
      console.log(json);
    });
  });
}
{% endhighlight %}

{% assign experiences = site.experiences | sort: 'meta.admissiondate' | reverse %}
{% for experience in experiences reversed %}
  {{ experience.output }}
{% endfor %}