# FederatedPhacts

This repo explores lightweight ways of integrating distributed data from the variety of life science infrastructures already available from a variety of organizations. 

There are two key approaches:
* Using Federated SPARQL queries
   * Example: [Compare MW, logP and PSA for known oxidoreductase inhibitors](https://github.com/openphacts/FederatedPhacts/issues/3)
* Exposing encapuslated sparql queries as web apis through [grlc.io](http://grlc.io). 
   * Example: [FederatedPhacts API](http://grlc.io/api/openphacts/FederatedPhacts/)

Both APIs and SPARQL queries can be combined using juypter notebooks. Examples of test cases can be found in the notebook directory and executed using Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/openphacts/FederatedPhacts/master?filepath=notebooks)
