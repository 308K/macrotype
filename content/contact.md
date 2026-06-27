---
title: "联系我们"
layout: "single"
hideMeta: true
disableShare: true
---

我们一般不看SNS信息，如有必要，您可以通过[contact@kkn.moe](mailto:contact@kkn.moe)来联系我们，我们会尽力在72小时内回复。请注意，回复邮件将由形如`<UUID>@send.kkn.moe`的地址代发。

如需OpenPGP端到端加密，请往下看。

[下载我们的公钥](/files/0xC96B13D1925E94A6_public.asc)或在[keys.openpgp.org](https://keys.openpgp.org/search?q=contact@kkn.moe)获取。我们使用下面的算法：

| 用途 |      算法       |   备注   |
| :--: | :-------------: | :------: |
| 加密 | ML-KEM768X25519 |          |
| 加密 |     X25519      | 即将弃用 |
| 签名 |     Ed25519     |          |

如需我们使用OpenPGP端到端加密的方式回信，请确保我们可在keys.openpgp.org通过邮件地址查找到您的公钥，或随信附带公钥。以下是我们支持的算法：

```
Pubkey: RSA, ML-KEM(Kyber), ELG, DSA, ECDH, ECDSA, EDDSA
Cipher: IDEA, 3DES, CAST5, BLOWFISH, AES, AES192, AES256, TWOFISH,
        CAMELLIA128, CAMELLIA192, CAMELLIA256
Hash:   SHA1, RIPEMD160, SHA256, SHA384, SHA512, SHA224
```

以下是我们支持的椭圆曲线：`cv25519; ed25519; cv25519; ed25519; cv448; ed448; brainpoolP256r1; brainpoolP384r1; brainpoolP512r1; secp256k1`
