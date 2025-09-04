# NWP (next word prediction)
<P>An AI project on next word prediction using transformer based models. Fine tuned meta llama 3.2 1B using dataset consisting of indian legal document from hugging face. </P>
Leveraging the ninadn/indian-legal dataset from Hugging Face and employing a resource-efficient training methodology utilizing 4-bit quantization (QLoRA), the model was fine-tuned for 10 epochs on a Google Colab T4 GPU. 
The experiment achieved a significant reduction in training loss, from an initial value of 3.0293 to a final value of 1.0447, representing a 65.3% improvement. 
Here in this project I have used the model for 4 next token prediction and 10 next token prediction and have found successful results.
