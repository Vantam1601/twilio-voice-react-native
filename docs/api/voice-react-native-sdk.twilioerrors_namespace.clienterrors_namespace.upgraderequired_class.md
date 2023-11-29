<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@twilio/voice-react-native-sdk](./voice-react-native-sdk.md) &gt; [TwilioErrors](./voice-react-native-sdk.twilioerrors_namespace.md) &gt; [ClientErrors](./voice-react-native-sdk.twilioerrors_namespace.clienterrors_namespace.md) &gt; [UpgradeRequired](./voice-react-native-sdk.twilioerrors_namespace.clienterrors_namespace.upgraderequired_class.md)

## TwilioErrors.ClientErrors.UpgradeRequired class

ClientErrors.UpgradeRequired error. Error code `31426`<!-- -->.

<b>Signature:</b>

```typescript
class UpgradeRequired extends TwilioError 
```
<b>Extends:</b> TwilioError

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(message)](./voice-react-native-sdk.twilioerrors_namespace.clienterrors_namespace.upgraderequired_class._constructor__constructor.md) |  | Constructs a new instance of the <code>UpgradeRequired</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [causes](./voice-react-native-sdk.twilioerrors_namespace.clienterrors_namespace.upgraderequired_class.causes_property.md) |  | string\[\] | Not applicable. |
|  [description](./voice-react-native-sdk.twilioerrors_namespace.clienterrors_namespace.upgraderequired_class.description_property.md) |  | string | Upgrade Required (HTTP) |
|  [explanation](./voice-react-native-sdk.twilioerrors_namespace.clienterrors_namespace.upgraderequired_class.explanation_property.md) |  | string | This error is raised when an HTTP 426 response is received. The reason for this is most likely because of an incompatible TLS version. To mitigate this, you may need to upgrade the OS or download a more recent version of the SDK. |
|  [name](./voice-react-native-sdk.twilioerrors_namespace.clienterrors_namespace.upgraderequired_class.name_property.md) |  | string | UpgradeRequired |
|  [solutions](./voice-react-native-sdk.twilioerrors_namespace.clienterrors_namespace.upgraderequired_class.solutions_property.md) |  | string\[\] | Not applicable. |
