# Json schema test

ALl "json" test files should contain errors. Ideally theese errors should be reported in the editor before a file is loaded.

## products.json and products.jsonc
Uses the vs code feature to map json schemas to a file inside the root:

> To map a schema that is located in the workspace, use a relative path. In this example, a file in the workspace root called myschema.json will be used as the schema for all files ending with .foo.json.

```json
"json.schemas": [
    {
        "fileMatch": [
            "/*.foo.json"
        ],
        "url": "./myschema.json"
    }
]
```

[Mapping to a schema in the workspace#](https://code.visualstudio.com/docs/languages/json#_mapping-to-a-schema-in-the-workspace)

