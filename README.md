## Overview ##

This is a sample project to show how we can run Jmeter tests using the JMeter Analysis Maven Plugin.

It runs a Jmeter tests against a few URLs on www.github.com .

## Usage ##

  * look in `target/jmeter/report/` for the JMeter results file
  * look in `target/reports/` for the Report generated by the JMeter Analysis Maven Plugin

## URL lists ##

Test with different URL's by changing /src/test/uris.txt

## Configuration for Jenkins ##

* SCM Configuration : ![myimage-alt-tag] (https://i.imgur.com/iTTiPd2.png)

* Execute Goals with `verify -Pperformance`
