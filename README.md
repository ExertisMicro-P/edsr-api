# edsr-api
###EDSR REST API definition

Definition source file is `edsr-api.raml`.
This definition is built using RAML 0.8. For more information on the RAML standard, please refer to http://raml.org.

The `.raml` file can be used by various RAML tools to produce human readable documentation and client skeletons in various programming languages.

As RAML 1.0 is still at RC status, there is patchy support for it, therefore we have opted to stick with version 0.8.

Details of body payloads are expressed using JSON Schemas within the `schemas` folder. Please refer to http://json-schema.org for details.

`edsr-api.html` has been produced from the .raml using the raml2html tool, see https://github.com/raml2html/raml2html


###Contributing
Contributions may be made via Pull Requests. Only the `.raml` and `.json` schemas should be modified.
