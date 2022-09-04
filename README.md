# Install project
- Install ruby on your system
- Run `Bundle` at the root this directory to install the dependencies

# Convert to PDF
- Run `asciidoctor-pdf -v -r asciidoctor-diagram -o ./out/tfe.pdf tfe.adoc` to convert the Asciidoctor file to a pdf
  file located at `out/tfe.pdf`

# Errors
- If you get the error `asciidoctor: DEBUG: tfe.adoc: line 2405: unknown style for literal block: plantuml`:
  - make sure you loaded asciidoctor-diagram by using the CLI parameter `-r asciidoctor-diagram`
