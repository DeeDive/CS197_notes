A warm up exercise: Write your 3 best ideas for a follow up research paper you would publish to CLIP. After the lecture, come back to this exercise, and see how your answers have changed.



CLIP limitations：

+ cannot do generative prediction (classification, interpretation) like image captioning
+ lack of few-show tuning ability (when tuned with few samples, the performance is worse than the human)
+ need to query validation sets for guiding the development.

My ideas?
+ keep CLIP, add RPN-like pathology-proposal network?  (or bruce force search?)
+ regarding limitation 2, is it the relation similar to today's finetuning vs. in-context learning?
+ what is the hyperparameter's true meaning? can we infer the hyperparameter from the label-free data?
+ add human feedback? (from current point of view)

# Analysis on the CheXzero paper 
## identify research gaps

+ Identify gaps in the research question
+ Identify gaps in the experimental setups
+ Identify gaps through expressed limitations, implicit and explicit
### central research question
medical-image-intepretations tasks; reduce the experts's labor needed for data anatation.

### research hypothesis

(a “precise, testable statement of what the researcher(s) predict will be the outcome of the study.”) 
Not every hypothesis may be explicitly stated – you may have to infer this from the experiments that were performed.

No need for supervised class label; instead the text in report data is useful, and hence CLIP could be used for pretraining.

### identifying research gaps
Now, you can look at gaps between the overall research question and the research hypotheses – what are hypotheses that have not been tested?


## Generating Ideas For Building on a Research Paper

+ Change the task of interest
+ Change the evaluation strategy
+ change the proposed method (like most deep learning method papers)
  + dataset format (another section of the radiology report)
  + pretraining/training strategies (what pretrained model to use; training objective (MLM)
  + deep learning architecture (vision-language pretraining)
  + problem formulation (e.g. take multiple images as input)


## Iterating on your research ideas
+ search for whether your idea has been tried
+ read important related works and follow-up works
+ Get feedback from experts
  
