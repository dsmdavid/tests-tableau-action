# Sample repo to test Github Actions for Tableau:
![format-validator](https://github.com/github/docs/actions/workflows/sample_workflow_format_validator.yml/badge.svg)

## Tableau Format Validator
![format-validator](https://github.com/dsmdavid/tests-tableau-action/actions/workflows/sample_workflow_format_validator.yml/badge.svg)  
This should be "Failing" in this example (update the threshold of errors in the workflow file, or fix them in the tableau workbook).
Uses [this action](https://github.com/marketplace/actions/validate-tableau-format).
- See the [configuration of the workflow](.github/workflows/sample_workflow_format_validator.yml)
- The example guide lives _style_guide/example.json_
- On a pull request, the modified .twb files will be sent for validation

