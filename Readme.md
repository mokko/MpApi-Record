# MpApi.Record
This project collects logic to process individual records in Zetcom's WebApi. 
Here "record" corresponds to moduleItem in Zetcom's xml format. By and large, the
logic we deal with here seems to be specific to the SPK's implementation, hence 
the code deserves its own package apart from MpApi. Splitting this package from MpApi 
also has the advantage that MpApi doesn't need Pillow to deal with exiv data in images.

This package focusses on methods, i.e. things to do with xml, to change it.

We start with one package, but in the future we want to add specific modules
MpApi.Record <-- first one
MpApi.Record.Multmedia <-- future
MpApi.Record.Object <-- future
MpApi.Record.Exhibition <-- future
...

