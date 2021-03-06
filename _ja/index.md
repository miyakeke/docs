---
layout: base
title:  'Japanese UD'
udver: '2'
---

# UD for Japanese <span class="flagspan"><img class="flag" src="../../flags/svg/AQ.svg" /></span>

## Tokenization and Word Segmentation

* In Japanese there is no obvious word boundary. So we need a definition of words.
  As the word definition for universal dependency (UD), we adopt short-unit word
  (SUW) [1]. SUW is also adopted to tokenize sentences in Balanced corpus of
  contemporary written Japanese (BCCWJ) [2] containing more than 60,000 sentences
  in various domains and it has been shown that the SUW definition covers various
  language phenomena in real texts.

* Many SUWs correspond to a single English word but they tend to be shorter than
  English counterparts. An example is "�t�����X ��" (French; French language).
  For detailed definition please refer to [3] written in Japanese.

* The automatic tokenization accuracy is more than 98% on in-domain data (BCCWJ) [4].

---



[1] A Proper Approach to Japanese Morphological Analysis: Dictionary, Model, and Evaluation,
Yasuharu Den, Junpei Nakamura, Toshinobu Ogiso, and Hideki Ogura,
In Proceedings of the Sixth International Conference on Language Resources and Evaluation, pp. 1019-1024, 2008.

[2] Balanced corpus of contemporary written Japanese,
Kikuo Maekawa, Makoto Yamazaki, Toshinobu Ogiso, Takehiko Maruyama, Hideki Ogura, Wakako Kashino, Hanae Koiso, Masaya Yamaguchi, Makiro Tanaka, and Yasuharu Den
Language Resources and Evaluation Vol. 48 345-371, May 2014.

[3] �w������{�ꏑ�����t�ύt�R�[�p�X�x�`�Ԙ_���K���W(��)(��)
���� �G��, ���� �ԊG, �y�m�r �D��, �{�� ���鍁, ���� ��, and �� �T,
�Ɨ��s���@�l�������ꌤ����, 2011.

[4] Language Resource Addition: Dictionary or Corpus?,
Shinsuke Mori and Graham Neubig,
In Proceedings of the Nineth International Conference on Language Resources and Evaluation, pp. 1631-1636, 2014.


<!-- **Instruction**: Describe the general rules for delimiting words (for example, based on whitespace and punctuation) and exceptions to these rules. Specify whether words with spaces and/or multiword tokens occur. Include links to further language-specific documentation if available.-->

---

## Morphology

### Tags

* to be described.

---
<!-- **Instruction**: Specify any unused tags. Explain what words are tagged as PART. Describe how the AUX-VERB and DET-PRON distinctions are drawn, and specify whether there are (de)verbal forms tagged as ADJ, ADV or NOUN. Include links to language-specific tag definitions if any.-->

---

### Features

* No features are provided.

---
<!-- **Instruction**: Describe inherent and inflectional features for major word classes (at least NOUN and VERB). Describe other noteworthy features. Include links to language-specific feature definitions if any. -->

---

## Syntax

* to be described.

---
<!-- **Instruction**: Give criteria for identifying core arguments (subjects and objects), and describe the range of copula constructions in nonverbal clauses. List all subtype relations used. Include links to language-specific relations definitions if any. -->

---

## Treebanks

There are [five](../treebanks/ja-comparison.html) Japanese UD treebanks:

  * [Japanese-GSD](../treebanks/ja_gsd/index.html)
  * [Japanese-BCCWJ](../treebanks/ja_bccws/index.html)
  * [Japanese-KTC](../treebanks/ja_ktc/index.html)
  * [Japanese-Modern](../treebanks/ja_modern/index.html)
  * [Japanese-PUD](../treebanks/ja_pud/index.html)

---
**Instruction**: Treebank-specific pages are generated automatically from the README file in the treebank repository and
from the data in the latest release. Link to the respective `*-index.html` page in the `treebanks` folder, using the language code
and the treebank code in the file name.

---
