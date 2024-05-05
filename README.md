# github-actions-library

## Helm lint

inputs:
- template_path:
  description: 'path to template'
  required: true
- lint_args:
  description: 'Adds additional arguments to "helm lint" command'
  required: false

## Helm render

inputs: 
- template_path: 
    description: 'path to template' 
    required: true 
- report_full_template: 
    description: 'Indicated if the full template should be posted to github comment. Consider switchit it off for massive charts' 
    default: true 
    required: false 
- template_args: 
    description: 'Adds additional arguments to "helm template" command' 
    required: false 
