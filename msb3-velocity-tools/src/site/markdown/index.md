# Msb3 Velocity tools

Msb3 skin provides custom tools for [Apache Velocity][velocity] to be used in Maven site
template. These objects are contributed to Velocity context and can be used within the template.
Refer to [Javadoc][javadoc-all] for each tool for more information.

-   **[`SkinConfigTool`][javadoc-config]** (key **$config**)

    Provides a uniform access to Maven site custom configuration options. Supports global and
    per-page configuration. See info on [_per-page configuration_][per-page-info] in Msb3 skin
    for an example of features it brings.
-   **[`HtmlTool`][javadoc-html]** (key **$htmlTool**)

    Provides methods to modify and query HTML text using [jsoup][jsoup] library.
-   **[`URITool`][javadoc-uri]** (key **$uriTool**)

    Provides URI utilities that expose URIs to the template.

[velocity]: http://velocity.apache.org/
[per-page-info]: ../skin/config.html#Per-page_configuration
[jsoup]: http://jsoup.org/

[javadoc-all]: apidocs/
[javadoc-config]: apidocs/lt/velykis/maven/skins/msb3/SkinConfigTool.html
[javadoc-html]: apidocs/lt/velykis/maven/skins/msb3/HtmlTool.html
[javadoc-uri]: apidocs/lt/velykis/maven/skins/msb3/URITool.html


## Usage

To enable these tools, add `msb3-velocity-tools` dependency to `maven-site-plugin` in the POM
file:

```xml
<build>
  <plugins>
    ...
    <plugin>
      <groupId>org.apache.maven.plugins</groupId>
      <artifactId>maven-site-plugin</artifactId>
      <version>3.3</version>
      <dependencies>
        ...
        <dependency>
          <groupId>pl.matsuo.maven.skins</groupId>
          <artifactId>msb3-velocity-tools</artifactId>
          <version>0.1.1-SNAPSHOT</version>
        </dependency>
        ...
      </dependencies>
      ...
    </plugin>
    ...
  </plugins>
</build>
```
