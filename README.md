# StarCC Dictionaries

Dictionary for the Traditional-Simplified Chinese conversion framework

## Usage

**From Chinese variants to StarCC standard:**

```json
{
  "cn": ["STCharacters", "STPhrases"],
  "hk": ["HKVariantsRev", "HKVariantsRevPhrases"],
  "tw": ["TWVariantsRev", "TWVariantsRevPhrases"],
  "twp": ["TWVariantsRev", "TWVariantsRevPhrases", "TWPhrasesRev"],
  "cnt": ["CNTradVariantsRev", "CNTradRevPhrases"],
  "jp": ["JPVariantsRev", "JPShinjitaiCharacters", "JPShinjitaiPhrases"]
}
```

**From StarCC standard to Chinese variants:**

```json
{
  "cn": ["TSCharacters", "TSPhrases"],
  "hk": ["HKVariants"],
  "tw": ["TWVariants"],
  "twp": ["TWVariants", "TWPhrasesIT", "TWPhrasesName", "TWPhrasesOther"],
  "cnt": ["CNTradVariants", "CNTradPhrases"],
  "jp": ["JPVariants"]
}
```

**Explanation of the Chinese variants above:**

- `cn`: Simplified Chinese (Mainland China)
- `tw`: Traditional Chinese (Taiwan)
- `twp`: Traditional Chinese (Taiwan, with phrase conversion)
- `hk`: Traditional Chinese (Hong Kong)
- `cnt`: Traditional Chinese (Mainland China)
- `jp`: Japanese Shinjitai

The support of `cnt` is currently experimental.

## Source

Main dictionary is a mirror of [nk2028/opencc-data](https://github.com/nk2028/opencc-data), distributed under the Apache 2.0 License.

The experimental `cnt` data is from [mrhso/OpenCC_CN-draft](https://github.com/mrhso/OpenCC_CN-draft).
