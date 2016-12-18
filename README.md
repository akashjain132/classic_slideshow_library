# Classic Slideshow #

Classic Slideshow is a lightweight javascript plugin which gives slider with caption on that.

# Getting started #

 Just clone this reporistory.

   * git clone git@github.com:innoraft/classic_slideshow.git

Include css and js file in your HTML

###### <!-- Javascript --&gt;
&lt;script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js">&lt;/script>
&lt;script src="js/uikit.min.js" type="text/javascript"></script>
&lt;script src="js/uikit-core-components.js" type="text/javascript"></script>

###### &lt;!-- CSS -->
&lt;link rel="stylesheet" href="css/theme.css">

###### &lt;!-- HTML structure -->
```html
<div class="tm-slideshow-default uk-slidenav-position" data-uk-slideshow="{autoplay:true, animation: 'scale', pauseOnHover: true, duration: 500, autoplayInterval: 10000, kenburns: false}">
  <ul class="uk-slideshow uk-overlay-active"><li><img src="images/demo/default/slider/1.jpg" width="1200" height="500" alt="demo"></li>
    <li><img src="images/demo/default/slider/2.jpg" width="1200" height="500" alt="demo"></li>
    <li><img src="images/demo/default/slider/3.jpg" width="1200" height="500" alt="demo"></li>
  </ul>

<!-- Pager -->
<div class="uk-margin">
    <ul class="uk-dotnav uk-flex-center uk-hidden-touch">
      <li data-uk-slideshow-item="0"><a href=""></a></li>
      <li data-uk-slideshow-item="1"><a href=""></a></li>
      <li data-uk-slideshow-item="2"><a href=""></a></li>
    </ul>
  </div>

<!-- Next and Previosu button -->
  <a href="" class="uk-slidenav uk-slidenav-previous" data-uk-slideshow-item="previous"></a>
  <a href="" class="uk-slidenav uk-slidenav-next" data-uk-slideshow-item="next"></a>
</div>
```

# Configuration #

You can change these parameter in HTML

| Parameters | Description |
| --- | --- |
| `autoplay` | Set it to true to have the slideshow play automatically. Otherwise, set to false to stop the automatic play. |
| `animation` | Set the transition animation between slides |
| `transition_duration` | set the duration for the transition animation |
| `autoplay_interval` | Set the duration between switching slideshow items |
| `kenburns` | Set it to true or false to enable/disable kenburns effect to an image |

# Example #

You will find a file named index.html. Open the file in your browser to see the demo.

# Credit #

[Arrow Themes](https://arrowthemes.com/demo/html/sandal/index.php?page=elements-slideshow#.)
