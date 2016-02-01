---
layout: page
title: Professional experience
permalink: /resume/professional-experience/
---

{% highlight js %}
Object.create(Company.prototype, {
  "name": { value: "CINQ Technologies" },
  "admissionDate": { value: "August 1, 2015" },
  "atributions": {
    value: "Working in international projects."
  },
  "frameworks": {
    value: "DOJO"
  }
})
{% endhighlight %}

{% highlight c# %}

Company company = new Company();
company.Name = "End2End Systems";
company.AdmissionDate = "January 1, 2012";
company.Atributions =
  "User centred system development, with fast response, " +
  "accessability, information archtecture, " +
  "always looking for innovative solutions.";
company.frameworks = new List<String>() {};
{% endhighlight %}

{% highlight js %}
Object.create(Company.prototype, {
  "name": { value: "Systrac" },
  "admissionDate": { value: "March 1, 2012" },
  "demissionDate": { value: "June 12, 2014" },
  "atributions": {
    value: "Architecture and development of web based systems
      for real time tracking vehicles."
  },
  "languages": {
    value: [
      "javascript",
      "java",
      "c#",
      "html",
      "xml",
      "JSON",
      "css",
      "Delphi"
    ]
  },
  "frameworks": {
    value: [
      ".NET",
      "Silverlight",
      "WebApi",
      "ASP.NET",
      "MVC",
      "Razor",
      "Entity",
      "Framework",
      "Bootstrap",
      "KnockoutJS",
      "jQuery"
    ]
  }
})
{% endhighlight %}