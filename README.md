# play2prep content integration schema
API schema documentation for integrating your content with play2prep.  We're using the [RAML](http://raml.org/) specification for defining the [Content Hosting API](http://play2prep.github.io/content-integration-schema/content-hosting-api.html), and [JSON Schema](http://json-schema.org/) for both the [Content File schema](https://github.com/play2prep/content-integration-schema/blob/master/question-bundle-schema.json) and for messages exchanged in the Content Hosting API.

**Note: This version is a draft, and the full schema is coming soon to github.**


# all data is json
All data structures are described with [JSON Schema](http://json-schema.org/).  Try using [z-schema](https://www.npmjs.com/package/z-schema) to validate your data, and see [json-schema.org/implementations](http://json-schema.org/implementations.html) for more validators in more languages.