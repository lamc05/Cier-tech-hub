---
name: Feature Request
description: Submit a feature request to enhance the project.
title: "[FEATURE] "
labels: ["feature request"]
body:
  - type: markdown
    attributes:
      value: "## Feature Description\n\nDescribe the feature you'd like to request and why you think it would be valuable."
  - type: input
    id: feature_name
    attributes:
      label: "Feature Name"
      description: "Name for the requested feature"
  - type: textarea
    id: feature_reason
    attributes:
      label: "Reason for Request"
      description: "Explain why this feature is needed."
  - type: checkbox
    id: impact
    attributes:
      label: "Impact of Feature"
      description: "How would this feature impact the project?"
      options:
        - label: "High"
          value: "high"
        - label: "Medium"
          value: "medium"
        - label: "Low"
          value: "low"
  - type: input
    id: examples
    attributes:
      label: "Use Case Examples"
      description: "Provide one or more examples of how this feature would be used."
  - type: input
    id: additional_info
    attributes:
      label: "Additional Information"
      description: "Any additional information you feel we should consider?"
---
