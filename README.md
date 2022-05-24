# Dialect-Comparison
Taiwan Mandarin (TM) and China Mandarin (CM) comparison with n-grams

This project compares 2 linguistic patterns in the two corpora:
1) N-grams:
	In Mandarin, each syllable is represented by a character. A character may carry its own meaning, have an extended or converted meaning when combined with other characters, or need to co-exist with other characters to possess meaningful reference.  E.g., fairy tale is translated as “Tong2 Hua4;” however, if Tong2 Hua4 is taken apart individually, they mean different things (Tong2: child/children; Hua4: utterance). Therefore, n-grams (1<=n<=3) and their frequency in each corpus (TM and CM) will be collected with the most frequent n-grams extracted and compared to the n-gram collection from the other dialect. If the most frequent n-grams do not exist throughout the other corpus or at very low frequency,  then it is considered unique in that dialect. 
2) Sentence-final particles (SFP):
	Through informal observation, it was noted that TM speakers use  SFP more frequently and with more variation compared to CM speakers. The spoken corpus provides a great opportunity to objectively document the observable differences if present. Hence, types and frequency of SFP will be recorded from each dialect for comparison. If the observation is supported by the corpus data, these SFP may indicate sentences ending in natural speech inputs. 

Results:
Overall, the n-gram models seem to be able to identify meaningful language differences in TM speech and CM speech in 1/3 of the results. It was originally expected that the differences will mostly concentrate on more modern terms, e.g., video, cell phones, but the results showed differences in various domains, many in adjectives and adverbs, like 爆 (explodingly) in TM and 肯定 (definitely) in CM, and in SFP uses. A few of them involve slightly different references or different word preferences, like 估計 (estimate/guessing) in CM, and 譬如說 vs 比方說 (both mean “for example” but are unique in each corpus). When examined in the original corpus, these differences can often be better understood and categorized. That is, context is crucial when analyzing a language corpus.
SFPs also showed divergent use between the two dialects of Mandarin. TM appeared to use SFPs of greater variability and at higher frequency. However, because of the corpus data differences (mainly the significant difficulties to define sentence ends in CM data), the difference degrees may vary depending on the examination method.




TM corpus source:
http://spokentaiwanmandarin.nccu.edu.tw

CM corpus source:
Li, L. (2021). A spoken Chinese corpus: Development, description, and application in L2 studies [Unpublished Doctoral dissertation]. Massey University. https://github.com/blculyn
