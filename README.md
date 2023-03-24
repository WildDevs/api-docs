# Wild Devs OpenAPI 3 Definition

High Performance & High Security API by [Wild-Devs](https://wild-devs.net).

## Description

This API is open for everyone without providing any api-key, but includes member and subscriber endpoints. For those you need an api-key to query the desired endpoints.

## Getting Started

### Dependencies

Since our API is divided into several files to ensure maintainability and extensibility, we use a tool called "swagger-cli" to create a definition file from all the individual files.

* swagger-cli

### Installing
```
npm i swagger-cli
```

### Bundle files
```
swagger-cli bundle -o dist\openapi.yaml -r -t yaml openapi.yaml
```

## Authors

Contributors names and contact info

* [Ray](mailto:ray@wild-devs.net)

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [Swagger OpenAPI 3 Specification](https://swagger.io/docs/specification/about/)