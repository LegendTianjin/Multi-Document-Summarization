This repositary includes summaries generated from several state-of-the-art summarization systems 
and popular baseline systems on DUC 2004 task 2.

Directory basicsums include summaries from baseline systems
  - FreqSum
  - TsSum
  - Centroid
  - LexRank
  - GreedyKL
 
Directory SOAsums include summaries from state-of-the-art systems:
  - CLASSY04
  - CLASSY11
  - DPP
  - ICSISumm
  - OCCAMS_V
  - RegSum
  - Submodular


Detailed description of the systems can be found in our work:
Kai Hong, John M. Conroy, Benoit Favre, Alex Kulesza, Hui Lin, and Ani Nenkova 
A Repositary of State of the Art and Competitive Baseline Summaries for Generic News Summarization
Proceedings of LREC, 2014.

=======================================

Recommended ROUGE settings which provides the best agreement with manual evaluations (on TAC):
Compute ROUGE-2 recall (main), along with ROUGE-1 recall and ROUGE-4 recall. Include stopwords, with stemming, truncate to 100 words:
-n 4 -m -a -l 100 -x -c 95 -r 1000 -f A -p 0.5 -t 0

According to 
Karolina Owczarzak, John M. Conroy, John M., Hoa Trang Dang, and Ani Nenkova
An Assessment of the Accuracy of Automatic Evaluation in Summarization
In Proceedings of Workshop on Evaluation Metrics and System Comparison for Automatic Summarization, 2012

