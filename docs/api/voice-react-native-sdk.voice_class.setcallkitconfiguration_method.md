<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@twilio/voice-react-native-sdk](./voice-react-native-sdk.md) &gt; [Voice](./voice-react-native-sdk.voice_class.md) &gt; [setCallKitConfiguration](./voice-react-native-sdk.voice_class.setcallkitconfiguration_method.md)

## Voice.setCallKitConfiguration() method

Custom iOS CallKit configuration.

<b>Signature:</b>

```typescript
setCallKitConfiguration(configuration: CallKit.ConfigurationOptions): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  configuration | [CallKit.ConfigurationOptions](./voice-react-native-sdk.callkit_namespace.configurationoptions_typealias.md) | iOS CallKit configuration options. |

<b>Returns:</b>

Promise&lt;void&gt;

A `Promise` that - Resolves when the configuration has been applied. - Rejects if the configuration is unable to be applied.

## Remarks

Unsupported platforms: - Android

See [CallKit](./voice-react-native-sdk.callkit_namespace.md) for more information.
