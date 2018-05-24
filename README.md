# Natural Verb Clusters in Biblical Hebrew 
## An Empirical, Text-Linguistic Approach to the Verb's Semantic Categorization

### An Introduction
What is the most natural categorization for verbs in Biblical Hebrew? Do our usual semantic classifications apply? What is the nature of categorization when it comes to abstract linguistic phenomena? This project seeks an answer to these questions. Over the recent years, linguists in Biblical Hebrew have come to recognize a deficiency in the area of semantics, that is, in the linguistic analysis of word meaning (see, for instance, Shead 2011, de Blois 2000, and the ongoing Semantics of Ancient Hebrew Database project). One oversight in particular has been the interface of lexicon and syntax, i.e. of word lemmas and the grammatical arguments which surround them (Shead 2011). Under the influence of structuralist linguistics, Hebraists have tended to view semantics and syntax as two distinct components of language (Shead 2011: 69-86; Van Hecke 2011: 286-294). However, work in corpus linguistics (e.g. Stefanowitsch 2003) and cognitive linguistics (e.g. Goldberg 1995) has questioned the strict division between the two areas. 

Over the last decade, important work has been done on the syntax and semantics of the Hebrew verb. Cook's *Time and the Biblical Hebrew Verb* (2012) argues strongly for a thoroughly semantic approach to the verbal system, while also contending for an aspect-based view of the verb. Meanwhile, Joosten has argued, instead, for a tense-based understanding (2012) while taking note of word order. Kalkman's study examined the modality function of the yiqtol in the context of a clause's discourse relations (2015); he also argues for the merits of a text-linguistic (discourse) approach. On another front, Dyk has shown how a verb's syntactic arguments contribute to its lexical meaning (e.g. 2017).

All of these studies grapple with the same basic question: what **is** the verb in Biblical Hebrew? Is it a semantic entity (Cook)? Is it a syntactic one (Joosten)? Is it a discourse marker (Kalkman)? Is it a valence pattern (Dyk)? Of course, each of these questions come from different perspectives, and address different areas of verbal grammar. On the other hand, the answer to each question necessarily affects the other.

One of the most interesting aspects of studies on the Hebrew verb is just how much they highlight methodological differences (see McFall 1982 for an excellent survey, also Cook 2012: 77-175). They ultimately reveal our complete reliance on our theoretical commitments. No one, under any rubric, is free from it. On the other hand, that reliance also presents big problems for obtaining an accurate understanding of a very distant, and dead language like Biblical Hebrew. This problem has occasionally been dismissed. For example, one of the methodological traditions which has sought to highlight and overcome this problem is the so-called form-to-function, discourse analysis approach (van der Merwe 1994). Form-to-function approaches seek to define linguistic functions in terms of their formal (i.e. explicit, empirical) distribution across aspects of a language. This often involves detailed analysis of forms and their patterns, with the use of statistics to describe their distribution. Yet, form-to-function analysis has remained restricted to a small group of researchers (Talstra and the Schneider school) whose commitments have never found a home in the mainstream. Van der Merwe characterizes the form-to-function method so:

> The form-to-function approaches...demand long and tedious studies that often yield relatively few results. It is assumed that it is necessary to treat the formal data at the lower levels exhaustively before any phenomenon is treated on a higher level...simply because there are no Biblical Hebrew speakers to consult. (1994: 16)

In a similar vein, others have argued against the need for caution with the study of dead languages on the grounds of linguistic universals (e.g. Cook 2012: 129). The use of statistical distribution as a method has also been strongly challenged by Cook: 

> A similar sort of a priori understanding of the BHVS seems to underlie the widespread and favored use of statistics (e.g., Furuli 2006; Penner 2006). The use of statistics provides a misleading sense of objectivity and definitiveness to the enterprise, because it mimics empirical science. However, in the end the statistics only serve as a tally of the interpreter’s subjective and often predetermined semantic interpretation of the forms of the BHVS. Statistics cannot serve to validate semantic interpretation, which still partakes of human enterprise. Statistics are only valid when they tally objectively measurable things, such as the number of times a distinctly Jussive form of the verb appears clause initially (e.g., Shulman 1996). Statistical studies are even unnecessary for gathering the requisite data for analysis, because their results are readily available in the standard reference grammars, old and more-recent, including examples of both “standard” meanings (e.g., Waltke and O’Connor 1990; van der Merwe, Kroeze, and Naudé 1999) and “inexplicable” uses (e.g., Gesenius 1910; Joüon 1923). The real challenge, then, is validation: How can one validate a theory of the BHVS? (2012: 184)

