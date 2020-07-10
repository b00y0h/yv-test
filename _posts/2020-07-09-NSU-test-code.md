---
layout: post
title: "NSU Test Code for IWC"
date: 2020-07-09 12:02:47 -0400
categories: test-code
---

{% capture styles %}
{% include main.scss %}
{% endcapture %}

<style>
{{ styles | scssify }}
</style>

## For Testing Purposes ONLY

Sample page: [https://www.youvisit.com/eabsample/nsu-iwc/](https://www.youvisit.com/eabsample/nsu-iwc/)

### Please note:

- The tour/IWC consists of two parts, the embed code (the `<div></div>` parts) and the script tag (the `<script></script` part).
- The script tag only needs to be placed once per page
- Script tag must be placed below the embed code.
- If you will be placing multiple tours/IWCs on a page, simply copy/paste the embed code for each tour and place one script tag below the tours.
- You'll notice on this page that each code example includes the script tag. This is not needed unless it's the last one on the page

#### 1st Embed

<div style="position:relative;">
 <div style="margin-left:auto; margin-right: auto;width:1440px;height:460px;">
  <a href="https://www.youvisit.com" class="virtualtour_embed"
     title="Virtual Reality, Virtual Tour"
     data-platform="v"
     data-link-type="immersive"
     data-inst="62610"
     data-image-width="100%"
     data-image-height="100%"
     data-image-quality="20">Virtual Tour</a>
 </div>
</div>

##### Code

{% highlight html %}

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 1440px; height: 460px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="v"
      data-link-type="immersive"
      data-inst="62610"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      >Virtual Tour</a
    >
  </div>
</div>
<script
  async="async"
  defer="defer"
  src="https://www.youvisit.com/tour/Embed/js3"
></script>

{% endhighlight %}

#### 2nd Embed

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 600px; height: 400px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="w"
      data-link-type="immersive"
      data-inst="78506"
      data-type="inline-embed"
      data-stopid="273479"
      data-load-stop-only="1"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      data-capabilities="48"
      data-loc="142970"
      >Virtual Tour</a
    >
    <script
      async="async"
      defer="defer"
      src="https://www.youvisit.com/tour/Embed/js3"
    ></script>
  </div>
</div>

##### Code

{% highlight html %}

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 600px; height: 400px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="w"
      data-link-type="immersive"
      data-inst="78506"
      data-type="inline-embed"
      data-stopid="273479"
      data-load-stop-only="1"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      data-capabilities="48"
      data-loc="142970"
      >Virtual Tour</a
    >
    <script
      async="async"
      defer="defer"
      src="https://www.youvisit.com/tour/Embed/js3"
    ></script>
  </div>
</div>
<script async="async" defer="defer" src="https://www.youvisit.com/tour/Embed/js3"></script>
{% endhighlight %}

#### 3rd Embed

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 1440px; height: 460px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="v"
      data-link-type="immersive"
      data-inst="78506"
      data-type="inline-embed"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      data-loc="142971"
      >Virtual Tour</a
    >
  </div>
</div>

##### Code

{% highlight html %}

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 1440px; height: 460px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="v"
      data-link-type="immersive"
      data-inst="78506"
      data-type="inline-embed"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      data-loc="142971"
      >Virtual Tour</a
    >
  </div>
</div>
<script async="async" defer="defer" src="https://www.youvisit.com/tour/Embed/js3"></script>
{% endhighlight %}

#### 4th Embed

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 1440px; height: 600px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="v"
      data-inst="78506"
      data-type="inline-embed"
      data-stopid="273504"
      data-load-stop-only="1"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      data-capabilities="96"
      data-loc="142970"
      >Virtual Tour</a
    >
  </div>
</div>

##### Code

{% highlight html %}

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 1440px; height: 600px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="v"
      data-inst="78506"
      data-type="inline-embed"
      data-stopid="273504"
      data-load-stop-only="1"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      data-capabilities="96"
      data-loc="142970"
      >Virtual Tour</a
    >
  </div>
</div>

<script
  async="async"
  defer="defer"
  src="https://www.youvisit.com/tour/Embed/js3"
></script>

{% endhighlight %}

#### 5th Embed

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 450px; height: 300px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="w"
      data-link-type="immersive"
      data-inst="78506"
      data-type="inline-embed"
      data-stopid="273531"
      data-load-stop-only="1"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      data-capabilities="96"
      data-loc="142970"
      >Virtual Tour</a
    >
  </div>
</div>

##### Code

{% highlight html %}

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 450px; height: 300px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="w"
      data-link-type="immersive"
      data-inst="78506"
      data-type="inline-embed"
      data-stopid="273531"
      data-load-stop-only="1"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      data-capabilities="96"
      data-loc="142970"
      >Virtual Tour</a
    >
  </div>
</div>
<script
  async="async"
  defer="defer"
  src="https://www.youvisit.com/tour/Embed/js3"
></script>

{% endhighlight %}

#### 6th Embed

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 1440px; height: 600px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="v"
      data-link-type="immersive"
      data-inst="78506"
      data-type="inline-embed"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      data-loc="142977"
      >Virtual Tour</a
    >
  </div>
</div>

##### Code

{% highlight html %}

<div style="position: relative;">
  <div
    style="margin-left: auto; margin-right: auto; width: 1440px; height: 600px;"
  >
    <a
      href="https://www.youvisit.com"
      class="virtualtour_embed"
      title="Virtual Reality, Virtual Tour"
      data-platform="v"
      data-link-type="immersive"
      data-inst="78506"
      data-type="inline-embed"
      data-image-width="100%"
      data-image-height="100%"
      data-image-quality="20"
      data-loc="142977"
      >Virtual Tour</a
    >
  </div>
</div>

<script
  async="async"
  defer="defer"
  src="https://www.youvisit.com/tour/Embed/js3"
></script>

{% endhighlight %}

<script async="async" defer="defer" src="https://www.youvisit.com/tour/Embed/js3"></script>
