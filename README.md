In your service's server-side `i18n.json` file, make sure to add `npm-hudl-payments` to the list of pre-loaded external sets.

```json
"version": 1.1,
"pre-load-external-sets": [
  "npm-hudl-payments"
],
"sets": {
  "your-service": {
    "keys": [
      "someKey",
      "anotherKey",
      "anotherKey",
    ],
    "base-language": {
      "someKey": "someTranslation",
      "anotherKey": "anotherTranslation",
      "anotherKey": "anotherTranslation"
    }
  }
}
```
