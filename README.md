# ORXeC Test Framework

This multi-module [Gradle] project leverages [Geb] and [Spock] to create a behavior-driven development ([BDD]) web automation framework.
The executable specifications, written in [Groovy] , read like plain English.
The use of [Page Object] modeling ensures the maintainability and re-usability of code.

Multi-level logging is supported via [slf4j] and [logback]. A shared utility package is utilized to store common code.
There is seamless Integration with IntelliJ [IDEA], enabling easy step-by-step debugging and the testing of pipeline automation entry-points.

## Technologies Integrated

Software                |Version|Description
---                     |---    |---
[Groovy]                |2.4.7  |Apache Groovy is a powerful, optionally typed and dynamic language, with static-typing and static compilation capabilities. A powerful and expressive JVM ([Java]) language.
[Geb] 	                |1.0    |Geb is a browser automation solution.It brings together the power of WebDriver, the elegance of jQuery content selection, the robustness of Page Object modelling and the expressiveness of the Groovy language.
[Spock]	                |1.1    |[BDD] test/specification runner.Spock is a testing and specification framework. It stand out from the crowd because of its beautiful and highly expressive specification language.
[Gradle]                |3.2    |Build tool & dependency management
[Selenium] (WebDriver)  |3.0.1  |Browser automation API
[ChromeDriver]          |2.25   |Selenium driver for Chrome
[GeckoDriver]           |0.11.1 |Selenium driver for Mozilla
[slf4j]                 |1.7.21 |Logging API
[logback]               |1.1.7  |Logging implementation

## References


[Groovy]                |http://groovy-lang.org/
[Geb] 	                |http://gebish.org
[Spock]	                |http://spockframework.org
[BDD]					|https://en.wikipedia.org/wiki/Behavior-driven_development
[Gradle]                |https://gradle.org
[Selenium] (WebDriver)  |http://docs.seleniumhq.org
[Grid]					|https://github.com/SeleniumHQ/docker-selenium
[ChromeDriver]          |https://sites.google.com/a/chromium.org/chromedriver
[GeckoDriver]           |https://github.com/mozilla/geckodriver
[slf4j]                 |http://www.slf4j.org
[logback]               |http://logback.qos.ch
[IDEA]					|https://www.jetbrains.com/idea