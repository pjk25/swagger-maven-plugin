**02/01/2014 2.0.0-SNAPSHOT**
- 02/01/2014 fully support swagger spec [1.2](https://github.com/wordnik/swagger-core/wiki/1.2-transition)
             Fix issue #33 #35 #31 #20 #29
- 02/01/2014 Fix issue #32



**01/20/2014 1.1.3-SNAPSHOT**
- 01/20/2014： *revert pull #27*
- 01/20/2014： *accept pull #22*
- 01/20/2014： *fix path issue when `useOutputFlatStructure` is false*

**01/19/2014 1.1.2**
- 01/19/2014： *accept pull #27*
- 01/19/2014： *accept pull #28*
- 07/18/2013:  *add `useOutputFlatStructure` and `mustacheFileRoot` in configuration.* 
- 07/23/2013:  *Maven 3.1.0 compat (pull#15)*
- 07/31/2013:  *fix issue #17*

**07/16/2013 1.1.1**
- released in central repository
- fix issue #7

-----

**07/03/2013 1.1.0**
- 1.1.0 released in central repository

-----

**06/26/2013 1.1-SNAPSHOT**
- Upgrade [mustache lib]https://github.com/spullara/mustache.java to 0.8.12
- Support remote url for outputTemplatePath

-----

**06/21/2013 1.1-SNAPSHOT**
- Use swagger 1.2.5 which supports generic classes in response, thanks the author accept my pull request
- Support document response class with generic class
- Support document response header by using:
  ```
  @ApiParamsImplicit(value = {
                        @ApiParamImplicit(name = "ETag", 
                                          paramType = "response_header",
                                          value = "version", dataType = "string")})
  ```
- use requestHeader, requestBody, responseHeader, requestPath and requestQuery to help document maker distinguish parameters
- fix issue #9

