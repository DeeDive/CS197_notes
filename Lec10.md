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
