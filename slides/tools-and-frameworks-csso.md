##  Tools and frameworks: [CSSO](http://bem.info/tools/csso/)

    .primary-navigation {
      font-size: 12px;
      color: red;
      font-weight: bold;
    }

    .secondary-navigation {
      color: red;
      font-weight: bold;
    }

To...

    .primary-navigation{
      font-size:12px
    }
    .primary-navigation, .secondary-navigation{
      color:red;
      font-weight:bold
    }

<aside data-markdown class="notes">
    Yandex's CSS Optimizer is helpful for cleaning up
    repeated properties.  It will handle tasks like
    merging blocks with identical properties.
</aside>
