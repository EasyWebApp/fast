---
id: fast-foundation.datagridrow
title: DataGridRow class
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-foundation](./fast-foundation.md) &gt; [DataGridRow](./fast-foundation.datagridrow.md)

## DataGridRow class

A Data Grid Row Custom HTML Element.


row-focused - Fires a custom 'row-focused' event when focus is on an element (usually a cell or its contents) in the row


- The default slot for custom cell elements

<b>Signature:</b>

```typescript
export declare class DataGridRow extends FoundationElement 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [cellItemTemplate](./fast-foundation.datagridrow.cellitemtemplate.md) |  | [ViewTemplate](./fast-element.viewtemplate.md) | The template used to render cells in generated rows. |
|  [columnDefinitions](./fast-foundation.datagridrow.columndefinitions.md) |  | [ColumnDefinition](./fast-foundation.columndefinition.md)<!-- -->\[\] \| null | The column definitions of the row |
|  [gridTemplateColumns](./fast-foundation.datagridrow.gridtemplatecolumns.md) |  | string | String that gets applied to the the css gridTemplateColumns attribute for the row |
|  [headerCellItemTemplate](./fast-foundation.datagridrow.headercellitemtemplate.md) |  | [ViewTemplate](./fast-element.viewtemplate.md) | The template used to render header cells in generated rows. |
|  [rowData](./fast-foundation.datagridrow.rowdata.md) |  | object \| null | The base data for this row |
|  [rowIndex](./fast-foundation.datagridrow.rowindex.md) |  | number | The index of the row in the parent grid. This is typically set programmatically by the parent grid. |
|  [rowType](./fast-foundation.datagridrow.rowtype.md) |  | [DataGridRowTypes](./fast-foundation.datagridrowtypes.md) | The type of row |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [handleCellFocus(e)](./fast-foundation.datagridrow.handlecellfocus.md) |  |  |
|  [handleFocusout(e)](./fast-foundation.datagridrow.handlefocusout.md) |  |  |
|  [handleKeydown(e)](./fast-foundation.datagridrow.handlekeydown.md) |  |  |