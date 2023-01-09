<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [zotero-plugin-toolkit](./zotero-plugin-toolkit.md) &gt; [ItemTreeManager](./zotero-plugin-toolkit.itemtreemanager.md) &gt; [(constructor)](./zotero-plugin-toolkit.itemtreemanager._constructor_.md)

## ItemTreeManager.(constructor)

Initialize Zotero.\_ItemTreeExtraColumnsGlobal if it doesn't exist.

New columns and hooks are stored there.

Then patch `require("zotero/itemTree").getColumns` and `Zotero.Item.getField`

<b>Signature:</b>

```typescript
constructor(base?: BasicTool);
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  base | [BasicTool](./zotero-plugin-toolkit.basictool.md) | <i>(Optional)</i> |
