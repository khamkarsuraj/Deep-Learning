CPSC 8430 Deep Learning Homework 2 : Video Caption Generation
============= 

---------------
1. Clone this repository.
2. The testing_main.ipynb is testing result module. The output with BLEU score is also provided.
3. The trainig_main.ipynb is notebook which has all code executed with epochs ran.
4. Alternate to that, just execute hw2_seq2seq.sh file with appropriate testing data to see the BLEU score.

  * Batch Size = 32 (Trained with 126, 32, 10 where Batch size = 10 was generating lowest loss).
  * Epochs = 10
  * Learning rate = 0.0001
  * Training Sample Size = 1450
  * Video features dimension = 4096
  * Video frame dimension = 80

Result:
---------------
Best bleu score is 0.68, for the testdata present in "/testing_data"

Report: 
---------------
https://github.com/khamkarsuraj/Deep-Learning/blob/main/Homework_2/Report.pdf


Thanks,
Suraj Khamkar
