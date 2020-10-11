# JSON Schemas for Unreal Engine files

If your editor or validator supports [Schema Catalogs](https://www.schemastore.org/json/), simply add the
following schema catalog (in Visual Studio 2019, this is under Tools->Options->Text Editor->Json->Schema):

```
https://raw.githubusercontent.com/starkat99/unreal-schema/main/catalog.json
```

Otherwise, you can associate the following schemas to file types in your editor/validator:

### `.uproject` files

```
https://raw.githubusercontent.com/starkat99/unreal-schema/main/uproject.schema.json
```

### `.uplugin` files

```
https://raw.githubusercontent.com/starkat99/unreal-schema/main/uplugin.schema.json
```