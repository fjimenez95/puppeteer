<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Network](./puppeteer.protocol.network.md) &gt; [SignedExchangeSignature](./puppeteer.protocol.network.signedexchangesignature.md)

## Protocol.Network.SignedExchangeSignature interface

Information about a signed exchange signature. https://wicg.github.io/webpackage/draft-yasskin-httpbis-origin-signed-exchanges-impl.html\#rfc.section.3.1

<b>Signature:</b>

```typescript
export interface SignedExchangeSignature 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [certificates](./puppeteer.protocol.network.signedexchangesignature.certificates.md) | string\[\] | The encoded certificates. |
|  [certSha256](./puppeteer.protocol.network.signedexchangesignature.certsha256.md) | string | The hex string of signed exchange signature cert sha256. |
|  [certUrl](./puppeteer.protocol.network.signedexchangesignature.certurl.md) | string | Signed exchange signature cert Url. |
|  [date](./puppeteer.protocol.network.signedexchangesignature.date.md) | [integer](./puppeteer.protocol.integer.md) | Signed exchange signature date. |
|  [expires](./puppeteer.protocol.network.signedexchangesignature.expires.md) | [integer](./puppeteer.protocol.integer.md) | Signed exchange signature expires. |
|  [integrity](./puppeteer.protocol.network.signedexchangesignature.integrity.md) | string | Signed exchange signature integrity. |
|  [label](./puppeteer.protocol.network.signedexchangesignature.label.md) | string | Signed exchange signature label. |
|  [signature](./puppeteer.protocol.network.signedexchangesignature.signature.md) | string | The hex string of signed exchange signature. |
|  [validityUrl](./puppeteer.protocol.network.signedexchangesignature.validityurl.md) | string | Signed exchange signature validity Url. |
