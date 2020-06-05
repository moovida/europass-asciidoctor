# europass-asciidoctor

A asciidoc example for recreating the Europass Curriculum Vitae


* you need to have [**asciidoctor-pdf**](https://asciidoctor.org/docs/asciidoctor-pdf/) installed
* the folder contains an example pdf produced
* to build the contained resume.adoc file, run build.sh (linux, macos) or from terminal:

```
asciidoctor-pdf -a pdf-themesdir=./resources/themes/ -a pdf-theme=curricola resume.adoc
```