Such a sentiment is echoed by Joosten, who writes that "[s]tatistics are of limited value in linguistic research" (2002: 65). Since the form-to-function method is considered "tedious," uses statistics, and does not account for "language universals," it has never quite caught on in mainstream Hebrew linguistics. Perhaps this also has something to do with the fact that the form-to-function approach as a method has been closely linked to text-linguistics or discourse analysis, and hence out of step with more philological approaches. 

However, the rejection of the form-to-function method, or at least its undergirding principles, is now increasingly out of step with new directions in mainstream linguistics. First, the assumption of language universals is by no means a settled debate in linguistics (Haspelmath 2007, Evans and Levinson 2009). Linguists are beginning to recogize that the sheer diversity in linguistic forms in languages simply precludes the presence of default, pre-established units. The appearance of this new perspective has coincided with the rise of cognitive linguistics as a challenger to traditional generative theories (Haspelmath 2007: 121). The cognitive perspective has likewise emphasized language as a cognitively, and culturally unique experience (cf. van Hecke 2011: 288-291 and the discussion with respect to James Barr). Second, English corpus linguistics have, for some time now, shown that native speakers' own intuition of linguistic mechanisms often does not match reality (Sampson 2014; Schütze 2016/1996; Geeraerts 2010; Gries and Divjak 2010). Introspection ultimately is a poor tool of linguistic analysis, because an individual is unable to anticipate all of the various, often surprising, constructions in their own language (Gries and Divjak 2010). In addition, a number of environmental factors affect grammaticality judgments (Schütze 2016/1996). If intution is an unreliable tool for native linguistic evaluation, how much more so for a language as culturally and temporally distant as Biblical Hebrew? Third, the assumption by Cook (especially) that semantics and statistics are incompatible is completely unwarranted. Research in the field of computational linguistics regularly makes use of distributional data and statistics to analyze differences and similarities in word and text meanings (Clark 2015). Anyone can anecdotally test this by picking up their smartphone and asking their digital assistant a question; to automate such tasks requires a combination of statistics and semantics. Systems like Wordnet or Framenet (Fellbaum 1998; [Framenet](https://framenet.icsi.berkeley.edu)) are used to model and store semantic data about word concepts. Computational semantics makes use of formal distributions such as collocation patterns (Xiao 2015), lexico-syntactic relations (e.g. automatically derived hyponymy, Hearst 1992; Snow et al. 2005), vector spaces (Clark 2015; and this present study); and collostructions (Stefanowitsch and Gries 2003; Gries and Stefanowitsch 2004) to automatically derive knowledge about word meanings in language. Finally, another assertion by Cook, about the assumption of correlation between a statistic and a function (Cook 2004) is not an argument against statistics. It is an argument against bad statistics. Of course correlation does not mean causation. Rather, correlation is a tool for discovering causation. Indeed, all data must be interpreted. But the question addressed by form-to-function methodology is not simply *interpretation* of data, rather it is focused on both the gathering of data, and the use of explicit criteria for interpreting it. This distinction is missing from Cook and others' rejection of form-to-function methodology.

The branch of cognitive linguistics which makes use of a form-to-function philosophy has taken a different moniker: empirical cognitive linguistics (Geeraerts 2010; Gries and Divjak 2010; Levshina and Heylen 2014). Like the Scheider school of form-to-function methodology, empirical cognitive linguistics seeks to utilize explicit, corpus-driven data rather than introspection for its conclusions. This likewise employs distributional statistics. This present study likewise adopts the term "empirical" with respect to the question of the Hebrew verb's semantic categorization.

*[to be continued; bibliography to follow]*   

### Data
The data used for the analysis is the [ETCBC](http://www.etcbc.nl)'s [BHSA](https://github.com/ETCBC/bhsa) in [Text-Fabric representation](https://github.com/Dans-labs/text-fabric/wiki). 

