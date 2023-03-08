# Support for importing Maven based DevKit Plugin projects.<br>

Hacks module type from `JAVA_MODULE` to `PLUGIN_MODULE`.
Why this is needed today? 
Modern way to develop Intellij Idea plugins is to use [Gradle IntelliJ Plugin](https://github.com/JetBrains/gradle-intellij-plugin) as DevKit is deprecated for a while.  
However DevKit way has own benefits: 
- seamless debugging;
- support for hot code swap.

Used as alternative to outdated [ijdevkitmvn](https://plugins.jetbrains.com/plugin/7127-intellij-plugin-development-with-maven) and currently tested to be working with Idea 2023.1 Beta

Pre-build [binary](distr/).