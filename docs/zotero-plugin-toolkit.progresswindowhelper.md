<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [zotero-plugin-toolkit](./zotero-plugin-toolkit.md) &gt; [ProgressWindowHelper](./zotero-plugin-toolkit.progresswindowhelper.md)

## ProgressWindowHelper class

ProgressWindow helper.

**Signature:**

```typescript
export declare class ProgressWindowHelper extends Zotero.ProgressWindow 
```
**Extends:** Zotero.ProgressWindow

## Example 1

Show a popup with success icon

```ts
const tool = new ZoteroTool();
tool.createProgressWindow("Addon").createLine({
  type: "success",
  text: "Finish"
  progress: 100,
}).show();
```

## Example 2

Show a popup and change line content

```ts
const compat = new ZoteroCompat();
const tool = new ZoteroTool();
const popupWin = tool.createProgressWindow("Addon").createLine({
  text: "Loading"
  progress: 50,
}).show(-1);
// Do operations
compat.getGlobal("setTimeout")(()=>{
  popupWin.changeLine({
    text: "Finish",
    progress: 100,
  });
}, 3000);
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(header, options)](./zotero-plugin-toolkit.progresswindowhelper._constructor_.md) |  | Constructs a new instance of the <code>ProgressWindowHelper</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [show](./zotero-plugin-toolkit.progresswindowhelper.show.md) |  | typeof \_popupWindowShow |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [changeLine(options)](./zotero-plugin-toolkit.progresswindowhelper.changeline.md) |  | Change the line content |
|  [createLine(options)](./zotero-plugin-toolkit.progresswindowhelper.createline.md) |  | Create a new line |
|  [setIconURI(key, uri)](./zotero-plugin-toolkit.progresswindowhelper.seticonuri.md) | <code>static</code> | Set custom icon uri for progress window |

