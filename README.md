# Progressive Web Applications

Tutorial per creare applicazioni cross platform, ovvero applicazioni che funzionino su iOS e Android. 

## Adobe PhoneGap

Per poter creare le applicazioni utilizziamo il sito [Adobe PhoneGap](https://build.phonegap.com)

## Preparazione dei file

- Config.xml

```xml
<?xml version="1.0" encoding="UTF-8" ?>
<widget xmlns   = "http://www.w3.org/ns/widgets"
    xmlns:gap   = "http://phonegap.com/ns/1.0"
    id          = "com.phonegap.example"
    versionCode = "10"
    version     = "1.0.0" >

<!-- versionCode is optional and Android only -->

  <name>PhoneGap Example</name>

  <description>
      An example for phonegap build docs.
  </description>

  <author href="https://build.phonegap.com" email="support@phonegap.com">
      Hardeep Shoker
  </author>

</widget>
```

- index.html

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
