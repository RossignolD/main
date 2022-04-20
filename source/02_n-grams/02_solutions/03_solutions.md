## Exercise 1
- The negative 3-gram grammar that describes intervocalic voicing for this set of sounds is {*afa, *afi, *afu, *ifa, *ifi, *ifu, *ufa, *ufi, *ufu, *asa, *asi, *asu, *isa, *isi, *isu, *usa, *usi, *usu}. This is a negative 3-gram grammar because each of the forbidden n-grams is a 3-gram, and we are listing out which combinations are not allowed, rather than which combinations are permitted. These are all the forbidden combinations because they each have a voiceless sound (s, f) between two vowels, and this is forbidden by the principle of intervocalic voicing.
- The negative 2-gram grammar that describes local assimilation for this set of sounds is {*np, *nb}. This is a negative 2-gram grammar because each of the forbidden n-grams is a 2-gram that is disallowed by the rule, rather than allowed. These are all the forbidden combinations because they have a nasal with a different place of articulation than the stop which follows.
- The negative 3-gram grammar that describes local dissimilation for this set of sounds is {*rar, *rir, *rur}. This is a negative 3-gram grammar because each of the forbidden n-grams is a 3-gram, and we are listing out which combinations are not allowed, rather than which combinations are permitted. These are all the forbidden 3-grams because they each have the same sound occuring with a vowel in between, and by the dissimilation rule, this cannot occur.
- The negative 3-gram grammar that describes this phenomenon is {*$\sigma \sigma${{{R}}}, *$\acute{\sigma} \acute{\sigma}$ {{{R}}}, *$\sigma \acute{\sigma}${{{R}}}, *$\sigma \sigma \acute{\sigma}$, *$\sigma \acute{\sigma} \acute{\sigma}$, *$\acute{\sigma} \acute{\sigma} \acute{\sigma}$, *$\acute{\sigma} \sigma \sigma$, *$\acute{\sigma} \acute{\sigma} \sigma$, *$\acute{\sigma} \sigma \acute{\sigma}$, *$\sigma \acute{\sigma} \sigma$}. This is a negative 3-gram grammar because each of the n-grams in it is a 3-gram, and we are specifying which ones are not permitted, rather than the ones that are. An answer to this problem that would not be correct would be { *$\sigma \sigma${{{R}}}, *$\acute{\sigma} \acute{\sigma}$ {{{R}}}, *$\sigma \acute{\sigma}${{{R}}}} because it only covers the cases that occur at the right--hand boundary of the word, and not before. This incorrect negative 3-gram grammar would permit the string $\acute{\sigma} \acute{\sigma} \sigma \acute{\sigma} \sigma$, which is not permitted because it has stressed syllables that are not penultimate.

## Exercise 2
- *de-* is a trigram if one views the basic building blocks as typed characters. The three components of the trigram would be *d*, *e*, and *-*. It could also be viewed as a unigram if one views the basic building blocks as morphemes.
- *mpi* is a trigram if one views the basic building blocks as typed characters. The three components of the trigram would be *m*, *p*, and *i*. If one views the basic building blocks as words, it could be a unigram.
- *John likes Mary* is a trigram if one views the basic building blocks as words. The three components are the three words. It could also be a 4-gram if one views the basic building blocks as morphemes. In this case, the four components are *John*, *like*, *-s* and *Mary*. If one views the the basic building blocks as characters (and include spaces), this could be analyzed as a 15-gram.

## Exercise 3
Positive grammar for this string language: {{{{L}}}a, b{{{R}}}}, ab, ba}
Negative grammar for this string language: {*{{{L}}}b, *a{{{R}}}, *aa, 
*bb} The positive grammar seems to be much more succinct and explanatory 
than the negative grammar. If the set of symbols were larger, the negative grammar would become even larger, but the positive grammar would not grow.
[insert amount grown here]

## Exercise 4
- The positive 3-gram gramar for intervocalic voicing with these symbols must capture the fact that the only allowed Vowel-Consonant-Vowel patterns are those with a voiced segment between the vowels. Therefore, the positve 3-gram grammar must be {aza, azi, azu, iza, izi, izu, uza, uzi, uzu, ava, avi, avu, iva, ivi, ivu, uva, uvi, uvu}
- The 2-gram grammaar that is needed is {mb, nb}
