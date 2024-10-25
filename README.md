# UserScript - Hide GitLab Migrate from Jenkins Widget

GitLab added a widget to the pipelines page that says "Migrate to GitLab CI/CD from Jenkins". Since GitLab doesn't currently have an option to permanently hide that widget, this userscript does it for you.

When using this userscript make sure to update the following line to match your domain if it doesn't already:
```js
// @match       https://gitlab.*/*/merge_requests/*
```
