<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [zotero-plugin-toolkit](./zotero-plugin-toolkit.md) &gt; [VirtualizedTableHelper](./zotero-plugin-toolkit.virtualizedtablehelper.md) &gt; [setProp](./zotero-plugin-toolkit.virtualizedtablehelper.setprop.md)

## VirtualizedTableHelper.setProp() method

Set properties by name.

**Signature:**

```typescript
setProp<K extends keyof VirtualizedTableProps, V extends VirtualizedTableProps[K]>(propName: K, propValue: V): VirtualizedTableHelper;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  propName | K | Property name |
|  propValue | V | Property value |

**Returns:**

[VirtualizedTableHelper](./zotero-plugin-toolkit.virtualizedtablehelper.md)

## Remarks

`id` and `getRowCount` are required. If `id` is not set, it's a random string.

