---
name: Jenkinsfile Work Item
about: 
title: " {{ payload.issue.title }} "
labels: jenkinsfile-transformer
assignees:
---

copied from: #{{ payload.issue.number }}

{{ payload.issue.body }}
