[@tevm/schemas](../README.md) / [Modules](../modules.md) / [ethereum](../modules/ethereum.md) / InvalidBytesFixedError

# Class: InvalidBytesFixedError

[ethereum](../modules/ethereum.md).InvalidBytesFixedError

Error thrown when a FixedByte is invalid.
A FixedByte string is invalid if it's not within the bounds of its size.

## Hierarchy

- `TypeError`

  ↳ **`InvalidBytesFixedError`**

## Table of contents

### Constructors

- [constructor](ethereum.InvalidBytesFixedError.md#constructor)

### Properties

- [cause](ethereum.InvalidBytesFixedError.md#cause)
- [message](ethereum.InvalidBytesFixedError.md#message)
- [name](ethereum.InvalidBytesFixedError.md#name)
- [stack](ethereum.InvalidBytesFixedError.md#stack)
- [prepareStackTrace](ethereum.InvalidBytesFixedError.md#preparestacktrace)
- [stackTraceLimit](ethereum.InvalidBytesFixedError.md#stacktracelimit)

### Methods

- [captureStackTrace](ethereum.InvalidBytesFixedError.md#capturestacktrace)

## Constructors

### constructor

• **new InvalidBytesFixedError**(`options`): [`InvalidBytesFixedError`](ethereum.InvalidBytesFixedError.md)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `options` | `Object` | The options for the error. |
| `options.bytes` | `string` | The invalid bytes string. |
| `options.cause` | `undefined` \| readonly [`ParseErrors`, `ParseErrors`] | The cause of the error. |
| `options.docs` | `undefined` \| `string` | The documentation URL. |
| `options.message` | `undefined` \| `string` | The error message. |
| `options.size` | [`BytesCapacity`](../modules/ethereum.md#bytescapacity) | The size of the bytes. |

#### Returns

[`InvalidBytesFixedError`](ethereum.InvalidBytesFixedError.md)

#### Overrides

TypeError.constructor

#### Defined in

[packages/schemas/src/ethereum/SBytesFixed/Errors.js:28](https://github.com/evmts/tevm-monorepo/blob/main/packages/schemas/src/ethereum/SBytesFixed/Errors.js#L28)

## Properties

### cause

• **cause**: `undefined` \| `string`

#### Inherited from

TypeError.cause

#### Defined in

[packages/schemas/src/ethereum/SBytesFixed/Errors.js:40](https://github.com/evmts/tevm-monorepo/blob/main/packages/schemas/src/ethereum/SBytesFixed/Errors.js#L40)

___

### message

• **message**: `string`

#### Inherited from

TypeError.message

#### Defined in

node_modules/.pnpm/typescript@5.3.3/node_modules/typescript/lib/lib.es5.d.ts:1076

___

### name

• **name**: `string`

#### Inherited from

TypeError.name

#### Defined in

node_modules/.pnpm/typescript@5.3.3/node_modules/typescript/lib/lib.es5.d.ts:1075

___

### stack

• `Optional` **stack**: `string`

#### Inherited from

TypeError.stack

#### Defined in

node_modules/.pnpm/typescript@5.3.3/node_modules/typescript/lib/lib.es5.d.ts:1077

___

### prepareStackTrace

▪ `Static` `Optional` **prepareStackTrace**: (`err`: `Error`, `stackTraces`: `CallSite`[]) => `any`

#### Type declaration

▸ (`err`, `stackTraces`): `any`

Optional override for formatting stack traces

##### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `Error` |
| `stackTraces` | `CallSite`[] |

##### Returns

`any`

**`See`**

https://v8.dev/docs/stack-trace-api#customizing-stack-traces

#### Inherited from

TypeError.prepareStackTrace

#### Defined in

node_modules/.pnpm/@types+node@20.9.1/node_modules/@types/node/globals.d.ts:11

node_modules/.pnpm/@types+node@20.10.6/node_modules/@types/node/globals.d.ts:28

___

### stackTraceLimit

▪ `Static` **stackTraceLimit**: `number`

#### Inherited from

TypeError.stackTraceLimit

#### Defined in

node_modules/.pnpm/@types+node@20.9.1/node_modules/@types/node/globals.d.ts:13

node_modules/.pnpm/@types+node@20.10.6/node_modules/@types/node/globals.d.ts:30

## Methods

### captureStackTrace

▸ **captureStackTrace**(`targetObject`, `constructorOpt?`): `void`

Create .stack property on a target object

#### Parameters

| Name | Type |
| :------ | :------ |
| `targetObject` | `object` |
| `constructorOpt?` | `Function` |

#### Returns

`void`

#### Inherited from

TypeError.captureStackTrace

#### Defined in

node_modules/.pnpm/@types+node@20.9.1/node_modules/@types/node/globals.d.ts:4

▸ **captureStackTrace**(`targetObject`, `constructorOpt?`): `void`

Create .stack property on a target object

#### Parameters

| Name | Type |
| :------ | :------ |
| `targetObject` | `object` |
| `constructorOpt?` | `Function` |

#### Returns

`void`

#### Inherited from

TypeError.captureStackTrace

#### Defined in

node_modules/.pnpm/@types+node@20.10.6/node_modules/@types/node/globals.d.ts:21