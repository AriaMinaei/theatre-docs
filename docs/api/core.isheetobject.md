<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@theatre/core](./core.md) &gt; [ISheetObject](./core.isheetobject.md)

## ISheetObject interface

<b>Signature:</b>

```typescript
export interface ISheetObject<Props extends IShorthandCompoundProps = {}> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [address](./core.isheetobject.address.md) | SheetObjectAddress | An object representing the address of the Object |
|  [project](./core.isheetobject.project.md) | [IProject](./core.iproject.md) | The Project the project belongs to |
|  [props](./core.isheetobject.props.md) | [Pointer](./dataverse.pointer.md)<!-- -->&lt;this\['value'\]&gt; | A Pointer to the props of the object.<!-- -->More documentation soon. |
|  [sheet](./core.isheetobject.sheet.md) | [ISheet](./core.isheet.md) | The instance of Sheet the Object belongs to |
|  [type](./core.isheetobject.type.md) | 'Theatre\_SheetObject\_PublicAPI' | All Objects will have <code>object.type === 'Theatre_SheetObject_PublicAPI'</code> |
|  [value](./core.isheetobject.value.md) | ShorthandPropToLonghandProp&lt;Props&gt;\['valueType'\] | The current values of the props. |

## Methods

|  Method | Description |
|  --- | --- |
|  [onValuesChange(fn)](./core.isheetobject.onvalueschange.md) | Calls <code>fn</code> every time the value of the props change. |
