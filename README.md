# transmart-gwas-plink
Plink integration for tranSMART

Installation
------------

Add the following entry into "inlinePlugins":

  'transmart-gwas-plink': 'transmart-gwas-plink'

and the following entry into "InternalDependenciesFilter":

  compile ":transmart-gwas-plink:$transmartVersion"

in file "DependencyManagement.groovy"

Add the following lines into Config.groovy:

  grails.plugin.transmartGwasPlink.enabled=true
  grails.plugin.transmartGwasPlink.plinkPath='/usr/local/bin/plink'

(the value of the last parameter depends on where you've installed plink binary).

Usage
-----

See wiki: https://github.com/ThomsonReuters-LSPS/transmart-gwas-plink/wiki
