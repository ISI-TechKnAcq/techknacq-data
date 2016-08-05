# TechKnAcq Concept Dependency Data
Release 1, 2016-08-08

This is data to accompany this publication:
> Jonathan Gordon, Linhong Zhu, Aram Galstyan, Prem Natarajan, and Gully
> Burns. 2016. Modeling Concept Dependencies in a Scientific Corpus.
> In Proceedings of ACL.

The files are:

- *Automatic dependency scores.csv*: These are the weights for concept
  dependency edges predicted by the methods described in the paper. The more
  positive a score is, the stronger the prediction that topic T1 would help a
  learner to understand T2?

- *Human judgments.csv*: These are the full judgments collected about the
  scientific topics from 8 academics with different levels of expertise in
  the domain (NLP). For a pair of topics T1 and T2, we report the judgments
  for how coherent T1 is, how coherent T2 is, how similar T1 and T2 are to
  each other, how much T1 would help you understand T2, and how much T2 would
  help you to understand T1. Responses are on a three-point scale:  
  1 Not at all.  
  2 Somewhat.  
  3 Very much.

- *Topic word counts.txt.bz2*: These are the (bzip2-compressed) counts for
  the bigrams associated with each topic, as produced by Mallet.

- *Topic model names.csv*: The human-generated names for each of the topics.
  Topics that didn't have a clear interpretation are named 'Miscellany' with a
  unique numeric identifier.

Inputs not included in this release are:
- The ACL citation network. We use the 2013 release of the ACL Anthology
  Network, which is available from http://clair.eecs.umich.edu/aan
- The ACL Anthology text corpus the topic model was learned from. We don't
  have the permissions to publicly distribute this at present, but it is
  available by request.


## Acknowledgments

This research is based upon work supported in part by the Office of the
Director of National Intelligence (ODNI), Intelligence Advanced Research
Projects Activity (IARPA), via Air Force Research Laboratory (AFRL). The views
and conclusions contained herein are those of the authors and should not be
interpreted as necessarily representing the official policies or endorsements,
either expressed or implied, of ODNI, IARPA, AFRL, or the U.S. Government. The
U.S. Government is authorized to reproduce and distribute reprints for
Governmental purposes notwithstanding any copyright annotation thereon.
