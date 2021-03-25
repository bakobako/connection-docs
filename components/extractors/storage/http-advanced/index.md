---
title: HTTP Advanced 
permalink: /components/extractors/storage/http-advanced/
redirect_from:
    - /extractors/storage/http-advanced/
---

* TOC
{:toc}

This extractor downloads a HTTP resource with custom headers and request parameters. 
For more simple HTTP extraction use the [HTTP extractor](/components/extractors/storage/http).

## Configuration
[Create a new configuration](/components/#creating-component-configuration) of the **HTTP Advanced** extractor.
View the configuration description for an example configuration. Fill in the path to the endpoint, the headers to send, 
additional request parameters, and user parameters. More details on the configuration of these parameters can be found
in the [Bitbucket repository](https://bitbucket.org/kds_consulting_team/kds-team.ex-http-extended/src/master/README.md).

{: .image-popup}
![Screenshot - Base URL](/components/extractors/storage/http-advanced/http-advanced-1.png)

### Dynamic Functions

The application support functions that may be applied on parameters in the configuration to get dynamic values.
Fill in these functions in the user parameters. Place the required function object instead of the user parameter value.