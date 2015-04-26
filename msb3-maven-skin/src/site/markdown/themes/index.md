# Themes

Msb3 skin builds on [Twitter Bootstrap][bootstrap] and supports predefined and custom
Bootstrap themes. They are set using the `<theme>` element in the customization:

[bootstrap]: http://getbootstrap.com/

```xml
<custom>
  <msb3Skin>
    ...
    <theme>default|site|bootswatch-*</theme>
    ...
  </msb3Skin>
</custom>
```

There are several options for the `<theme>` value:

-   **`default`**
    
    (**Default**: will be used if `<theme>` is not set).
    
    Default Bootstrap theme (version 2.1.1). The default theme (with minor customizations)
    is used for this website.
    
    The default Bootstrap theme is loaded from the
    [BootstrapCDN Content Delivery Network][bootstrapcdn], which improves website loading
    by hosting the Bootstrap CSS and JavaScript files.

-   **`site`**
    
    A customized (local) Bootstrap theme. This option should be used when a custom Bootstrap
    theme is developed and included with the Maven site. The theme expects the following
    Bootstrap CSS and JavaScript files to be available in `src/site/resources`:
    
    -   `css/bootstrap.min.css`
    -   `css/bootstrap-responsive.min.css`
    -   `js/bootstrap.min.js`
    
    The files can be customized and generated at [Bootstrap's Customize page][bootstrap-custom].

-   **`bootswatch-*`**<span id="theme-bootswatch"></span>
    
    One of free Bootstrap themes from [Bootswatch][bootswatch]. Append the lowercase theme name
    in the [Bootswatch gallery][bootswatch-gallery], e.g. `bootswatch-readable`.
    
    Bootswatch themes (version 2.1.0) are loaded from the
    [BootstrapCDN Content Delivery Network][bootstrapcdn].
    
    Preview full themes at the [Bootswatch gallery][bootswatch-gallery],
    or check out several examples of Msb3 skin using Bootswatch themes below.

[bootstrapcdn]: http://bootstrapcdn.com
[bootstrap-custom]: http://getbootstrap.com/customize
[bootswatch]: http://bootswatch.com
[bootswatch-gallery]: http://bootswatch.com/#gallery

---


### [Cerulean][theme-cerulean]

[![Cerulean Bootswatch theme](../img/bootswatch-cerulean.png)][theme-cerulean]

```xml
<theme>bootswatch-cerulean</theme>
```

[theme-cerulean]: bootswatch-cerulean.html


### [Cosmo][theme-cosmo]

[![Cosmo Bootswatch theme](../img/bootswatch-cosmo.png)][theme-cosmo]

```xml
<theme>bootswatch-cosmo</theme>
```

[theme-cosmo]: bootswatch-cosmo.html


### [Cyborg][theme-cyborg]

[![Cyborg Bootswatch theme](../img/bootswatch-cyborg.png)][theme-cyborg]

```xml
<theme>bootswatch-cyborg</theme>
```

[theme-cyborg]: bootswatch-cyborg.html


### [Darkly][theme-darkly]

[![Darkly Bootswatch theme](../img/bootswatch-darkly.png)][theme-darkly]

```xml
<theme>bootswatch-darkly</theme>
```

[theme-darkly]: bootswatch-darkly.html


### [Flatly][theme-flatly]

[![Flatly Bootswatch theme](../img/bootswatch-flatly.png)][theme-flatly]

```xml
<theme>bootswatch-flatly</theme>
```

[theme-flatly]: bootswatch-flatly.html


### [Journal][theme-journal]

[![Journal Bootswatch theme](../img/bootswatch-journal.png)][theme-journal]

```xml
<theme>bootswatch-journal</theme>
```

[theme-journal]: bootswatch-journal.html


### [Lumen][theme-lumen]

[![Lumen Bootswatch theme](../img/bootswatch-lumen.png)][theme-lumen]

```xml
<theme>bootswatch-lumen</theme>
```

[theme-lumen]: bootswatch-lumen.html


### [Paper][theme-paper]

[![Paper Bootswatch theme](../img/bootswatch-paper.png)][theme-paper]

```xml
<theme>bootswatch-paper</theme>
```

[theme-paper]: bootswatch-paper.html


### [Readable][theme-readable]

[![Readable Bootswatch theme](../img/bootswatch-readable.png)][theme-readable]

```xml
<theme>bootswatch-readable</theme>
```

[theme-readable]: bootswatch-readable.html


### [Sandstone][theme-sandstone]

[![Sandstone Bootswatch theme](../img/bootswatch-sandstone.png)][theme-sandstone]

```xml
<theme>bootswatch-sandstone</theme>
```

[theme-sandstone]: bootswatch-sandstone.html


### [Simplex][theme-simplex]

[![Simplex Bootswatch theme](../img/bootswatch-simplex.png)][theme-simplex]

```xml
<theme>bootswatch-simplex</theme>
```

[theme-simplex]: bootswatch-simplex.html


### [Slate][theme-slate]

[![Slate Bootswatch theme](../img/bootswatch-slate.png)][theme-slate]

```xml
<theme>bootswatch-slate</theme>
```

[theme-slate]: bootswatch-slate.html


### [Spacelab][theme-spacelab]

[![Spacelab Bootswatch theme](../img/bootswatch-spacelab.png)][theme-spacelab]

```xml
<theme>bootswatch-spacelab</theme>
```

[theme-spacelab]: bootswatch-spacelab.html


### [Superhero][theme-superhero]

[![Superhero Bootswatch theme](../img/bootswatch-superhero.png)][theme-superhero]

```xml
<theme>bootswatch-superhero</theme>
```

[theme-superhero]: bootswatch-superhero.html


### [United][theme-united]

[![United Bootswatch theme](../img/bootswatch-united.png)][theme-united]

```xml
<theme>bootswatch-united</theme>
```

[theme-united]: bootswatch-united.html


### [Yeti][theme-yeti]

[![Yeti Bootswatch theme](../img/bootswatch-yeti.png)][theme-yeti]

```xml
<theme>bootswatch-yeti</theme>
```

[theme-yeti]: bootswatch-yeti.html



### [And more..][bootswatch-gallery]

Check out all themes at [Bootswatch gallery][bootswatch-gallery].

```xml
<theme>bootswatch-*</theme>
```


---

All theme images above are from the [Bootswatch gallery][bootswatch-gallery].

