+++
title = "Test highlight"
date = "2015-10-10T13:07:31+02:00"
tags = ["ipsum"]
categories = ["lorem"]
banner = "img/banners/banner-5.jpg"
+++

{{< highlight html >}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}

[Linked post]({{< ref "linked-post.md" >}})