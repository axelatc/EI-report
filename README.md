# Install project
- Run `Bundle` at the roof this directory

# Convert to PDF
- Run `asciidoctor-pdf -v -r asciidoctor-diagram tfe.adoc` to convert the Asciidoctor file to a pdf file

# Errors
- If you get the error `asciidoctor: DEBUG: tfe.adoc: line 2405: unknown style for literal block: plantuml`:
  - make sure you loaded asciidoctor-diagram by using the CLI parameter `-r asciidoctor-diagram`
