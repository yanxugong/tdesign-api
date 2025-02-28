:: BASE_DOC ::

## API
### TimeRangePicker Props

name | type | default | description | required
-- | -- | -- | -- | --
className | String | - | 类名 | N
style | Object | - | 样式，Typescript：`React.CSSProperties` | N
allowInput | Boolean | false | \- | N
clearable | Boolean | false | \- | N
disableTime | Function | - | Typescript：`(h: number, m: number, s: number, context: { partial: TimeRangePickerPartial }) =>Partial<{ hour: Array<number>, minute: Array<number>, second: Array<number> }>` `type TimeRangePickerPartial = 'start' \| 'end'`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/time-picker/type.ts) | N
disabled | Boolean / Array | false | Typescript：`boolean \| Array<boolean>` | N
format | String | HH:mm:ss | \- | N
hideDisabledTime | Boolean | true | \- | N
placeholder | String / Array | undefined | Typescript：`string \| Array<string>` | N
popupProps | Object | - | Typescript：`PopupProps`，[Popup API Documents](./popup?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/time-picker/type.ts) | N
presets | Object | - | Typescript：`PresetTimeRange` `interface PresetTimeRange { [presetRageName: string]: TimeRangeValue \| (() => TimeRangeValue)}`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/time-picker/type.ts) | N
rangeInputProps | Object | - | Typescript：`RangeInputProps`，[RangeInput API Documents](./range-input?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/time-picker/type.ts) | N
size | String | medium | options：small/medium/large | N
status | String | - | options：default/success/warning/error | N
steps | Array | [1, 1, 1] | Typescript：`Array<string \| number>` | N
tips | TNode | - | Typescript：`string \| TNode`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
value | Array | - | Typescript：`TimeRangeValue` `type TimeRangeValue = Array<string>`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/time-picker/type.ts) | N
defaultValue | Array | - | uncontrolled property。Typescript：`TimeRangeValue` `type TimeRangeValue = Array<string>`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/time-picker/type.ts) | N
onBlur | Function |  | Typescript：`(context: { value: TimeRangeValue; e?: FocusEvent; position?: TimeRangePickerPartial })  => void`<br/>[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/time-picker/type.ts)。<br/>`type TimeRangePickerPartial = 'start' \| 'end'`<br/> | N
onChange | Function |  | Typescript：`(value: TimeRangeValue) => void`<br/> | N
onFocus | Function |  | Typescript：`(context?: { value: TimeRangeValue; e?: FocusEvent; position?: TimeRangePickerPartial })  => void`<br/>[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/time-picker/type.ts)。<br/>`type TimeRangePickerPartial = 'start' \| 'end'`<br/> | N
onInput | Function |  | Typescript：`(context: { value: TimeRangeValue; e?: InputEvent; position?: TimeRangePickerPartial  })  => void`<br/>[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/time-picker/type.ts)。<br/>`type TimeRangePickerPartial = 'start' \| 'end'`<br/> | N
onPick | Function |  | Typescript：`(value: TimeRangeValue, context: { e: MouseEvent, position?: TimeRangePickerPartial }) => void`<br/> | N
