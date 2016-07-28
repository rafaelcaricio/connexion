# Change Log

## [Unreleased](https://github.com/zalando/connexion/tree/HEAD)

[Full Changelog](https://github.com/zalando/connexion/compare/1.0.107...HEAD)

**Implemented enhancements:**

- Don't send back entire schema after validation errors [\#234](https://github.com/zalando/connexion/issues/234)

**Fixed bugs:**

- OAuth token should have all scopes listed in swagger spec to grant access [\#256](https://github.com/zalando/connexion/issues/256)

**Merged pull requests:**

- Fix security check [\#257](https://github.com/zalando/connexion/pull/257) ([rafaelcaricio](https://github.com/rafaelcaricio))

## [1.0.107](https://github.com/zalando/connexion/tree/1.0.107) (2016-07-22)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.103...1.0.107)

**Closed issues:**

- Raise original exception while importing modules [\#250](https://github.com/zalando/connexion/issues/250)
- UnicodeDecodeError: 'gbk' codec can't decode byte 0xaf in position [\#249](https://github.com/zalando/connexion/issues/249)
- Stricter requirements.txt? [\#246](https://github.com/zalando/connexion/issues/246)

**Merged pull requests:**

- Open spec file as binary and then handle problems with encoding. [\#252](https://github.com/zalando/connexion/pull/252) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Isort imports [\#248](https://github.com/zalando/connexion/pull/248) ([dimbleby](https://github.com/dimbleby))
- Don't send back entire API schema to clients after validation failures [\#236](https://github.com/zalando/connexion/pull/236) ([jvinet](https://github.com/jvinet))

## [1.0.103](https://github.com/zalando/connexion/tree/1.0.103) (2016-06-08)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.98...1.0.103)

**Closed issues:**

- Connexion hides real errors in endpoint handling module [\#218](https://github.com/zalando/connexion/issues/218)

**Merged pull requests:**

- Raise import errors on endpoint handling [\#245](https://github.com/zalando/connexion/pull/245) ([jmcs](https://github.com/jmcs))
- Add a Gitter chat badge to README.rst [\#244](https://github.com/zalando/connexion/pull/244) ([gitter-badger](https://github.com/gitter-badger))
- Add link to official spec [\#243](https://github.com/zalando/connexion/pull/243) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Corrected the Content-Type header for /basePath/swagger.json to retur… [\#242](https://github.com/zalando/connexion/pull/242) ([jkozlowicz](https://github.com/jkozlowicz))
- fix flake8 formatting of SQLAlchemy example [\#241](https://github.com/zalando/connexion/pull/241) ([hjacobs](https://github.com/hjacobs))
- SQLAlchemy based example [\#238](https://github.com/zalando/connexion/pull/238) ([nmusatti](https://github.com/nmusatti))

## [1.0.98](https://github.com/zalando/connexion/tree/1.0.98) (2016-06-03)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.97...1.0.98)

**Implemented enhancements:**

- Add flag for validation disabling [\#182](https://github.com/zalando/connexion/issues/182)

**Closed issues:**

- Problems with new version of Flask 0.11 [\#239](https://github.com/zalando/connexion/issues/239)
- AWS API Gateway, Lambda & DynamoDB [\#230](https://github.com/zalando/connexion/issues/230)
- How to define nullable response attributes? [\#226](https://github.com/zalando/connexion/issues/226)

**Merged pull requests:**

- Support flask 0.11 [\#240](https://github.com/zalando/connexion/pull/240) ([rafaelcaricio](https://github.com/rafaelcaricio))

## [1.0.97](https://github.com/zalando/connexion/tree/1.0.97) (2016-05-17)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.95...1.0.97)

**Closed issues:**

- Skipped Parameter Validation [\#219](https://github.com/zalando/connexion/issues/219)

**Merged pull requests:**

- Fix for when parameter spec is unordered. [\#228](https://github.com/zalando/connexion/pull/228) ([arjunrn](https://github.com/arjunrn))

## [1.0.95](https://github.com/zalando/connexion/tree/1.0.95) (2016-05-17)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.94...1.0.95)

**Merged pull requests:**

- Fix array conversion during validation [\#227](https://github.com/zalando/connexion/pull/227) ([gredin](https://github.com/gredin))

## [1.0.94](https://github.com/zalando/connexion/tree/1.0.94) (2016-05-11)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.91...1.0.94)

**Closed issues:**

- Swagger 2.0 yaml and git head and pip install connextion fail [\#220](https://github.com/zalando/connexion/issues/220)
- AttributeError: 'App' object has no attribute 'handle\_exception'  [\#217](https://github.com/zalando/connexion/issues/217)

**Merged pull requests:**

- Cleanup decorators [\#224](https://github.com/zalando/connexion/pull/224) ([jmcs](https://github.com/jmcs))
- Defer user error handing for swagger spec validator [\#222](https://github.com/zalando/connexion/pull/222) ([rafaelcaricio](https://github.com/rafaelcaricio))
- How to create custom format for JSON types [\#216](https://github.com/zalando/connexion/pull/216) ([rafaelcaricio](https://github.com/rafaelcaricio))

## [1.0.91](https://github.com/zalando/connexion/tree/1.0.91) (2016-04-22)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.89...1.0.91)

**Closed issues:**

- swagger\_spec\_validator adds in x-scope property to definitions [\#214](https://github.com/zalando/connexion/issues/214)

**Merged pull requests:**

- Copy spec before validation occurs [\#215](https://github.com/zalando/connexion/pull/215) ([wasbazi](https://github.com/wasbazi))
- Add \_\_call\_\_ method for WSGI-compliance [\#212](https://github.com/zalando/connexion/pull/212) ([tdpsk](https://github.com/tdpsk))

## [1.0.89](https://github.com/zalando/connexion/tree/1.0.89) (2016-04-08)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.88...1.0.89)

**Merged pull requests:**

- Reorganize imports [\#207](https://github.com/zalando/connexion/pull/207) ([rafaelcaricio](https://github.com/rafaelcaricio))

## [1.0.88](https://github.com/zalando/connexion/tree/1.0.88) (2016-04-07)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.84...1.0.88)

**Closed issues:**

- File download doesn't work [\#203](https://github.com/zalando/connexion/issues/203)
- specify minimum requirements [\#195](https://github.com/zalando/connexion/issues/195)

**Merged pull requests:**

- Add minimum versions of dependencies [\#209](https://github.com/zalando/connexion/pull/209) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Update templates [\#208](https://github.com/zalando/connexion/pull/208) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Validate accordingly with content-type defined in spec [\#205](https://github.com/zalando/connexion/pull/205) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Make JSON printing a bit nicer [\#193](https://github.com/zalando/connexion/pull/193) ([gdb](https://github.com/gdb))

## [1.0.84](https://github.com/zalando/connexion/tree/1.0.84) (2016-03-31)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.81...1.0.84)

**Implemented enhancements:**

- Not possible to return Decimals from the controller [\#196](https://github.com/zalando/connexion/issues/196)

**Closed issues:**

- version-mismatch: v1.0.33 in master, while v1.0.76 was already released [\#194](https://github.com/zalando/connexion/issues/194)
- File upload doesn't work [\#191](https://github.com/zalando/connexion/issues/191)

**Merged pull requests:**

- Real version is generated during release process [\#201](https://github.com/zalando/connexion/pull/201) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Json encoder customization [\#199](https://github.com/zalando/connexion/pull/199) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Support nullable parameters [\#197](https://github.com/zalando/connexion/pull/197) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Allow files to be passed into handler [\#192](https://github.com/zalando/connexion/pull/192) ([chriscoomber](https://github.com/chriscoomber))

## [1.0.81](https://github.com/zalando/connexion/tree/1.0.81) (2016-03-29)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.76...1.0.81)

**Implemented enhancements:**

- Log details of response validation errors? [\#153](https://github.com/zalando/connexion/issues/153)

**Closed issues:**

- Python3 syntax used in exception [\#190](https://github.com/zalando/connexion/issues/190)
- Is a standalone Framework in top of Flask o can be implemented as a Flask Blueprint? [\#188](https://github.com/zalando/connexion/issues/188)
- Global response definitions not supported [\#180](https://github.com/zalando/connexion/issues/180)
- Proposed Tagline change [\#158](https://github.com/zalando/connexion/issues/158)
- Remove usage of HTTP\_TOKENINFO\_URL environment variable [\#148](https://github.com/zalando/connexion/issues/148)
- Document, how headers are passed to the methods [\#76](https://github.com/zalando/connexion/issues/76)

**Merged pull requests:**

- Feature/option to disable swagger json [\#198](https://github.com/zalando/connexion/pull/198) ([dfeinzeig](https://github.com/dfeinzeig))
- Response definitions can be defined globally in spec [\#187](https://github.com/zalando/connexion/pull/187) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Better error handling for non-conforming responses [\#186](https://github.com/zalando/connexion/pull/186) ([dfeinzeig](https://github.com/dfeinzeig))
- Added documentation about header parameters. [\#184](https://github.com/zalando/connexion/pull/184) ([arjunrn](https://github.com/arjunrn))
- Update README.rst [\#176](https://github.com/zalando/connexion/pull/176) ([LappleApple](https://github.com/LappleApple))

## [1.0.76](https://github.com/zalando/connexion/tree/1.0.76) (2016-03-09)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.67...1.0.76)

**Implemented enhancements:**

- Typecasting? [\#104](https://github.com/zalando/connexion/issues/104)

**Fixed bugs:**

- README: "Installing It" section will not work [\#164](https://github.com/zalando/connexion/issues/164)

**Closed issues:**

- Include a link to the RTD in the README. [\#167](https://github.com/zalando/connexion/issues/167)
- Document response handling [\#78](https://github.com/zalando/connexion/issues/78)
- Document how arguments are passed to the functions [\#75](https://github.com/zalando/connexion/issues/75)
- HTTPS support [\#73](https://github.com/zalando/connexion/issues/73)
- Document how to allow long running request not block everything else [\#62](https://github.com/zalando/connexion/issues/62)
- Support all JSON schema validation and parsing attributes [\#39](https://github.com/zalando/connexion/issues/39)

**Merged pull requests:**

- Remove unecessary argument [\#178](https://github.com/zalando/connexion/pull/178) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Remove assignment to prevent unexpected keyword argument 'port' error [\#177](https://github.com/zalando/connexion/pull/177) ([JoshStutts](https://github.com/JoshStutts))
- Fix some issues reported by quantifiedcode [\#174](https://github.com/zalando/connexion/pull/174) ([jmcs](https://github.com/jmcs))
- Type cast in path parameters [\#172](https://github.com/zalando/connexion/pull/172) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Add parameter handing docs to README [\#170](https://github.com/zalando/connexion/pull/170) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Improve docs [\#169](https://github.com/zalando/connexion/pull/169) ([jmcs](https://github.com/jmcs))
- Update README.rst [\#168](https://github.com/zalando/connexion/pull/168) ([LappleApple](https://github.com/LappleApple))
- Remove usage of HTTP\_TOKENINFO\_URL environment variable [\#166](https://github.com/zalando/connexion/pull/166) ([jmcs](https://github.com/jmcs))
- \#164 Fix installation instructions [\#165](https://github.com/zalando/connexion/pull/165) ([jmcs](https://github.com/jmcs))
- Only support valid OpenAPI/Swagger 2.0 specifications [\#160](https://github.com/zalando/connexion/pull/160) ([rafaelcaricio](https://github.com/rafaelcaricio))

## [1.0.67](https://github.com/zalando/connexion/tree/1.0.67) (2016-03-02)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.61...1.0.67)

**Implemented enhancements:**

- Silencing ImportErrors raised in modules referenced by operationId [\#155](https://github.com/zalando/connexion/issues/155)
- Consider bravado-core to manage OpenAPI/Swagger 2.0 validation/parser [\#151](https://github.com/zalando/connexion/issues/151)
- Query and Path Parameter Validation [\#48](https://github.com/zalando/connexion/issues/48)

**Closed issues:**

- Not passing get params to controller function [\#135](https://github.com/zalando/connexion/issues/135)
- Optional and uppercase parameters [\#99](https://github.com/zalando/connexion/issues/99)

**Merged pull requests:**

- Add pull request template [\#161](https://github.com/zalando/connexion/pull/161) ([rafaelcaricio](https://github.com/rafaelcaricio))
- App breaks if error adding operation raise exception [\#159](https://github.com/zalando/connexion/pull/159) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Update README.rst [\#157](https://github.com/zalando/connexion/pull/157) ([LappleApple](https://github.com/LappleApple))
- Update LICENSE.txt [\#154](https://github.com/zalando/connexion/pull/154) ([LappleApple](https://github.com/LappleApple))

## [1.0.61](https://github.com/zalando/connexion/tree/1.0.61) (2016-02-17)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.58...1.0.61)

**Implemented enhancements:**

- Add /.well-known/schema-discovery route for queries from TWINTIP [\#82](https://github.com/zalando/connexion/issues/82)

**Closed issues:**

- get\_function\_arguments\(\) behavior changes between python 2.7 and python 3.5 [\#142](https://github.com/zalando/connexion/issues/142)
- Problems with array and boolean inputs from query parameters [\#71](https://github.com/zalando/connexion/issues/71)
- Provide examples of correctly configuring OAuth support [\#61](https://github.com/zalando/connexion/issues/61)

**Merged pull requests:**

- Support parameters definitions in path level [\#152](https://github.com/zalando/connexion/pull/152) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Add Rafael Caricio to the list of maintainers [\#150](https://github.com/zalando/connexion/pull/150) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Recommend usage of `decorator` package in Connexion projects [\#149](https://github.com/zalando/connexion/pull/149) ([rafaelcaricio](https://github.com/rafaelcaricio))

## [1.0.58](https://github.com/zalando/connexion/tree/1.0.58) (2016-02-13)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.57...1.0.58)

**Implemented enhancements:**

- Use "TOKENINFO\_URL" environment variable as fallback [\#146](https://github.com/zalando/connexion/issues/146)

**Merged pull requests:**

- \#146 allow using TOKENINFO\_URL env var \(OAuth2 token info\) [\#147](https://github.com/zalando/connexion/pull/147) ([hjacobs](https://github.com/hjacobs))

## [1.0.57](https://github.com/zalando/connexion/tree/1.0.57) (2016-02-11)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.54...1.0.57)

**Implemented enhancements:**

- Auth 404 errors option [\#143](https://github.com/zalando/connexion/pull/143) ([rafaelcaricio](https://github.com/rafaelcaricio))

**Fixed bugs:**

- All Boolean values passed in via query strings evaluate to True [\#139](https://github.com/zalando/connexion/issues/139)

**Closed issues:**

- Status code 204 should be allowed to return headers metadata [\#144](https://github.com/zalando/connexion/issues/144)
- Issue with endpoints with body and path params [\#141](https://github.com/zalando/connexion/issues/141)
- Basic working example for RestyResolver? [\#120](https://github.com/zalando/connexion/issues/120)

**Merged pull requests:**

- Support header params on 204 response code [\#145](https://github.com/zalando/connexion/pull/145) ([rafaelcaricio](https://github.com/rafaelcaricio))

## [1.0.54](https://github.com/zalando/connexion/tree/1.0.54) (2016-02-08)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.53...1.0.54)

**Merged pull requests:**

- Use the JSON/Swagger aware boolean constructor for constructing boole… [\#140](https://github.com/zalando/connexion/pull/140) ([scolby33](https://github.com/scolby33))

## [1.0.53](https://github.com/zalando/connexion/tree/1.0.53) (2016-02-05)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.52...1.0.53)

**Merged pull requests:**

- Added support for circular references and additionalProperties [\#126](https://github.com/zalando/connexion/pull/126) ([jbryan](https://github.com/jbryan))

## [1.0.52](https://github.com/zalando/connexion/tree/1.0.52) (2016-02-03)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.50...1.0.52)

**Implemented enhancements:**

- Pass formData parameters as keyword arguments to handler function [\#132](https://github.com/zalando/connexion/issues/132)

**Fixed bugs:**

- Missing query parameters returns HTTP 500 instead of 400 [\#131](https://github.com/zalando/connexion/issues/131)

**Closed issues:**

- What is the way to declare an endpoint that returns a flask.Response object? [\#133](https://github.com/zalando/connexion/issues/133)

**Merged pull requests:**

- Fix when API returns flask response [\#137](https://github.com/zalando/connexion/pull/137) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Fixes problem with param validation [\#136](https://github.com/zalando/connexion/pull/136) ([rafaelcaricio](https://github.com/rafaelcaricio))

## [1.0.50](https://github.com/zalando/connexion/tree/1.0.50) (2016-02-03)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.49...1.0.50)

**Closed issues:**

- Issue with Boolean types in code generated by swagger-codegen [\#127](https://github.com/zalando/connexion/issues/127)

**Merged pull requests:**

- Pass formData parameters as keyword arguments [\#134](https://github.com/zalando/connexion/pull/134) ([jvgutierrez](https://github.com/jvgutierrez))

## [1.0.49](https://github.com/zalando/connexion/tree/1.0.49) (2016-02-02)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.38...1.0.49)

**Implemented enhancements:**

- Option to disable validatorUrl [\#110](https://github.com/zalando/connexion/issues/110)
- Cross-origin resource sharing support [\#50](https://github.com/zalando/connexion/issues/50)

**Closed issues:**

- Documentation - relative routing with router controller [\#128](https://github.com/zalando/connexion/issues/128)
- Add basic example with HTTP Basic Auth [\#123](https://github.com/zalando/connexion/issues/123)

**Merged pull requests:**

- Handle correctly boolean values in default property [\#130](https://github.com/zalando/connexion/pull/130) ([rafaelcaricio](https://github.com/rafaelcaricio))
- Fix \#128 - document `x-swagger-router-controller` [\#129](https://github.com/zalando/connexion/pull/129) ([milo-minderbinder](https://github.com/milo-minderbinder))
- RestyResolver Example [\#125](https://github.com/zalando/connexion/pull/125) ([kleijnweb](https://github.com/kleijnweb))

## [1.0.38](https://github.com/zalando/connexion/tree/1.0.38) (2016-01-21)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.37...1.0.38)

**Implemented enhancements:**

- Explore using jsonschema to validate requests [\#108](https://github.com/zalando/connexion/issues/108)

## [1.0.37](https://github.com/zalando/connexion/tree/1.0.37) (2016-01-13)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.33...1.0.37)

**Merged pull requests:**

- fix bug in restyresolver which was causing collision between .search and .get methods [\#121](https://github.com/zalando/connexion/pull/121) ([dfeinzeig](https://github.com/dfeinzeig))

## [1.0.33](https://github.com/zalando/connexion/tree/1.0.33) (2016-01-12)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.31...1.0.33)

**Merged pull requests:**

- Handle array of definition and definition properties in a definition [\#118](https://github.com/zalando/connexion/pull/118) ([cyprien-g](https://github.com/cyprien-g))

## [1.0.31](https://github.com/zalando/connexion/tree/1.0.31) (2016-01-12)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.29...1.0.31)

**Merged pull requests:**

- Support for default fields in operation parameters [\#117](https://github.com/zalando/connexion/pull/117) ([arjunrn](https://github.com/arjunrn))

## [1.0.29](https://github.com/zalando/connexion/tree/1.0.29) (2016-01-05)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.28...1.0.29)

**Merged pull requests:**

- Allow True/False for query parameters [\#116](https://github.com/zalando/connexion/pull/116) ([cyprien-g](https://github.com/cyprien-g))

## [1.0.28](https://github.com/zalando/connexion/tree/1.0.28) (2015-12-21)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.26...1.0.28)

**Implemented enhancements:**

- Allow for optional operationId [\#98](https://github.com/zalando/connexion/issues/98)

**Closed issues:**

- Concurrency Control Using E-Tags [\#111](https://github.com/zalando/connexion/issues/111)

**Merged pull requests:**

- Use jsonschema [\#114](https://github.com/zalando/connexion/pull/114) ([jmcs](https://github.com/jmcs))

## [1.0.26](https://github.com/zalando/connexion/tree/1.0.26) (2015-12-08)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.25...1.0.26)

**Implemented enhancements:**

- Endpoint not found in main module [\#101](https://github.com/zalando/connexion/issues/101)

**Merged pull requests:**

- Updated endpoint routing docs [\#113](https://github.com/zalando/connexion/pull/113) ([kleijnweb](https://github.com/kleijnweb))
- Handle dashes in resource names in RestyResolver [\#112](https://github.com/zalando/connexion/pull/112) ([kleijnweb](https://github.com/kleijnweb))

## [1.0.25](https://github.com/zalando/connexion/tree/1.0.25) (2015-12-08)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.22...1.0.25)

**Implemented enhancements:**

- Fix GitHub language detection [\#106](https://github.com/zalando/connexion/issues/106)

**Merged pull requests:**

- Sensible defaults for controller resolution [\#107](https://github.com/zalando/connexion/pull/107) ([kleijnweb](https://github.com/kleijnweb))
- Add type casting \(and type-based routing\) for int/float path params [\#105](https://github.com/zalando/connexion/pull/105) ([hjacobs](https://github.com/hjacobs))

## [1.0.22](https://github.com/zalando/connexion/tree/1.0.22) (2015-12-05)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.20...1.0.22)

**Fixed bugs:**

- Won't build in official python Docker image [\#103](https://github.com/zalando/connexion/issues/103)

## [1.0.20](https://github.com/zalando/connexion/tree/1.0.20) (2015-12-05)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.19...1.0.20)

## [1.0.19](https://github.com/zalando/connexion/tree/1.0.19) (2015-12-04)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.9...1.0.19)

**Implemented enhancements:**

- Expose Request Metrics as JSON endpoint [\#49](https://github.com/zalando/connexion/issues/49)

**Fixed bugs:**

- Prioritisation of similar paths [\#92](https://github.com/zalando/connexion/issues/92)

**Closed issues:**

- change use of `operationId` [\#94](https://github.com/zalando/connexion/issues/94)

**Merged pull requests:**

- Add support for extension members in Problem Detail packets [\#102](https://github.com/zalando/connexion/pull/102) ([jvinet](https://github.com/jvinet))
- updated swagger-ui [\#100](https://github.com/zalando/connexion/pull/100) ([kashif](https://github.com/kashif))

## [1.0.9](https://github.com/zalando/connexion/tree/1.0.9) (2015-11-18)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.8...1.0.9)

**Fixed bugs:**

- unorderable types with `default` response [\#96](https://github.com/zalando/connexion/issues/96)

**Merged pull requests:**

- added logic for detecting x-swagger-router-controller [\#95](https://github.com/zalando/connexion/pull/95) ([fehguy](https://github.com/fehguy))

## [1.0.8](https://github.com/zalando/connexion/tree/1.0.8) (2015-11-18)
[Full Changelog](https://github.com/zalando/connexion/compare/1.0.5...1.0.8)

**Implemented enhancements:**

- Add support for multiple implementations in operationId [\#89](https://github.com/zalando/connexion/issues/89)

**Merged pull requests:**

- Fix swagger.json url with  response [\#97](https://github.com/zalando/connexion/pull/97) ([jmcs](https://github.com/jmcs))
- Allow custom function resolver [\#93](https://github.com/zalando/connexion/pull/93) ([jmcs](https://github.com/jmcs))

## [1.0.5](https://github.com/zalando/connexion/tree/1.0.5) (2015-11-12)
[Full Changelog](https://github.com/zalando/connexion/compare/0.13...1.0.5)

**Merged pull requests:**

- Fixed an issue with query parameters not properly handling arrays [\#90](https://github.com/zalando/connexion/pull/90) ([danballance](https://github.com/danballance))

## [0.13](https://github.com/zalando/connexion/tree/0.13) (2015-11-06)
[Full Changelog](https://github.com/zalando/connexion/compare/0.12.1...0.13)

**Implemented enhancements:**

- Allow adding headers to problem responses [\#85](https://github.com/zalando/connexion/issues/85)

**Closed issues:**

- Reconsider logging client errors \(HTTP status 4xx\) with "ERROR" log level [\#83](https://github.com/zalando/connexion/issues/83)
- How to add headers to the Response object? [\#74](https://github.com/zalando/connexion/issues/74)

**Merged pull requests:**

- Use headers.extend instead of adding headers one by one [\#88](https://github.com/zalando/connexion/pull/88) ([jmcs](https://github.com/jmcs))
- \#83 change log severity levels in the decorators [\#87](https://github.com/zalando/connexion/pull/87) ([jmcs](https://github.com/jmcs))
- \#85 Allow adding headers to problem responses [\#86](https://github.com/zalando/connexion/pull/86) ([jmcs](https://github.com/jmcs))
- Validating the developer's returned response against the specification [\#84](https://github.com/zalando/connexion/pull/84) ([danballance](https://github.com/danballance))

## [0.12.1](https://github.com/zalando/connexion/tree/0.12.1) (2015-10-29)
[Full Changelog](https://github.com/zalando/connexion/compare/0.12.0...0.12.1)

**Implemented enhancements:**

- Return api from App.add\_api ? [\#79](https://github.com/zalando/connexion/issues/79)

**Merged pull requests:**

- Return api from App.add\_api [\#81](https://github.com/zalando/connexion/pull/81) ([jmcs](https://github.com/jmcs))
- Add some basic unit tests to improve test coverage. [\#80](https://github.com/zalando/connexion/pull/80) ([elezar](https://github.com/elezar))
- Proposed technique for returning custom headers \(with simple unit test\) [\#77](https://github.com/zalando/connexion/pull/77) ([danballance](https://github.com/danballance))

## [0.12.0](https://github.com/zalando/connexion/tree/0.12.0) (2015-10-13)
[Full Changelog](https://github.com/zalando/connexion/compare/0.11.3...0.12.0)

**Implemented enhancements:**

- Token\_info in request object [\#69](https://github.com/zalando/connexion/issues/69)

**Merged pull requests:**

- Options Parameter for Werkzeug [\#72](https://github.com/zalando/connexion/pull/72) ([cansik](https://github.com/cansik))

## [0.11.3](https://github.com/zalando/connexion/tree/0.11.3) (2015-10-07)
[Full Changelog](https://github.com/zalando/connexion/compare/0.11.2...0.11.3)

**Implemented enhancements:**

- Use PEP 484 Type Annotations [\#2](https://github.com/zalando/connexion/issues/2)

## [0.11.2](https://github.com/zalando/connexion/tree/0.11.2) (2015-10-02)
[Full Changelog](https://github.com/zalando/connexion/compare/0.11.1...0.11.2)

**Implemented enhancements:**

- Expose WSGI interface [\#54](https://github.com/zalando/connexion/issues/54)

**Merged pull requests:**

- Include oauth authentication information on request [\#70](https://github.com/zalando/connexion/pull/70) ([jmcs](https://github.com/jmcs))

## [0.11.1](https://github.com/zalando/connexion/tree/0.11.1) (2015-09-28)
[Full Changelog](https://github.com/zalando/connexion/compare/0.10.2...0.11.1)

**Implemented enhancements:**

- Pass query and body parameters as keyword arguments to handler function [\#59](https://github.com/zalando/connexion/issues/59)

**Fixed bugs:**

- List as body parameter fails in validation [\#66](https://github.com/zalando/connexion/issues/66)

**Closed issues:**

- Python3 swagger.json generation error [\#63](https://github.com/zalando/connexion/issues/63)

**Merged pull requests:**

- Handle non object body parameters [\#68](https://github.com/zalando/connexion/pull/68) ([jmcs](https://github.com/jmcs))
- Serialization: Don't append 'Z' to datetime objects if they already have a timezone [\#67](https://github.com/zalando/connexion/pull/67) ([jvinet](https://github.com/jvinet))
- Pass query and body parameters as keyword arguments to handler function [\#65](https://github.com/zalando/connexion/pull/65) ([jmcs](https://github.com/jmcs))

## [0.10.2](https://github.com/zalando/connexion/tree/0.10.2) (2015-09-21)
[Full Changelog](https://github.com/zalando/connexion/compare/0.10.1...0.10.2)

## [0.10.1](https://github.com/zalando/connexion/tree/0.10.1) (2015-09-18)
[Full Changelog](https://github.com/zalando/connexion/compare/0.10...0.10.1)

## [0.10](https://github.com/zalando/connexion/tree/0.10) (2015-09-18)
[Full Changelog](https://github.com/zalando/connexion/compare/0.9.4...0.10)

**Merged pull requests:**

- Add UWSGI metrics collector [\#64](https://github.com/zalando/connexion/pull/64) ([hjacobs](https://github.com/hjacobs))

## [0.9.4](https://github.com/zalando/connexion/tree/0.9.4) (2015-09-04)
[Full Changelog](https://github.com/zalando/connexion/compare/0.9.3...0.9.4)

**Merged pull requests:**

- Add validation for array types in query or path [\#60](https://github.com/zalando/connexion/pull/60) ([jvinet](https://github.com/jvinet))

## [0.9.3](https://github.com/zalando/connexion/tree/0.9.3) (2015-09-02)
[Full Changelog](https://github.com/zalando/connexion/compare/0.9.2...0.9.3)

**Implemented enhancements:**

- Allow configurable path and URL for swagger-ui [\#58](https://github.com/zalando/connexion/pull/58) ([jvinet](https://github.com/jvinet))

## [0.9.2](https://github.com/zalando/connexion/tree/0.9.2) (2015-08-27)
[Full Changelog](https://github.com/zalando/connexion/compare/0.9.1...0.9.2)

**Merged pull requests:**

- Feature/parameter validation issue 48 [\#57](https://github.com/zalando/connexion/pull/57) ([hjacobs](https://github.com/hjacobs))

## [0.9.1](https://github.com/zalando/connexion/tree/0.9.1) (2015-08-27)
[Full Changelog](https://github.com/zalando/connexion/compare/0.9.0...0.9.1)

**Implemented enhancements:**

- Tornado dependency should be optional [\#47](https://github.com/zalando/connexion/issues/47)

**Fixed bugs:**

- Not including a 'produces' in a swagger definition results in an error [\#53](https://github.com/zalando/connexion/issues/53)

**Merged pull requests:**

- Feature/parameter validation issue 48 [\#56](https://github.com/zalando/connexion/pull/56) ([hjacobs](https://github.com/hjacobs))

## [0.9.0](https://github.com/zalando/connexion/tree/0.9.0) (2015-08-26)
[Full Changelog](https://github.com/zalando/connexion/compare/0.8.6...0.9.0)

**Merged pull requests:**

- Serialize as json by default and removed tornado dependency [\#55](https://github.com/zalando/connexion/pull/55) ([jmcs](https://github.com/jmcs))

## [0.8.6](https://github.com/zalando/connexion/tree/0.8.6) (2015-08-18)
[Full Changelog](https://github.com/zalando/connexion/compare/0.8.5...0.8.6)

**Fixed bugs:**

- JSON References for Parameters Not Supported [\#46](https://github.com/zalando/connexion/issues/46)

**Closed issues:**

- JSONEncoder datetime.date encoding fails [\#51](https://github.com/zalando/connexion/issues/51)

**Merged pull requests:**

- added date support for JSONEncoder [\#52](https://github.com/zalando/connexion/pull/52) ([cansik](https://github.com/cansik))

## [0.8.5](https://github.com/zalando/connexion/tree/0.8.5) (2015-08-13)
[Full Changelog](https://github.com/zalando/connexion/compare/0.8.4...0.8.5)

## [0.8.4](https://github.com/zalando/connexion/tree/0.8.4) (2015-08-11)
[Full Changelog](https://github.com/zalando/connexion/compare/0.8.3...0.8.4)

## [0.8.3](https://github.com/zalando/connexion/tree/0.8.3) (2015-08-05)
[Full Changelog](https://github.com/zalando/connexion/compare/0.8.2...0.8.3)

## [0.8.2](https://github.com/zalando/connexion/tree/0.8.2) (2015-08-05)
[Full Changelog](https://github.com/zalando/connexion/compare/0.8.1...0.8.2)

**Merged pull requests:**

- Fix bug: forward the listen port in case of server being gevent [\#45](https://github.com/zalando/connexion/pull/45) ([jkliff](https://github.com/jkliff))

## [0.8.1](https://github.com/zalando/connexion/tree/0.8.1) (2015-07-31)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.8.0...0.8.1)

## [v0.8.0](https://github.com/zalando/connexion/tree/v0.8.0) (2015-07-31)
[Full Changelog](https://github.com/zalando/connexion/compare/0.7.6...v0.8.0)

**Implemented enhancements:**

- Support gevent WSGI server [\#40](https://github.com/zalando/connexion/issues/40)
- Make it Python 2 compatible [\#33](https://github.com/zalando/connexion/issues/33)
- Allow adding single routes [\#20](https://github.com/zalando/connexion/issues/20)

**Merged pull requests:**

- Release/v0.8 [\#44](https://github.com/zalando/connexion/pull/44) ([jmcs](https://github.com/jmcs))
- Support python 2.7 and pypy \(\#33\) [\#42](https://github.com/zalando/connexion/pull/42) ([jmcs](https://github.com/jmcs))
- Allow adding single routes [\#41](https://github.com/zalando/connexion/pull/41) ([jmcs](https://github.com/jmcs))

## [0.7.6](https://github.com/zalando/connexion/tree/0.7.6) (2015-07-28)
[Full Changelog](https://github.com/zalando/connexion/compare/0.7.5...0.7.6)

## [0.7.5](https://github.com/zalando/connexion/tree/0.7.5) (2015-07-23)
[Full Changelog](https://github.com/zalando/connexion/compare/0.7.4...0.7.5)

## [0.7.4](https://github.com/zalando/connexion/tree/0.7.4) (2015-07-23)
[Full Changelog](https://github.com/zalando/connexion/compare/0.7.3...0.7.4)

## [0.7.3](https://github.com/zalando/connexion/tree/0.7.3) (2015-07-23)
[Full Changelog](https://github.com/zalando/connexion/compare/0.7.2...0.7.3)

## [0.7.2](https://github.com/zalando/connexion/tree/0.7.2) (2015-07-20)
[Full Changelog](https://github.com/zalando/connexion/compare/0.7.1...0.7.2)

**Fixed bugs:**

- Paths with "-" do not work [\#36](https://github.com/zalando/connexion/issues/36)

**Merged pull requests:**

- Better error messages [\#38](https://github.com/zalando/connexion/pull/38) ([hjacobs](https://github.com/hjacobs))

## [0.7.1](https://github.com/zalando/connexion/tree/0.7.1) (2015-07-17)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.7.0...0.7.1)

**Implemented enhancements:**

- Return more detailed errors when validation fails [\#32](https://github.com/zalando/connexion/issues/32)
- Add validation for Swagger schema definitions [\#4](https://github.com/zalando/connexion/issues/4)

**Merged pull requests:**

- Fix paths with hyphen issue 36 [\#37](https://github.com/zalando/connexion/pull/37) ([hjacobs](https://github.com/hjacobs))
- Add codeclimate configuration [\#35](https://github.com/zalando/connexion/pull/35) ([jmcs](https://github.com/jmcs))
- Improve error messages [\#34](https://github.com/zalando/connexion/pull/34) ([jmcs](https://github.com/jmcs))

## [v0.7.0](https://github.com/zalando/connexion/tree/v0.7.0) (2015-07-08)
[Full Changelog](https://github.com/zalando/connexion/compare/0.6.1...v0.7.0)

**Merged pull requests:**

- allow running without OAuth2 token info URL \(for local development\) [\#31](https://github.com/zalando/connexion/pull/31) ([hjacobs](https://github.com/hjacobs))
- Add release.sh helper script to build and release to PyPI [\#30](https://github.com/zalando/connexion/pull/30) ([hjacobs](https://github.com/hjacobs))

## [0.6.1](https://github.com/zalando/connexion/tree/0.6.1) (2015-07-07)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.6.0...0.6.1)

**Closed issues:**

- Swagger paths without operationId property should not crash connexion [\#27](https://github.com/zalando/connexion/issues/27)

**Merged pull requests:**

- Schema Validation [\#29](https://github.com/zalando/connexion/pull/29) ([jmcs](https://github.com/jmcs))
- wrap add\_operation with try/except to continue even if operationId or… [\#28](https://github.com/zalando/connexion/pull/28) ([hjacobs](https://github.com/hjacobs))

## [v0.6.0](https://github.com/zalando/connexion/tree/v0.6.0) (2015-06-29)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.5.1...v0.6.0)

**Implemented enhancements:**

- Don't jsonify responses with status 204 [\#24](https://github.com/zalando/connexion/issues/24)
- Include extra information in logs [\#19](https://github.com/zalando/connexion/issues/19)
- Make swagger ui optional [\#18](https://github.com/zalando/connexion/issues/18)

**Merged pull requests:**

- Better handling for 204 responses [\#26](https://github.com/zalando/connexion/pull/26) ([jmcs](https://github.com/jmcs))
- Add extra logging information [\#25](https://github.com/zalando/connexion/pull/25) ([jmcs](https://github.com/jmcs))
- \#18 Make Swagger UI optional [\#23](https://github.com/zalando/connexion/pull/23) ([jmcs](https://github.com/jmcs))

## [v0.5.1](https://github.com/zalando/connexion/tree/v0.5.1) (2015-06-22)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.5...v0.5.1)

**Fixed bugs:**

- Don't change the specification when parsing it [\#21](https://github.com/zalando/connexion/issues/21)

**Merged pull requests:**

- https://github.com/zalando/connexion/issues/21 Don't pop stuff that's… [\#22](https://github.com/zalando/connexion/pull/22) ([jmcs](https://github.com/jmcs))

## [v0.5](https://github.com/zalando/connexion/tree/v0.5) (2015-06-18)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.4.2...v0.5)

**Implemented enhancements:**

- Use application/problem+json for error messages [\#11](https://github.com/zalando/connexion/issues/11)
- Jsonify responses with application specific content types [\#10](https://github.com/zalando/connexion/issues/10)
- Decorator to set the correct content-type [\#9](https://github.com/zalando/connexion/issues/9)
- Custom jsonfier [\#8](https://github.com/zalando/connexion/issues/8)
-  \#10  Jsonify responses with application specific content types [\#17](https://github.com/zalando/connexion/pull/17) ([jmcs](https://github.com/jmcs))

**Fixed bugs:**

- Use certifi bundle in security decorator [\#12](https://github.com/zalando/connexion/issues/12)

**Merged pull requests:**

- \#11 Implemented application/problem+json errors [\#16](https://github.com/zalando/connexion/pull/16) ([jmcs](https://github.com/jmcs))
- \#9 default produces decorator [\#15](https://github.com/zalando/connexion/pull/15) ([jmcs](https://github.com/jmcs))
- \#8 custom jsonfier [\#14](https://github.com/zalando/connexion/pull/14) ([jmcs](https://github.com/jmcs))

## [v0.4.2](https://github.com/zalando/connexion/tree/v0.4.2) (2015-06-17)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.4.1...v0.4.2)

**Closed issues:**

- Add Travis CI test running py.test and flake8 [\#6](https://github.com/zalando/connexion/issues/6)

**Merged pull requests:**

- Issues12 cert [\#13](https://github.com/zalando/connexion/pull/13) ([jmcs](https://github.com/jmcs))
- Add unit tests and CI [\#7](https://github.com/zalando/connexion/pull/7) ([jmcs](https://github.com/jmcs))

## [v0.4.1](https://github.com/zalando/connexion/tree/v0.4.1) (2015-06-12)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.4...v0.4.1)

**Fixed bugs:**

- Fix security parsing [\#5](https://github.com/zalando/connexion/issues/5)
- Convert dashes in the path to underscore [\#3](https://github.com/zalando/connexion/issues/3)

## [v0.4](https://github.com/zalando/connexion/tree/v0.4) (2015-06-12)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.3.1...v0.4)

## [v0.3.1](https://github.com/zalando/connexion/tree/v0.3.1) (2015-06-08)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.3...v0.3.1)

**Implemented enhancements:**

- Support configurable arguments on yaml specifications [\#1](https://github.com/zalando/connexion/issues/1)

## [v0.3](https://github.com/zalando/connexion/tree/v0.3) (2015-06-07)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.2...v0.3)

## [v0.2](https://github.com/zalando/connexion/tree/v0.2) (2015-05-21)
[Full Changelog](https://github.com/zalando/connexion/compare/v0.1...v0.2)

## [v0.1](https://github.com/zalando/connexion/tree/v0.1) (2015-05-19)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*