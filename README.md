
# Perspectives on Politics Quarto Format

## Creating a New Article

To create a new article using this format:

```bash
quarto use template christopherkenny/perspectives
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add christopherkenny/perspectives
```

Then, add the format to your document options:

```yaml
format:
  perspectives-pdf: default
```    

## Options

- `runningtitle`: A short title that goes on the header of each page
- `word-count`: A word count for the document

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

<!-- pdftools::pdf_convert('template.pdf',pages = 1) -->
![[template.qmd](template.qmd)](template_1.png) 

## License

This modifies the Perspectives on Politics (PPS) Template, available at <https://www.overleaf.com/latex/templates/perspectives-in-politics-pps/wyprtcqbrvpz>.
The original template is licensed under the [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) by Cambridge University Press and Overleaf.