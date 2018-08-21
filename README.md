# Mantle YotPo Integration

[![license](http://img.shields.io/badge/license-CC0%201.0%20Universal-blue.svg)](https://github.com/moqui/mantle-yotpo/blob/master/LICENSE.md)

Mantle integration with YotPo (www.yotpo.com) for site and product reviews.

See API docs at: https://apidocs.yotpo.com/reference

To add this component to Moqui the easiest approach is to use the Gradle get component task:

    $ ./gradlew getComponent -Pcomponent=mantle-yotpo

Or add a dependency in your component.xml file like:

    <depends-on name="mantle-yotpo"/>