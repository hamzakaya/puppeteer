<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Frame](./puppeteer.frame.md) &gt; [waitForFunction](./puppeteer.frame.waitforfunction.md)

## Frame.waitForFunction() method

<b>Signature:</b>

```typescript
waitForFunction(pageFunction: Function | string, options?: {
        polling?: string | number;
        timeout?: number;
    }, ...args: SerializableOrJSHandle[]): Promise<JSHandle>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  pageFunction | Function \| string |  |
|  options | { polling?: string \| number; timeout?: number; } |  |
|  args | [SerializableOrJSHandle](./puppeteer.serializableorjshandle.md)<!-- -->\[\] |  |

<b>Returns:</b>

Promise&lt;[JSHandle](./puppeteer.jshandle.md)<!-- -->&gt;

