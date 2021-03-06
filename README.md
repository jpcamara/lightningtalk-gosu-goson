# Gosu + Goson - Typeloading JSON

### See the presentation

http://www.youtube.com/watch?v=zoSliq8_Oxk

### Slides

https://docs.google.com/presentation/d/1GokZ-hIXqUhdJ-NtY-EB43Ch2ruBwwjOeNri77mmm04/edit#slide=id.p


## Using Gosu in an IDE

Unfortunately, at the moment Gosu is only available in Intellij (there is an eclipse plugin, but it's pretty badly out
of date and a bit buggy)

You can find out more about installing that here: http://gosu-lang.org/intellij.html

## Gosu features

Check src/main/GosuFeatures.gsp to check out some of the base Gosu features.

.gs is a gosu class

.gsp is a gosu program (the entry point, like main(String[] args))

.gsx is a gosu enhancement

## JSON Typeloading

When a project has the Gosu SDK selected and there is a typeloader jar on the classpath (in this case
goson-0.3-SNAPSHOT.jar), it will automatically typeload any file that is appropriate for that loader. In this case,
the project is picking up any .json files. Add your own .json files in to use them in a Gosu class/program