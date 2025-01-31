<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Bladeburner](./bitburner.bladeburner.md) &gt; [startAction](./bitburner.bladeburner.startaction.md)

## Bladeburner.startAction() method

Start an action.

**Signature:**

```typescript
startAction(
    type: BladeburnerActionType | `${BladeburnerActionType}`,
    name: BladeburnerActionName | `${BladeburnerActionName}`,
  ): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  type | [BladeburnerActionType](./bitburner.bladeburneractiontype.md) \| \`${[BladeburnerActionType](./bitburner.bladeburneractiontype.md)<!-- -->}\` | Type of action. |
|  name | [BladeburnerActionName](./bitburner.bladeburneractionname.md) \| \`${[BladeburnerActionName](./bitburner.bladeburneractionname.md)<!-- -->}\` | Name of action. Must be an exact match |

**Returns:**

boolean

True if the action was started successfully, and false otherwise.

## Remarks

RAM cost: 4 GB

Attempts to start the specified Bladeburner action. Returns true if the action was started successfully, and false otherwise.

## Example


```js
ns.bladeburner.startAction("Contracts", "Tracking")

// This will start the Bladeburner Contracts action of Tracking
```

