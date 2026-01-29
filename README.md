Repository to link japanese frequently used vocabulary to the kanji order in Remembering the Kanji by James W. Heisig (6th edition).

### heisig kanjis
The dataset heisig_kanjis.csv contains 3 columns:
- Kanji: the kanji appearing in the book Remembering the Kanji, in the same order
- Heisig_number: the number associated to the kanji in the book
- Chapter: the chapter in which tje kanji appear

### JP Vocabulary
The dataset jp_freq_translation_reading.csv contains 6 columns. The words and frequency come from https://www.manythings.org/japanese/words/leeds/. 
- Word: japanese words (can be a gramatical particle too)
- Frequency:  frequency distribution dounf in the corpus 'internet-jp'
- Reading: reading of the word in Hiragana (or Katakana if the word itself is completely in katakana)
- English: translation of the word in english (in case of a grammatical particle, the function of the particle is given, e.g Nominalizer)
- Heisig_numbers: a list of the heisig_number of the kanjis composing the word. If the word has no kanji, heisig_number is an empty list. If there are kanjis in the word that do not exist in the book Remembering the Kanji, they are given the number 9999 
- Heisig_chapter: the chapter of the book Remembering the Kanji that needs to be reached (and finished) to learn this word. The chapter are supposed to be learned in the order of the book. (e.g word:委員; heisig_numbers:[979, 59]; chapter:26; To know all the kanjis in this word, one has to have reached and finished the chapter 26).

### Jokugo Vocabulary
The dataset jokugos_freq_db_heisig_hiragana.csv contains 7 columns. This dataset only contains words with 2 kanji inside. The frequency was counted from apparition in news content.
- Composite_word: japanese words with 2 kanjis
- Frequency: frequency distribution from apparition in news content.
- Grammatical_feature: adverb, noun etc.
- Pronunciation: prononciation of the kanji is given in Hiragana
- English Translation: the english translation of the word
- Heisig_numbers: a list of the heisig_number of the kanjis composing the word. If the word has no kanji, heisig_number is an empty list. If there are kanjis in the word that do not exist in the book Remembering the Kanji, they are given the number 9999 
- Heisig_chapter: the chapter of the book Remembering the Kanji that needs to be reached (and finished) to learn this word. The chapter are supposed to be learned in the order of the book. (e.g word:首相;heisig_numbers:[74, 222]; chapter:10; To know all the kanjis in this word, one has to have reached and finished the chapter 10).
