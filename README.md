

<body>

  <h1>Automated Realistic Story Generation</h1>

  <p>This repository showcases the generation of realistic stories and evaluates the generated stories using various metrics.</p>

  <h2>Overview</h2>

  <p>This project utilizes the capabilities of GPT-2, GPT-2 Medium, Mistral-7B-v0.1, Starling-LM-7B-alpha, Mistral-7B-Instruct-v0.2, TinyLlama-1.1B-Chat-v1.0, and OpenChat-3.5-1210 powerful language generation models from the Hugging Face Transformers library, to autonomously generate realistic stories. The primary goal is to craft captivating narratives that showcase realism, coherence, and natural language fluency.</p>

  <h2>Dataset</h2>

  <p>The dataset used for this project is sourced from the <a href="https://huggingface.co/datasets/AtlasUnified/atlas-storyteller?row=42">Atlas Storyteller Dataset</a> available on the Hugging Face Datasets Hub. This dataset contains a collection of stories suitable for training Large Language Models.</p>

  <h2>Models Used</h2>
<ul>
  <li><a href="https://huggingface.co/docs/transformers/model_doc/gpt2">GPT-2</a></li>
  <li><a href="https://huggingface.co/gpt2-medium">GPT-2 Medium</a></li>
  <li><a href="https://huggingface.co/meta-llama/Llama-2-7b-chat-hf">Llama-2-7b-chat-hf</a></li>
  <li><a href="https://huggingface.co/mistralai/Mistral-7B-v0.1">Mistral-7B-v0.1</a></li>
  <li><a href="https://huggingface.co/berkeley-nest/Starling-LM-7B-alpha">Starling-LM-7B-alpha</a></li>
  <li><a href="https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2">Mistral-7B-Instruct-v0.2</a></li>
  <li><a href="https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0">TinyLlama-1.1B-Chat-v1.0</a></li>
  <li><a href="https://huggingface.co/openchat/openchat-3.5-1210">openchat-3.5-1210</a></li>
</ul>
These models serve as the core for generating stories in this project. They have been fine-tuned on the provided dataset to facilitate the creation of realistic and engaging narratives.


  <h2>Evaluation Metrics</h2>

  <p>The following evaluation metrics have been calculated to assess the quality of the generated stories:</p>
  <ul>
    <li>BLEU Score</li>
    <li>METEOR Score</li>
     <li>BERT Score</li>
  </ul>

  <p>These metrics help quantify the accuracy, fluency, and similarity of the generated stories compared to the reference or ground truth stories.</p>

</body>


