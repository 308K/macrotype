---
title: "联系我们 / Contact Us"
layout: "single"
hideMeta: true
disableShare: true
---

我们一般不看SNS消息，如有必要，可以通过[contact@kkn.moe](mailto:contact@kkn.moe)来联系我们，我们会尽力在72小时内回复。请注意，回复邮件将由形如`<UUID>@send.kkn.moe`的地址代发。

<p lang='en'>We generally do not check social media messages. If necessary, please contact us at <a href="mailto:contact@kkn.moe">contact@kkn.moe</a>; we will do our best to reply within 72 hours. Please note that email replies will be sent from an address in the format <code>&lt;UUID&gt;@send.kkn.moe</code>.</p>


如需OpenPGP端到端加密，请往下看。

<p lang='en'>If you need OpenPGP end-to-end encryption, please read on.</p>

[下载我们的公钥](/files/0xC96B13D1925E94A6_public.asc)或在[keys.openpgp.org](https://keys.openpgp.org/search?q=contact@kkn.moe)获取。我们使用下面的算法：

<p lang='en'><a href="/files/0xC96B13D1925E94A6_public.asc">Download our public key</a> or get it from <a href="https://keys.openpgp.org/search?q=contact@kkn.moe">keys.openpgp.org</a>. We use the following algorithms:</p>

|  用途 / <span lang='en'>Purpose</span>   | 算法 / <span lang='en'>Algorithm</span> |        备注 / <span lang='en'>Notes</span>         |
| :--------------------------------------: | :-------------------------------------: | :------------------------------------------------: |
| 加密 / <span lang='en'>Encryption</span> |             ML-KEM768X25519             |                                                    |
| 加密 / <span lang='en'>Encryption</span> |                 X25519                  | 即将弃用 / <span lang='en'>To be deprecated</span> |
| 签名 / <span lang='en'>Signature</span>  |                 Ed25519                 |                                                    |

如需我们使用OpenPGP端到端加密的方式回信，请确保我们可在keys.openpgp.org通过邮件地址查找到您的公钥，或随信附带公钥。以下是我们支持的算法：

<p lang='en'>If you would like us to reply using OpenPGP end-to-end encryption, please ensure that your public key can be found via your email address on keys.openpgp.org, or attach your public key to your message. The following are the algorithms we support:</p>

```
Pubkey: RSA, ML-KEM(Kyber), ELG, DSA, ECDH, ECDSA, EDDSA
Cipher: IDEA, 3DES, CAST5, BLOWFISH, AES, AES192, AES256, TWOFISH,
        CAMELLIA128, CAMELLIA192, CAMELLIA256
Hash:   SHA1, RIPEMD160, SHA256, SHA384, SHA512, SHA224
```

以下是我们支持的椭圆曲线：

<p lang='en'>The following are the elliptic curves we support:</p>

`cv25519; ed25519; cv25519; ed25519; cv448; ed448; brainpoolP256r1; brainpoolP384r1; brainpoolP512r1; secp256k1`
