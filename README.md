# Progressive Web Applications

Tutorial per creare applicazioni cross platform, ovvero applicazioni che funzionino su iOS e Android. 

## Adobe PhoneGap

Per poter creare le applicazioni utilizzare il sito [Adobe PhoneGap](https://build.phonegap.com)

## Preparazione dei file

> config.xml [[Link]](http://docs.phonegap.com/phonegap-build/configuring/#example)

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

> Opzione 1 - index.html [[Link]](https://www.w3schools.com/html/) 

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

> Opzione 2 - index.html [[Link]](https://www.w3schools.com/html/)

```html
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="refresh" content="0; url='https://kiwidatascience.com'" />
  </head>
  <body>
  </body>
</html>
```

## Creazione delle Applicazioni

1. Recarsi sul sito Adobe PhoneGap
2. Accedere con un account gratuito (questo da la possibilità di lavorare ad una sola app).
3. Comprimere tutti i file necessari in un .zip e caricarlo sul sito.
4. Cliccare sul tasto "Build"

OSS: per creare un'applicazione iOS è necessario un'account sviluppatore.

## Installazione APP

### Android

Per installare l'applicazione è sufficiente scaricare il file apk o, in alternativa, inquadrare con la fotocamera il QRCode. Ovviamente il cellulare riconoscerà l'applicazione come non sicura. Se non risulta possibile continuare l'installazione è necessario recarsi nella sezione "Opzioni sviluppatore" e abilitare l'installazione da terze parti. 

### iOS

... to be done

## License
[MIT](https://choosealicense.com/licenses/mit/)
