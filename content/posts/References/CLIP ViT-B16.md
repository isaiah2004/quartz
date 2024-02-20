CLIP (_Contrastive Language–Image Pre-training_) builds on a large body of work on zero-shot transfer, natural language supervision, and multimodal learning. The idea of zero-data learning dates back over a decade[8](https://openai.com/research/clip#fn-8) but until recently was mostly studied in computer vision as a way of generalizing to unseen object categories.[9](https://openai.com/research/clip#fn-9),[10](https://openai.com/research/clip#fn-10) A critical insight was to leverage natural language as a flexible prediction space to enable generalization and transfer. In 2013, Richer Socher and co-authors at Stanford[11](https://openai.com/research/clip#fn-11) developed a proof of concept by training a model on CIFAR-10 to make predictions in a word vector embedding space and showed this model could predict two unseen classes. The same year DeVISE[12](https://openai.com/research/clip#fn-12) scaled this approach and demonstrated that it was possible to fine-tune an ImageNet model so that it could generalize to correctly predicting objects outside the original 1000 training set.





[CLIP: Connecting text and images (openai.com)](https://openai.com/research/clip) 

hugging face:
[openai/clip-vit-base-patch16 · Hugging Face](https://huggingface.co/openai/clip-vit-base-patch16)

