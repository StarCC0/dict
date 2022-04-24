# StarCC Dictionaries

Dictionary for the Traditional-Simplified Chinese conversion framework

## Usage

**From Chinese variants to StarCC standard:**

```json
{
  "cn": ["STCharacters", "STPhrases"],
  "tw": ["TWVariantsRev", "TWVariantsRevPhrases"],
  "twp": ["TWVariantsRev", "TWVariantsRevPhrases", "TWPhrasesRev"],
  "hk": ["HKVariantsRev", "HKVariantsRevPhrases"],
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
  "jp": ["JPVariants"]
}
```

**Explanation of the Chinese variants above:**

- `cn`: Simplified Chinese (Mainland China)
- `tw`: Traditional Chinese (Taiwan)
- `twp`: Traditional Chinese (Taiwan, with phrase conversion)
- `hk`: Traditional Chinese (Hong Kong)
- `jp`: Japanese Shinjitai

## Source

Currently a mirror of [nk2028/opencc-data](https://github.com/nk2028/opencc-data).
