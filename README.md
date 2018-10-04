# Docs-as-Code

Example project to demonstrate the use of Asciidoc to generate software documentation. Combining models from the following sources:

+ [Arc42](https://arc42.org/download)
+ [C4-model](https://c4model.com/)
+ Architecture Decision Records

Generation of diagrams is supported using PlantUML.

Please feel free to adjust the template and have fun generating you own documentation.

## Getting Started

### Prerequisites

+ Java installed
+ [Graphviz](https://graphviz.gitlab.io/) installed (needed to generate diagrams)

## Running

Execute the documentation generation by:
`./gradlew asciidoctor`

The generated documentation can be found at:

+ `/build/asciidoc/index.html` (HTML website)
+ `/build/asciidoc/index.pdf` (PDF document)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* The documentation template is inspired by the ARC42 model/C4-Model and Architecture Decision Records.
