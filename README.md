# Pitman-Translator
An English to Pitman Shorthand translator using the CMULexicon for pronunciation.

## What is Shorthand?
Shorthand is an abbreviated symbolic writing method that increases speed and brevity of writing. Historically 
it has been used to take down speeches and public addresses verbatim during speech, and then is recorded in
long hand later. This is the reason that we have so many verbatim records from ancient Rome, and other sources
from before recording technology was available.

## What is Pitman?
There are many forms of shorthand, each with their own quirks and benefits. Pitman Shorthand is one of these forms.
It was developed in 1837 by a Sir Isaac Pitman. It combines thin and broad strokes to get more meaning out of 
minimal different forms. It is based purely on phonetics, so it is not language specific. However, this makes 
machine transcribing difficult since there needs to be a pronunciation guide for each locale, instead of just 
going through the characters. 

## So what does this program do?
This program takes a sentence(At the moment only in English) and displays the Pitman shorthand representation
of that sentence. 

## How do I run it?

You need Java and Maven installed on your system.

You can compile the code by running `mvn clean install`.

You can run the code by running `java -Djdk.gtk.version=2 -jar target/Pitman-Translator-1.0-SNAPSHOT-jar-with-dependencies.jar`.

### Ubuntu

* [Install JVM](https://docs.aws.amazon.com/corretto/latest/corretto-21-ug/generic-linux-install.html)
* Install Maven - `sudo apt-get install maven`

Then run from project root with: `./bin/go.sh`
(Wraps the above commands in single line run script)

## Important notice

The .png images that are used for drawing shorthand are temporary and are for testing purposes only. 
They have been take from [this](http://www.long-live-pitmans-shorthand.org.uk/index.htm) 
very nice site that you can visit to learn about shorthand yourself! I highly recommend their resources, 
and have learned a lot from them.
