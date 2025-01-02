# ML Papers Explained

Explanations to key concepts in ML

## Language Models

| Paper | Date | Description |
|---|---|---|
| [Transformer](https://ritvik19.medium.com/papers-explained-01-transformer-474bb60a33f7) | June 2017 | An Encoder Decoder model, that introduced multihead attention mechanism for language translation task. |
| [Elmo](https://ritvik19.medium.com/papers-explained-33-elmo-76362a43e4) | February 2018 | Deep contextualized word representations that captures both intricate aspects of word usage and contextual variations across language contexts. |
| [Marian MT](https://ritvik19.medium.com/papers-explained-150-marianmt-1b44479b0fd9) | April 2018 | A Neural Machine Translation framework written entirely in C++ with minimal dependencies, designed for high training and translation speed. |
| [GPT](https://ritvik19.medium.com/papers-explained-43-gpt-30b6f1e6d226) | June 2018 | A Decoder only transformer which is autoregressively pretrained and then finetuned for specific downstream tasks using task-aware input transformations. |
| [BERT](https://ritvik19.medium.com/papers-explained-02-bert-31e59abc0615) | October 2018 | Introduced pre-training for Encoder Transformers. Uses unified architecture across different tasks. |
| [Transformer XL](https://ritvik19.medium.com/papers-explained-34-transformerxl-2e407e780e8) | January 2019 | Extends the original Transformer model to handle longer sequences of text by introducing recurrence into the self-attention mechanism. |
| [XLM](https://ritvik19.medium.com/papers-explained-158-xlm-42a175e93caf) | January 2019 | Proposes two methods to learn cross-lingual language models (XLMs): one unsupervised that only relies on monolingual data, and one supervised that leverages parallel data with a new cross-lingual language model objective.  |
| [GPT 2](https://ritvik19.medium.com/papers-explained-65-gpt-2-98d0a642e520) | February 2019 | Demonstrates that language models begin to learn various language processing tasks without any explicit supervision. | 
| [Sparse Transformer](https://ritvik19.medium.com/papers-explained-122-sparse-transformer-906a0be1e4e7) | April 2019 | Introduced sparse factorizations of the attention matrix to reduce the time and memory consumption to O(n√ n) in terms of sequence lengths. |
| [UniLM](https://ritvik19.medium.com/papers-explained-72-unilm-672f0ecc6a4a) | May 2019 | Utilizes a shared Transformer network and specific self-attention masks to excel in both language understanding and generation tasks. |
| [XLNet](https://ritvik19.medium.com/papers-explained-35-xlnet-ea0c3af96d49) | June 2019 | Extension of the Transformer-XL, pre-trained using a new method that combines ideas from AR and AE objectives. |
| [RoBERTa](https://ritvik19.medium.com/papers-explained-03-roberta-81db014e35b9) | July 2019 | Built upon BERT, by carefully optimizing hyperparameters and training data size to improve performance on various language tasks . |
| [Sentence BERT](https://ritvik19.medium.com/papers-explained-04-sentence-bert-5159b8e07f21) | August 2019 | A modification of BERT that uses siamese and triplet network structures to derive sentence embeddings that can be compared using cosine-similarity. |
| [CTRL](https://ritvik19.medium.com/papers-explained-153-ctrl-146fcd18a566) | September 2019 | A 1.63B language model that can generate text conditioned on control codes that govern style, content, and task-specific behavior, allowing for more explicit control over text generation. |
| [Tiny BERT](https://ritvik19.medium.com/papers-explained-05-tiny-bert-5e36fe0ee173) | September 2019 | Uses attention transfer, and task specific distillation for distilling BERT. |
| [ALBERT](https://ritvik19.medium.com/papers-explained-07-albert-46a2a0563693) | September 2019 | Presents certain parameter reduction techniques to lower memory consumption and increase the training speed of BERT. |
| [Distil BERT](https://ritvik19.medium.com/papers-explained-06-distil-bert-6f138849f871) | October 2019 | Distills BERT on very large batches leveraging gradient accumulation, using dynamic masking and without the next sentence prediction objective. |
| [Distil RoBERTa](https://ritvik19.medium.com/papers-explained-06-distil-bert-6f138849f871#a260) | October 2019 | Distillation of RoBERTa, using the same techniques as Distil BERT. |
| [T5](https://ritvik19.medium.com/papers-explained-44-t5-9d974a3b7957) | October 2019 | A unified encoder-decoder framework that converts all text-based language problems into a text-to-text format. |
| [BART](https://ritvik19.medium.com/papers-explained-09-bart-7f56138175bd) | October 2019 | An Encoder-Decoder pretrained to reconstruct the original text from corrupted versions of it. |
| [XLM-Roberta](https://ritvik19.medium.com/papers-explained-159-xlm-roberta-2da91fc24059) | November 2019 | A multilingual masked language model pre-trained on text in 100 languages, shows that pretraining multilingual language models at scale leads to significant performance gains for a wide range of crosslingual transfer tasks. |
| [XLM-Roberta](https://ritvik19.medium.com/papers-explained-159-xlm-roberta-2da91fc24059) | November 2019 | A multilingual masked language model pre-trained on text in 100 languages, shows that pretraining multilingual language models at scale leads to significant performance gains for a wide range of crosslingual transfer tasks. |
| [Pegasus](https://ritvik19.medium.com/papers-explained-162-pegasus-1cb16f572553) | December 2019 | A self-supervised pre-training objective for abstractive text summarization, proposes removing/masking important sentences from an input document and generating them together as one output sequence. |
| [Reformer](https://ritvik19.medium.com/papers-explained-165-reformer-4445ad305191) | January 2020 | Improves the efficiency of Transformers by replacing dot-product attention with locality-sensitive hashing (O(Llog L) complexity), using reversible residual layers to store activations only once, and splitting feed-forward layer activations into chunks, allowing it to perform on par with Transformer models while being much more memory-efficient and faster on long sequences. |
| [mBART](https://ritvik19.medium.com/papers-explained-169-mbart-98432ef6fec) | January 2020 | A multilingual sequence-to-sequence denoising auto-encoder that pre-trains a complete autoregressive model on large-scale monolingual corpora across many languages using the BART objective, achieving significant performance gains in machine translation tasks. |
| [UniLMv2](https://ritvik19.medium.com/papers-explained-unilmv2-5a044ca7c525) | February 2020 | Utilizes a pseudo-masked language model (PMLM) for both autoencoding and partially autoregressive language modeling tasks,significantly advancing the capabilities of language models in diverse NLP tasks. |
| [ELECTRA](https://ritvik19.medium.com/papers-explained-173-electra-501c175ae9d8) | March 2020 | Proposes a sample-efficient pre-training task called replaced token detection, which corrupts input by replacing some tokens with plausible alternatives and trains a discriminative model to predict whether each token was replaced or no. |
| [FastBERT](https://ritvik19.medium.com/papers-explained-37-fastbert-5bd246c1b432) | April 2020 | A speed-tunable encoder with adaptive inference time having branches at each transformer output to enable early outputs. |
| [MobileBERT](https://ritvik19.medium.com/papers-explained-36-mobilebert-933abbd5aaf1) | April 2020 | Compressed and faster version of the BERT, featuring bottleneck structures, optimized attention mechanisms, and knowledge transfer. |
| [Longformer](https://ritvik19.medium.com/papers-explained-38-longformer-9a08416c532e) | April 2020 | Introduces a linearly scalable attention mechanism, allowing handling texts of exteded length. |
| [GPT 3](https://ritvik19.medium.com/papers-explained-66-gpt-3-352f5a1b397) | May 2020 | Demonstrates that scaling up language models greatly improves task-agnostic, few-shot performance. |
| [DeBERTa](https://ritvik19.medium.com/papers-explained-08-deberta-a808d9b2c52d) | June 2020 | Enhances BERT and RoBERTa through disentangled attention mechanisms, an enhanced mask decoder, and virtual adversarial training. |
| [DeBERTa v2](https://ritvik19.medium.com/papers-explained-08-deberta-a808d9b2c52d#f5e1) | June 2020 | Enhanced version of the DeBERTa featuring a new vocabulary, nGiE integration, optimized attention mechanisms, additional model sizes, and improved tokenization. |
| [T5 v1.1](https://ritvik19.medium.com/papers-explained-44-t5-9d974a3b7957#773b) | July 2020 | An enhanced version of the original T5 model, featuring improvements such as GEGLU activation, no dropout in pre-training, exclusive pre-training on C4, no parameter sharing between embedding and classifier layers. |
| [mT5](https://ritvik19.medium.com/papers-explained-113-mt5-c61e03bc9218) | October 2020 | A multilingual variant of T5 based on T5 v1.1, pre-trained on a new Common Crawl-based dataset covering 101 languages (mC4). |
| [Codex](https://ritvik19.medium.com/papers-explained-45-codex-caca940feb31) | July 2021 | A GPT language model finetuned on publicly available code from GitHub. |
| [FLAN](https://ritvik19.medium.com/papers-explained-46-flan-1c5e0d5db7c9) | September 2021 | An instruction-tuned language model developed through finetuning on various NLP datasets described by natural language instructions. |
| [T0](https://ritvik19.medium.com/papers-explained-74-t0-643a53079fe) | October 2021 | A fine tuned encoder-decoder model on a multitask mixture covering a wide variety of tasks, attaining strong zero-shot performance on several standard datasets. |
| [DeBERTa V3](https://ritvik19.medium.com/papers-explained-182-deberta-v3-65347208ce03) | November 2021 | Enhances the DeBERTa architecture by introducing replaced token detection (RTD) instead of mask language modeling (MLM), along with a novel gradient-disentangled embedding sharing method, exhibiting superior performance across various natural language understanding tasks. |
| [WebGPT](https://ritvik19.medium.com/papers-explained-123-webgpt-5bb0dd646b32) | December 2021 | A fine-tuned GPT-3 model utilizing text-based web browsing, trained via imitation learning and human feedback, enhancing its ability to answer long-form questions with factual accuracy. |
| [Gopher](https://ritvik19.medium.com/papers-explained-47-gopher-2e71bbef9e87) | December 2021 | Provides a comprehensive analysis of the performance of various Transformer models across different scales upto 280B on 152 tasks. |
| [LaMDA](https://ritvik19.medium.com/papers-explained-76-lamda-a580ebba1ca2) | January 2022 | Transformer based models specialized for dialog, which are pre-trained on public dialog data and web text. |
| [BERTopic](https://ritvik19.medium.com/papers-explained-193-bertopic-f9aec10cd5a6) | March 20222 | Utilizes Sentence-BERT for document embeddings, UMAP, HDBSCAN (soft-clustering), and an adjusted class-based TF-IDF, addressing multiple topics per document and dynamic topics' linear evolution. |
| [Instruct GPT](https://ritvik19.medium.com/papers-explained-48-instructgpt-e9bcd51f03ec) | March 2022 | Fine-tuned GPT using supervised learning (instruction tuning) and reinforcement learning from human feedback to align with user intent. |
| [CodeGen](https://ritvik19.medium.com/papers-explained-125-codegen-a6bae5c1f7b5) | March 2022 | An LLM trained for program synthesis using input-output examples and natural language descriptions. |
| [Chinchilla](https://ritvik19.medium.com/papers-explained-49-chinchilla-a7ad826d945e) | March 2022 | Investigated the optimal model size and number of tokens for training a transformer LLM within a given compute budget (Scaling Laws). |
| [PaLM](https://ritvik19.medium.com/papers-explained-50-palm-480e72fa3fd5) | April 2022 | A 540-B parameter, densely activated, Transformer, trained using Pathways, (ML system that enables highly efficient training across multiple TPU Pods). |
| [GPT-NeoX-20B](https://ritvik19.medium.com/papers-explained-78-gpt-neox-20b-fe39b6d5aa5b) | April 2022 | An autoregressive LLM trained on the Pile, and the largest dense model that had publicly available weights at the time of submission. |
| [OPT](https://ritvik19.medium.com/papers-explained-51-opt-dacd9406e2bd) | May 2022 | A suite of decoder-only pre-trained transformers with parameter ranges from 125M to 175B. OPT-175B being comparable to GPT-3. |
| [Flan T5, Flan PaLM](https://ritvik19.medium.com/papers-explained-75-flan-t5-flan-palm-caf168b6f76) | October 2022 | Explores instruction fine tuning with a particular focus on scaling the number of tasks, scaling the model size, and fine tuning on chain-of-thought data. |
| [BLOOM](https://ritvik19.medium.com/papers-explained-52-bloom-9654c56cd2) | November 2022 | A 176B-parameter open-access decoder-only transformer, collaboratively developed by hundreds of researchers, aiming to democratize LLM technology. |
| [BLOOMZ, mT0](https://ritvik19.medium.com/papers-explained-99-bloomz-mt0-8932577dcd1d) | November 2022 | Applies Multitask prompted fine tuning to the pretrained multilingual models on English tasks with English prompts to attain task generalization to non-English languages that appear only in the pretraining corpus. |
| [Galactica](https://ritvik19.medium.com/papers-explained-53-galactica-1308dbd318dc) | November 2022 | An LLM trained on scientific data thus specializing in scientific knowledge. |
| [ChatGPT](https://ritvik19.medium.com/papers-explained-54-chatgpt-78387333268f) | November 2022 | An interactive model designed to engage in conversations, built on top of GPT 3.5. |
| [Self Instruct](https://ritvik19.medium.com/papers-explained-112-self-instruct-5c192580103a) | December 2022 | A framework for improving the instruction-following capabilities of pretrained language models by bootstrapping off their own generations. |
| [LLaMA](https://ritvik19.medium.com/papers-explained-55-llama-c4f302809d6b) | February 2023 | A collection of foundation LLMs by Meta ranging from 7B to 65B parameters, trained using publicly available datasets exclusively. |
| [Toolformer](https://ritvik19.medium.com/papers-explained-140-toolformer-d21d496b6812) | February 2023 | An LLM trained to decide which APIs to call, when to call them, what arguments to pass, and how to best incorporate the results into future token prediction. |
| [Alpaca](https://ritvik19.medium.com/papers-explained-56-alpaca-933c4d9855e5) | March 2023 | A fine-tuned LLaMA 7B model, trained on instruction-following demonstrations generated in the style of self-instruct using text-davinci-003. |
| [GPT 4](https://ritvik19.medium.com/papers-explained-67-gpt-4-fc77069b613e) | March 2023 | A multimodal transformer model pre-trained to predict the next token in a document, which can accept image and text inputs and produce text outputs. |
| [Vicuna](https://ritvik19.medium.com/papers-explained-101-vicuna-daed99725c7e) | March 2023 | A 13B LLaMA chatbot fine tuned on user-shared conversations collected from ShareGPT, capable of generating more detailed and well-structured answers compared to Alpaca. |
| [BloombergGPT](https://ritvik19.medium.com/papers-explained-120-bloomberggpt-4bedd52ef54b) | March 2023 | A 50B language model train on general purpose and domain specific data to support a wide range of tasks within the financial industry. |
| [Pythia](https://ritvik19.medium.com/papers-explained-121-pythia-708284c32964) | April 2023 | A suite of 16 LLMs all trained on public data seen in the exact same order and ranging in size from 70M to 12B parameters. |
| [WizardLM](https://ritvik19.medium.com/papers-explained-127-wizardlm-65099705dfa3) | April 2023 | Introduces Evol-Instruct, a method to generate large amounts of instruction data with varying levels of complexity using LLM instead of humans to fine tune a Llama model  |
| [CodeGen2](https://ritvik19.medium.com/papers-explained-codegen2-d2690d7eb831) | May 2023 | Proposes an approach to make the training of LLMs for program synthesis more efficient by unifying key components of model architectures, learning methods, infill sampling, and data distributions |
| [PaLM 2](https://ritvik19.medium.com/papers-explained-58-palm-2-1a9a23f20d6c) | May 2023 | Successor of PALM, trained on a mixture of different pre-training objectives in order to understand different aspects of language. |
| [LIMA](https://ritvik19.medium.com/papers-explained-57-lima-f9401a5760c3) | May 2023 | A LLaMa model fine-tuned on only 1,000 carefully curated prompts and responses, without any reinforcement learning or human preference modeling. |
| [Gorilla](https://ritvik19.medium.com/papers-explained-139-gorilla-79f4730913e9) | May 2023 | A retrieve-aware finetuned LLaMA-7B model, specifically for API calls. |
| [Orca](https://ritvik19.medium.com/papers-explained-160-orca-928eff06e7f9) | June 2023 | Presents a novel approach that addresses the limitations of instruction tuning by leveraging richer imitation signals, scaling tasks and instructions, and utilizing a teacher assistant to help with progressive learning. |
| [Falcon](https://ritvik19.medium.com/papers-explained-59-falcon-26831087247f) | June 2023 | An Open Source LLM trained on properly filtered and deduplicated web data alone. |
| [Phi-1](https://ritvik19.medium.com/papers-explained-114-phi-1-14a8dcc77ce5) | June 2023 | An LLM for code, trained using a textbook quality data from the web and synthetically generated textbooks and exercises with GPT-3.5. |
| [WizardCoder](https://ritvik19.medium.com/papers-explained-wizardcoder-a12ecb5b93b6) | June 2023 | Enhances the performance of the open-source Code LLM, StarCoder, through the application of Code Evol-Instruct. |
| [LLaMA 2](https://ritvik19.medium.com/papers-explained-60-llama-v2-3e415c5b9b17) | July 2023 | Successor of LLaMA. LLaMA 2-Chat is optimized for dialogue use cases. |
| [Tool LLM](https://ritvik19.medium.com/papers-explained-141-tool-llm-856f99e79f55) | July 2023 | A LLaMA model finetuned on an instruction-tuning dataset for tool use, automatically created using ChatGPT. |
| [Humpback](https://ritvik19.medium.com/papers-explained-61-humpback-46992374fc34) | August 2023 | LLaMA finetuned using Instrustion backtranslation. |
| [Code LLaMA](https://ritvik19.medium.com/papers-explained-62-code-llama-ee266bfa495f) | August 2023 | LLaMA 2 based LLM for code. |
| [WizardMath](https://ritvik19.medium.com/papers-explained-129-wizardmath-265e6e784341) | August 2023 | Proposes Reinforcement Learning from Evol-Instruct Feedback (RLEIF) method, applied to Llama-2 to enhance the mathematical reasoning abilities. |
| [LLaMA 2 Long](https://ritvik19.medium.com/papers-explained-63-llama-2-long-84d33c26d14a) | September 2023 | A series of long context LLMs s that support effective context windows of up to 32,768 tokens. |
| [Phi-1.5](https://ritvik19.medium.com/papers-explained-phi-1-5-2857e56dbd2a) | September 2023 | Follows the phi-1 approach, focusing this time on common sense reasoning in natural language. |
| [MAmmoTH](https://ritvik19.medium.com/papers-explained-230-mammoth-06189e929910) | September 2023 | A series of LLMs specifically designed for general math problem-solving, trained on MathInstruct, a dataset compiled from 13 math datasets with intermediate rationales that combines chain-of-thought and program-of-thought approaches to accommodate different thought processes for various math problems. |
| [Mistral 7B](https://ritvik19.medium.com/papers-explained-mistral-7b-b9632dedf580) | October 2023 | Leverages grouped-query attention for faster inference, coupled with sliding window attention to effectively handle sequences of arbitrary length with a reduced inference cost. |
| [Llemma](https://ritvik19.medium.com/papers-explained-69-llemma-0a17287e890a) | October 2023 | An LLM for mathematics, formed by continued pretraining of Code Llama on a mixture of scientific papers, web data containing mathematics, and mathematical code. |
| [CodeFusion](https://ritvik19.medium.com/papers-explained-70-codefusion-fee6aba0149a) | October 2023 | A diffusion code generation model that iteratively refines entire programs based on encoded natural language, overcoming the limitation of auto-regressive models in code generation by allowing reconsideration of earlier tokens. |
| [Zephyr 7B](https://ritvik19.medium.com/papers-explained-71-zephyr-7ec068e2f20b) | October 2023 | Utilizes dDPO and AI Feedback (AIF) preference data to achieve superior intent alignment in chat-based language modeling. |
| [Grok 1](https://ritvik19.medium.com/papers-explained-186-grok-0d9f1aef69be) | November 2023 | A 314B Mixture-of-Experts model,  modeled after the Hitchhiker's Guide to the Galaxy, designed to be witty. |
| [Orca 2](https://ritvik19.medium.com/papers-explained-161-orca-2-b6ffbccd1eef) | November 2023 | Introduces Cautious Reasoning for training smaller models to select the most effective solution strategy based on the problem at hand, by crafting data with task-specific system instruction(s) corresponding to the chosen strategy in order to obtain teacher responses for each task and replacing the student’s system instruction with a generic one vacated of details of how to approach the task. |
| [Phi-2](https://ritvik19.medium.com/papers-explained-phi-1-5-2857e56dbd2a#8230) | December 2023 | A 2.7B model, developed to explore whether emergent abilities achieved by large-scale language models can also be achieved at a smaller scale using strategic choices for training, such as data selection. |
| [TinyLlama](https://ritvik19.medium.com/papers-explained-93-tinyllama-6ef140170da9) | January 2024 | A  1.1B language model built upon the architecture and tokenizer of Llama 2, pre-trained on around 1 trillion tokens for approximately 3 epochs, leveraging FlashAttention and Grouped Query Attention, to achieve better computational efficiency. |
| [Mixtral 8x7B](https://ritvik19.medium.com/papers-explained-95-mixtral-8x7b-9e9f40ebb745) | January 2024 | A Sparse Mixture of Experts language model trained with multilingual data using a context size of 32k tokens. |
| [H2O Danube 1.8B](https://ritvik19.medium.com/papers-explained-111-h2o-danube-1-8b-b790c073d257) | January 2024 | A language model trained on 1T tokens following the core principles of LLama 2 and Mistral, leveraging and refining various techniques for pre-training large language models. |
| [OLMo](https://ritvik19.medium.com/papers-explained-98-olmo-fdc358326f9b) | February 2024 | A state-of-the-art, truly open language model and framework that includes training data, code, and tools for building, studying, and advancing language models. |
| [MobileLLM](https://ritvik19.medium.com/papers-explained-216-mobilellm-2d7fdd5acd86) | February 2024 | Leverages various architectures and attention mechanisms to achieve a strong baseline network, which is then improved upon by introducing an immediate block-wise weight-sharing approach, resulting in a further accuracy boost. |
| [Orca Math](https://ritvik19.medium.com/papers-explained-163-orca-math-ae6a157ce48d) | February 2024 | A fine tuned Mistral-7B that excels at math problems without external tools, utilizing a high-quality synthetic dataset of 200K problems created through multi-agent collaboration and an iterative learning process that involves practicing problem-solving, receiving feedback, and learning from preference pairs incorporating the model's solutions and feedback. |
| [Gemma](https://ritvik19.medium.com/papers-explained-106-gemma-ca2b449321ac) | February 2024 | A family of 2B and 7B, state-of-the-art language models based on Google's Gemini models, offering advancements in language understanding, reasoning, and safety. |
| [Aya 101](https://ritvik19.medium.com/papers-explained-aya-101-d813ba17b83a) | Februray 2024 | A massively multilingual generative language model that follows instructions in 101 languages,trained by finetuning mT5. |
| [Nemotron-4 15B](https://ritvik19.medium.com/papers-explained-206-nemotron-4-15b-7d895fb56134) | February 2024 | A 15B multilingual language model trained on 8T text tokens by Nvidia. |
| [Hawk, Griffin](https://ritvik19.medium.com/papers-explained-131-hawk-griffin-dfc8c77f5dcd) |  February 2024 | Introduces Real Gated Linear Recurrent Unit Layer that forms the core of the new recurrent block, replacing Multi-Query Attention for better efficiency and scalability |
| [WRAP](https://ritvik19.medium.com/papers-explained-118-wrap-e563e009fe56) | March 2024 | Uses an off-the-shelf instruction-tuned model prompted to paraphrase documents on the web in specific styles to jointly pre-train LLMs on real and synthetic rephrases. |
| [Command R](https://ritvik19.medium.com/papers-explained-166-command-r-models-94ba068ebd2b) | March 2024 | An LLM optimized for retrieval-augmented generation and tool use, across multiple languages. |
| [DBRX](https://ritvik19.medium.com/papers-explained-119-dbrx-17c61739983c) | March 2024 | A 132B open, general-purpose fine grained Sparse MoE LLM surpassing GPT-3.5 and competitive with Gemini 1.0 Pro. |
| [Grok 1.5](https://ritvik19.medium.com/papers-explained-186-grok-0d9f1aef69be) | March 2024 | An advancement over grok, capable of long context understanding up to 128k tokens and advanced reasoning. |
| [Command R+](https://ritvik19.medium.com/papers-explained-166-command-r-models-94ba068ebd2b#c2b5) | April 2024 | Successor of Command R+ with improved performance for retrieval-augmented generation and tool use, across multiple languages. |
| [Llama 3](https://ritvik19.medium.com/papers-explained-187a-llama-3-51e2b90f63bb) | April 2024 | A family of 8B and 70B parameter models trained on 15T tokens with a focus on data quality, demonstrating state-of-the-art performance on various benchmarks, improved reasoning capabilities. |
| [Mixtral 8x22B](https://ritvik19.medium.com/papers-explained-95-mixtral-8x7b-9e9f40ebb745#20f3) | April 2024 | A open-weight AI model optimised for performance and efficiency, with capabilities such as fluency in multiple languages, strong mathematics and coding abilities, and precise information recall from large documents. |
| [CodeGemma](https://ritvik19.medium.com/papers-explained-124-codegemma-85faa98af20d) | April 2024 | Open code models based on Gemma models by further training on over 500 billion tokens of primarily code. |
| [RecurrentGemma](https://ritvik19.medium.com/papers-explained-132-recurrentgemma-52732d0f4273) | April 2024 | Based on Griffin, uses a combination of linear recurrences and local attention instead of global attention to model long sequences efficiently. |
| [Rho-1](https://ritvik19.medium.com/papers-explained-132-rho-1-788125e42241) | April 2024 | Introduces Selective Language Modelling that optimizes the loss only on tokens that align with a desired distribution, utilizing a reference model to score and select tokens. |
| [Phi-3](https://ritvik19.medium.com/papers-explained-130-phi-3-0dfc951dc404) | April 2024 | A series of language models trained on heavily filtered web and synthetic data set, achieving performance comparable to much larger models like Mixtral 8x7B and GPT-3.5. |
| [Open ELM](https://ritvik19.medium.com/papers-explained-133-open-elm-864f6b28a6ab) | April 2024 | A fully open language model designed to enhance accuracy while using fewer parameters and pre-training tokens. Utilizes a layer-wise scaling strategy to allocate smaller dimensions in early layers, expanding in later layers. |
| [H2O Danube2 1.8B](https://ritvik19.medium.com/papers-explained-111-h2o-danube-1-8b-b790c073d257#00d8) | April 2024 |  An updated version of the original H2O-Danube model, with improvements including removal of sliding window attention, changes to the tokenizer, and adjustments to the training data, resulting in significant performance enhancements. |
| [MAmmoTH 2](https://ritvik19.medium.com/papers-explained-231-mammoth2-e9c0e6fb9795) | May 2024 | LLMs fine tuned on a dataset curated through the proposed paradigm that efficiently harvest 10M naturally existing instruction data from the pre-training web corpus to enhance LLM reasoning. It involves recalling relevant documents, extracting instruction-response pairs, and refining the extracted pairs using open-source LLMs. |
| [Granite Code Models](https://ritvik19.medium.com/paper-explained-144-granite-code-models-e1a92678739b) | May 2024 | A family of code models ranging from 3B to 34B trained on 3.5-4.5T tokens of code written in 116 programming languages. |
| [Codestral 22B](https://medium.com/dair-ai/papers-explained-mistral-7b-b9632dedf580#057b) | May 2024 | An open-weight model designed for code generation tasks, trained on over 80 programming languages, and licensed under the Mistral AI Non-Production License, allowing developers to use it for research and testing purposes. |
| [Aya 23](https://ritvik19.medium.com/papers-explained-151-aya-23-d01605c3ee80) | May 2024 | A family of multilingual language models supporting 23 languages, designed to balance breadth and depth by allocating more capacity to fewer languages during pre-training. |
| [Gemma 2](https://ritvik19.medium.com/papers-explained-157-gemma-2-f1b75b56b9f2) | June 2024 | Utilizes interleaving local-global attentions and group-query attention, trained with knowledge distillation instead of next token prediction to achieve competitive performance comparable with larger models. |
| [Orca 3 (Agent Instruct)](https://ritvik19.medium.com/papers-explained-164-orca-3-agent-instruct-41340505af36) | June 2024 | A fine tuned Mistral-7B through Generative Teaching via synthetic data generated through the proposed AgentInstruct framework, which generates both the prompts and responses, using only raw data sources like text documents and code files as seeds. |
| [Nemotron-4 340B](https://ritvik19.medium.com/papers-explained-207-nemotron-4-340b-4cfe268439f8) | June 2024 | 340B models, along with a reward model by Nvidia, suitable for generating synthetic data to train smaller language models, with over 98% of the data used in model alignment being synthetically generated. |
| [Mathstral](https://medium.com/dair-ai/papers-explained-mistral-7b-b9632dedf580#0fbe) | July 2024 | a 7B model designed for math reasoning and scientific discovery based on Mistral 7B specializing in STEM subjects. |
| [Mistral Nemo](https://medium.com/dair-ai/papers-explained-mistral-7b-b9632dedf580#37cd) | July 2024 | A 12B Language Model built in collaboration between Mistral and NVIDIA, featuring a context window of 128K, an efficient tokenizer and trained with quantization awareness, enabling FP8 inference without any performance loss. |
| [Smol LM](https://ritvik19.medium.com/papers-explained-176-smol-lm-a166d5f1facc) | July 2024 | A family of small models with 135M, 360M, and 1.7B parameters, utilizes Grouped-Query Attention (GQA), embedding tying, and a context length of 2048 tokens, trained on a new open source high-quality dataset. |
| [Llama 3.1](https://ritvik19.medium.com/papers-explained-187b-llama-3-1-f0fb06898c59) | July 2024 | A family of multilingual language models ranging from 8B to 405B parameters, trained on a massive dataset of 15T tokens and achieving comparable performance to leading models like GPT-4 on various tasks. |
| [Llama 3.1 - Multimodal Experiments](https://ritvik19.medium.com/papers-explained-187c-llama-3-1-multimodal-experiments-a1940dd45575) | July 2024 | Additional experiments of adding multimodal capabilities to Llama3. |
| [Mistral Large 2](https://ritvik19.medium.com/papers-explained-mistral-7b-b9632dedf580#301d) | July 2024 | A 123B model, offers significant improvements in code generation, mathematics, and reasoning capabilities, advanced function calling, a 128k context window, and supports dozens of languages and over 80 coding languages. |
| [Minitron](https://ritvik19.medium.com/papers-explained-208-minitron-e55ea374d9dd) | July 2024 | Prunes an existing Nemotron model and re-trains it with a fraction of the original training data, achieving compression factors of 2-4×, compute cost savings of up to 40×, and improved performance on various language modeling tasks. |
| [H2O Danube 3](https://ritvik19.medium.com/papers-explained-217-h2o-danube-3-917a7b40a79f) | July 2024 | A series of 4B and 500M language models, trained on high-quality Web data in three stages with different data mixes before being fine-tuned for chat version. |
| [LLM Compiler](https://ritvik19.medium.com/papers-explained-223-llm-compiler-15b1ddb9a1b0) | July 2024 | A suite of pre-trained models designed for code optimization tasks, built upon Code Llama, with two sizes (7B and 13B), trained on LLVM-IR and assembly code to optimize compiler intermediate representations, assemble/disassemble, and achieve high accuracy in optimizing code size and disassembling from x86_64 and ARM assembly back into LLVM-IR. |
| [Apple Intelligence Foundation Language Models](https://ritvik19.medium.com/papers-explained-222-apple-intelligence-foundation-language-models-2b8a41371a42) | July 2024 | Two foundation language models, AFM-on-device (a ~3 B parameter model) and AFM-server (a larger server-based model), designed to power Apple Intelligence features efficiently, accurately, and responsibly, with a focus on Responsible AI principles that prioritize user empowerment, representation, design care, and privacy protection. |
| [Hermes 3](https://ritvik19.medium.com/papers-explained-188-hermes-3-67d36cfe07d8) | August 2024 | Neutrally generalist instruct and tool use models, created by fine-tuning Llama 3.1 models with strong reasoning and creative abilities, and are designed to follow prompts neutrally without moral judgment or personal opinions. |
| [Smol LM v0.2](https://ritvik19.medium.com/papers-explained-176-smol-lm-a166d5f1facc#fdb2) | August 2024 | An advancement over SmolLM, better at staying on topic and responding appropriately to standard prompts, such as greetings and questions about their role as AI assistants. |
| [Phi-3.5](https://ritvik19.medium.com/papers-explained-192-phi-3-5-a95429ea26c9) | August 2024 |  A family of models consisting of three variants - MoE (16x3.8B), mini (3.8B), and vision (4.2B) - which are lightweight, multilingual, and trained on synthetic and filtered publicly available documents - with a focus on very high-quality, reasoning dense data. |
| [Minitron Approach in Practice](https://ritvik19.medium.com/papers-explained-209-minitron-approach-in-practice-6b473f67328d) | August 2024 | Applies the minitron approach to Llama 3.1 8B and Mistral-Nemo 12B, additionally applies teacher correction to align with the new data distribution. |
| [OLMoE](https://ritvik19.medium.com/papers-explained-270-olmoe-38832ff4f9bd) | September 2024 | An open source language model based on sparse Mixture-of-Experts architecture with 7B parameters, out of which only 1B parameters are active per input token. Conducted extensive experiments on MoE training, analyzing routing strategies, expert specialization, and the impact of design choices like routing algorithms and expert size. |
| [o1](https://ritvik19.medium.com/papers-explained-211-o1-163fd9c7308e) | September 2024 | A large language model trained with reinforcement learning to think before answering, producing a long internal chain of thought before responding. | 
| [o1-mini](https://ritvik19.medium.com/papers-explained-211-o1-163fd9c7308e#f16a) | September 2024 | A cost-efficient reasoning model, excelling at STEM, especially math and coding ,  nearly matching the performance of OpenAI o1 on evaluation benchmarks. | 
| [Llama 3.1-Nemotron-51B](https://ritvik19.medium.com/papers-explained-209-minitron-approach-in-practice-6b473f67328d#5df9) | September 2024 | Uses knowledge distillation and NAS to optimize various constraints, resulting in a model that achieves 2.2x faster inference compared to the reference model while maintaining nearly the same accuracy, with an irregular block structure that reduces or prunes attention and FFN layers for better utilization of H100 and improved LLMs for inference. |
| [Mistral Small](https://medium.com/dair-ai/papers-explained-mistral-7b-b9632dedf580#5662) | September 2024 | A 22B model with significant improvements in human alignment, reasoning capabilities, and code over the previous model. |
| [Llama 3.2](https://ritvik19.medium.com/papers-explained-187d-llama-3-2-e517fa1f2528) | September 2024 | Small and medium-sized vision LLMs (11B and 90B), and lightweight, text-only models (1B and 3B). |
| [Ministral](https://ritvik19.medium.com/papers-explained-mistral-7b-b9632dedf580#1f34) | October 2024 | 3B and 8B models with support up to 128k context length having a special interleaved sliding-window attention pattern for faster and memory-efficient inference. |
| [Quantized Llama 3](https://ritvik19.medium.com/papers-explained-187e-quantized-llama-3-2-cc6965f61370) | October 2024 | Optimized versions of the Llama, using techniques like Quantization-Aware Training with LoRA Adapters and SpinQuant, to reduce model size and memory usage while maintaining accuracy and performance, enabling deployment on resource-constrained devices like mobile phones. |
| [Nemotron-Mini-Hindi](https://ritvik19.medium.com/papers-explained-252-nemotron-mini-hindi-c7adc3b2f759) | October 2024 | A bilingual language model based on Nemotron-Mini 4B, specifically trained to improve Hindi and English performance using continuous pre-training on 400B real and synthetic tokens. |
| [Smol LM v2](https://ritvik19.medium.com/papers-explained-176-smol-lm-a166d5f1facc#aa17) | November 2024 | A family of language models (135M, 360M, and 1.7B parameters), trained on 2T, 4T, and 11T tokens respectively from datasets including FineWeb-Edu, DCLM, The Stack, and curated math and coding datasets, with instruction-tuned versions created using Smol Talk dataset and DPO using UltraFeedback. |
| [Llama3.3](https://ritvik19.medium.com/papers-explained-187e-quantized-llama-3-2-cc6965f61370#bd2c) | December 2024 | A multilingual, instruction-tuned generative language model with 70B parameters, optimized for dialogue use cases and trained on 15 trillion tokens of public data, incorporating both human-generated and synthetic data for safety and quality control. |
| [Command R 7B](https://ritvik19.medium.com/papers-explained-166-command-r-models-94ba068ebd2b#0836) | December 2024 | The smallest, fastest, and final model in the R series of enterprise-focused LLMs. It offers a context length of 128k and delivers a powerful combination of multilingual support, citation verified retrieval-augmented generation (RAG), reasoning, tool use, and agentic behavior. |
| [Phi-4](https://ritvik19.medium.com/papers-explained-278-phi-4-ea59220f3f88) | December 2024 | A 14B language model prioritizing data quality through a training process incorporating synthetic data for pretraining and midtraining, curated organic data seeds, and innovative post-training techniques like pivotal token search for DPO, resulting in strong performance on reasoning-focused benchmarks, especially in STEM, comparable to much larger models, while also addressing overfitting and data contamination concerns. |
| [ModernBERT](https://ritvik19.medium.com/papers-explained-277-modernbert-59f25989f685) | December 2024 | Modernized encoder-only transformer model trained on 2 trillion tokens with a native 8192 sequence length, incorporating architectural improvements like GeGLU activations, RoPE embeddings, alternating attention, and unpadding, resulting in state-of-the-art performance across diverse classification and retrieval tasks (including code) and superior inference speed and memory efficiency compared to existing encoder models. |

## LLMs For Math

| Paper | Date | Description |
|---|---|---|
| [Wizard Math](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#ecf7) | August 2023 | Proposes Reinforcement Learning from Evol-Instruct Feedback (RLEIF) method, applied to Llama-2 to enhance the mathematical reasoning abilities. |
| [MAmmoTH](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#8cd9) | September 2023 | A series of LLMs specifically designed for general math problem-solving, trained on MathInstruct, a dataset compiled from 13 math datasets with intermediate rationales that combines chain-of-thought and program-of-thought approaches to accommodate different thought processes for various math problems. |
| [MetaMath](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#bd74) | September 2023 | A fine-tuned language model that specializes in mathematical reasoning, achieved by bootstrapping mathematical questions from multiple perspectives without extra knowledge and then fine-tuning an LLaMA-2 model on the resulting dataset |
| [ToRA](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#feb4) | September 2023 | A series of large language models that seamlessly integrate natural language reasoning with external tools to solve complex mathematical problems |
| [Math Coder](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#102e) | October 2023 | The first systematic study that explicitly integrates natural language reasoning, code generation, and feedback from execution results into open-source pre-trained large language models |
| [MuggleMath](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#c53e) | October 2023 | GSM8K and MATH datasets are augmented using query augmentation and response augmentation to fine tune Llama 2 models |
| [Llemma](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#1b38) | October 2023 | An LLM for mathematics, formed by continued pretraining of Code Llama on a mixture of scientific papers, web data containing mathematics, and mathematical code. |
| [MuMath](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#25c2) | December 2023 | A multi-perspective augmentation dataset for mathematics that combines strengths from tool-free methods, broadening the scope of augmentation techniques to enhance mathematical reasoning capabilities. |
| [MMIQC](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#3a88) | January 2024 | Curates a data set by sampling Meta Math, Iterative Question Composition, Utilizing Stack Exchange, Augmenting Similar Problems, Answer Augmentation and Question Bootstrapping to finetune Mistral, Llemma, DeepSeek and Qwen. |
| [DeepSeek Math](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#7760) | February 2024 | A language model for mathematics leveraging  a variant of Proximal Policy Optimization (PPO) called Group Relative Policy Optimization (GRPO), without relying on external toolkits or voting techniques. |
| [Open Math Instruct 1](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#8709) | February 2024 | A math instruction tuning dataset containing 1.8M code interpreter styled problem-solution pairs for GSM8K and MATH dataset, generated using Mixtral. |
| [Math Orca](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#80d0) | February 2024 | A fine tuned Mistral-7B that excels at math problems without external tools, utilizing a high-quality synthetic dataset of 200K problems created through multi-agent collaboration and an iterative learning process that involves practicing problem-solving, receiving feedback, and learning from preference pairs incorporating the model's solutions and feedback. |
| [Math Genie](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#8894) | February 2024 | A framework that generates diverse and reliable math problems by iteratively augmenting small-scale problem-solution datasets and back-translating, followed by generating and verifying code-integrated solutions |
| [Xwin-Math](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#f71c) | March 2024 | Scales up GSM 8K and MATH dataset to 1.44M questions using data synthesis and then Llama 2, Mistral, Llemma are finetuned on the curated datasets. |
| [MuMath Code](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#9fb8) | May 2024 | Integrates tool use and data augmentation by finetuning Llama-2 on a dataset of math questions with code-nested solutions. |
| [Numina Math](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#b743) | July 2024 | Winner of the 1st AIMO Progress Prize, based on DeepSeek Math, finetuned in two stages: CoT and ToRA. |
| [Qwen 2 Math](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#e37a) | August 2024 | A model series focused on mathematical capabilities, built upon the Qwen2, outperforming proprietary models such as GPT-4o and Claude 3.5 in math-related tasks. |
| [Qwen 2.5 Math](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#eb40) | September 2024 | An upgrade of Qwen 2 Math series with improved performance and expanded support to Tool Integrated Reasoning. |
| [Open Math Instruct 2](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#ff3a) | October 2024 | A math instruction tuning dataset containing 14M question-solution pairs (≈ 600K unique questions) augmented from GSM8K and MATH dataset, generated using Llama 3.2 405B. |
| [Math Coder 2](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#97c9) | October 2024 | Creates Math Code Pile by filtering web data and then extracting and translating mathematical data from it to create a corpus of interleaved reasoning and code data. |
| [AceMath](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c#65b1) | December 2024 | A suite of math instruction-following models, trained through a two-stage SFT process focusing on general and math-specific reasoning, utilizing high-quality synthetic data and a specialized reward model (AceMath-RM) trained with diverse responses. |

## Multi Modal Language Models

| Paper | Date | Description |
|---|---|---|
| [Florence](https://ritvik19.medium.com/papers-explained-213-florence-f93a3a7d9ef0) | November 2021 | A computer vision foundation model that can be adapted to various tasks by expanding representations from coarse (scene) to fine (object), static (images) to dynamic (videos), and RGB to multiple modalities. |
| [BLIP](https://ritvik19.medium.com/papers-explained-154-blip-6d85c80a744d) | February 2022 | A Vision-Language Pre-training (VLP) framework that introduces Multimodal mixture of Encoder-Decoder (MED) and Captioning and Filtering (CapFilt), a new dataset bootstrapping method for learning from noisy image-text pairs. |
| [Flamingo](https://ritvik19.medium.com/papers-explained-82-flamingo-8c124c394cdb) | April 2022 | Visual Language Models enabling seamless handling of interleaved visual and textual data, and facilitating few-shot learning on large-scale web corpora. |
| [PaLI](https://ritvik19.medium.com/papers-explained-194-pali-c1fffc14068c) | September 2022 | A joint language-vision model that generates multilingual text based on visual and textual inputs, trained using large pre-trained encoder-decoder language models and Vision Transformers, specifically mT5 and ViT-e. |
| [BLIP 2](https://ritvik19.medium.com/papers-explained-155-blip-2-135fff70bf65) | January 2023 | A Vision-Language Pre-training (VLP) framework that proposes Q-Former, a trainable module to bridge the gap between a frozen image encoder and a frozen LLM to bootstrap vision-language pre-training. |
| [LLaVA 1](https://ritvik19.medium.com/papers-explained-102-llava-1-eb0a3db7e43c) | April 2023 | A large multimodal model connecting CLIP and Vicuna trained end-to-end on instruction-following data generated through GPT-4 from image-text pairs. |
| [PaLI-X](https://ritvik19.medium.com/papers-explained-195-pali-x-f9859e73fd97) | May 2023 | A multilingual vision and language model with scaled-up components, specifically ViT-22 B and UL2 32B, exhibits emergent properties such as complex counting and multilingual object detection, and demonstrates improved performance across various tasks. |
| [InstructBLIP](https://ritvik19.medium.com/papers-explained-156-instructblip-c3cf3291a823) | May 2023 | Introduces instruction-aware Query Transformer to extract informative features tailored to the given instruction to study vision-language instruction tuning based on the pretrained BLIP-2 models. |
| [Idefics](https://ritvik19.medium.com/papers-explained-179-obelics-idefics-a581f8d909b6) | June 2023 | 9B and 80B multimodal models trained on Obelics, an open web-scale dataset of interleaved image-text documents, curated in this work. |
| [GPT-4V](https://ritvik19.medium.com/papers-explained-68-gpt-4v-6e27c8a1d6ea) | September 2023 | A multimodal model that combines text and vision capabilities, allowing users to instruct it to analyze image inputs. |
| [PaLI-3](https://ritvik19.medium.com/papers-explained-196-pali-3-2f5cf92f60a8) | October 2023 | A 5B vision language model, built upon a 2B SigLIP Vision Model and UL2 3B Language Model outperforms larger models on various benchmarks and achieves SOTA on several video QA benchmarks despite not being pretrained on any video data. |
| [LLaVA 1.5](https://ritvik19.medium.com/papers-explained-103-llava-1-5-ddcb2e7f95b4) | October 2023 | An enhanced version of the LLaVA model that incorporates a CLIP-ViT-L-336px with an MLP projection and academic-task-oriented VQA data to set new benchmarks in large multimodal models (LMM) research. |
| [Florence-2](https://ritvik19.medium.com/papers-explained-214-florence-2-c4e17246d14b) | November 2023 | A vision foundation model with a unified, prompt-based representation for a variety of computer vision and vision-language tasks. | 
| [CogVLM](https://ritvik19.medium.com/papers-explained-235-cogvlm-9f3aa657f9b1) | November 2023 | Bridges the gap between the frozen pretrained language model and image encoder by a trainable visual expert module in the attention and FFN layers. |
| [Gemini 1.0](https://ritvik19.medium.com/papers-explained-80-gemini-1-0-97308ef96fcd) | December 2023 | A family of highly capable multi-modal models, trained jointly across image, audio, video, and text data for the purpose of building a model with strong generalist capabilities across modalities. |
| [MoE-LLaVA](https://ritvik19.medium.com/papers-explained-104-moe-llava-cf14fda01e6f) | January 2024 | A MoE-based sparse LVLM framework that activates only the top-k experts through routers during deployment, maintaining computational efficiency while achieving comparable performance to larger models. |
| [LLaVA 1.6](https://ritvik19.medium.com/papers-explained-107-llava-1-6-a312efd496c5) | January 2024 | An improved version of a LLaVA 1.5 with enhanced reasoning, OCR, and world knowledge capabilities, featuring increased image resolution |
| [Gemini 1.5 Pro](https://ritvik19.medium.com/papers-explained-105-gemini-1-5-pro-029bbce3b067) | February 2024 | A highly compute-efficient multimodal mixture-of-experts model that excels in long-context retrieval tasks and understanding across text, video, and audio modalities. |
| [Claude 3](https://ritvik19.medium.com/papers-explained-181-claude-89dd45e35d92) | March 2024 | A family of VLMs consisting of Claude 3 Haiku, Claude 3 Sonnet, and Claude 3 Opus, sets new industry standards for cognitive tasks, offering varying levels of intelligence, speed, and cost-efficiency. |
| [MM1](https://ritvik19.medium.com/papers-explained-117-mm1-c579142bcdc0) | March 2024 | A multimodal llm that combines a ViT-H image encoder with 378x378px resolution, pretrained on a data mix of image-text documents and text-only documents, scaled up to 3B, 7B, and 30B parameters for enhanced performance across various tasks. |
| [Grok 1.5 V](https://ritvik19.medium.com/papers-explained-186-grok-0d9f1aef69be) | April 2024 | The first multimodal model in the grok series. |
| [Idefics2](https://ritvik19.medium.com/papers-explained-180-idefics-2-0adf35cef4ee) | April 2024 | Improvement upon Idefics1 with enhanced OCR capabilities, simplified architecture, and better pre-trained backbones, trained on a mixture of openly available datasets and fine-tuned on task-oriented data. |
| [Phi 3 Vision](https://ritvik19.medium.com/papers-explained-130-phi-3-0dfc951dc404#7ba6) | May 2024 | First multimodal model in the Phi family, bringing the ability to reason over images and extract and reason over text from images. |
| [An Introduction to Vision-Language Modeling](https://ritvik19.medium.com/papers-explained-an-introduction-to-vision-language-modeling-89e7697da6e3) | May 2024 | Provides a comprehensive introduction to VLMs, covering their definition, functionality, training methods, and evaluation approaches, aiming to help researchers and practitioners enter the field and advance the development of VLMs for various applications. |
| [GPT-4o](https://ritvik19.medium.com/papers-explained-185-gpt-4o-a234bccfd662) | May 2024 | An omni model accepting and generating various types of inputs and outputs, including text, audio, images, and video. |
| [Gemini 1.5 Flash](https://ritvik19.medium.com/papers-explained-142-gemini-1-5-flash-415e2dc6a989) | May 2024 | A more lightweight variant of the Gemini 1.5 pro, designed for efficiency with minimal regression in quality, making it suitable for applications where compute resources are limited. |
| [Chameleon](https://ritvik19.medium.com/papers-explained-143-chameleon-6cddfdbceaa8) | May 2024 | A family of early-fusion token-based mixed-modal models capable of understanding and generating images and text in any arbitrary sequence. |
| [Claude 3.5 Sonnet](https://ritvik19.medium.com/papers-explained-181-claude-89dd45e35d92#2a14) | June 2024 | Surpasses previous versions and competitors in intelligence, speed, and cost-efficiency, excelling in graduate-level reasoning, undergraduate-level knowledge, coding proficiency, and visual reasoning. |
| [Pali Gemma](https://ritvik19.medium.com/papers-explained-197-pali-gemma-6899e871998e) | July 2024 | Combines SigLIP vision model and the Gemma language model and follows the PaLI-3 training recipe to achieve strong performance on various vision-language tasks. |
| [GPT-4o mini](https://ritvik19.medium.com/papers-explained-185-gpt-4o-a234bccfd662#08b9) | July 2024 | A cost-efficient small model that outperforms GPT-4 on chat preferences, enabling a broad range of tasks with low latency and supporting text, vision, and multimodal inputs and outputs. |
| [Grok 2](https://ritvik19.medium.com/papers-explained-186-grok-0d9f1aef69be) | August 2024 | A frontier language model with state-of-the-art capabilities in chat, coding, and reasoning on par with Claude 3.5 Sonnet and GPT-4-Turbo. |
| [BLIP-3 (xGen-MM)](https://ritvik19.medium.com/papers-explained-190-blip-3-xgen-mm-6a9c04a3892d) | August 2024 | A comprehensive system for developing Large Multimodal Models, comprising curated datasets, training recipes, model architectures, and pre-trained models that demonstrate strong in-context learning capabilities and competitive performance on various tasks. |
| [Idefics 3](https://ritvik19.medium.com/papers-explained-218-idefics-3-81791c4cde3f) | August 2024 | A VLM based on Llama 3.1 and SigLIP-SO400M trained efficiently, using only open datasets and a straightforward pipeline, significantly outperforming in document understanding tasks. |
| [CogVLM2](https://ritvik19.medium.com/papers-explained-236-cogvlm2-db0261745cf5) | August 2024 | A family of visual language models that enables image and video understanding with improved training recipes, exploring enhanced vision-language fusion, higher input resolution, and broader modalities and applications. |
| [Eagle](https://ritvik19.medium.com/papers-explained-269-eagle-09c21e549395) | August 2024 | Provides an extensive exploration of the design space for MLLMs using a mixture of vision encoders and resolutions, and reveals several underlying principles common to various existing strategies, leading to a streamlined yet effective design approach. |
| [Pixtral](https://ritvik19.medium.com/papers-explained-219-pixtral-a714f94e59ac) | September 2024 | A 12B parameter natively multimodal vision-language model, trained with interleaved image and text data demonstrating strong performance on multimodal tasks, and excels in instruction following. |
| [NVLM](https://ritvik19.medium.com/papers-explained-240-nvlm-7ad201bfbfc2) | September 2024 | A family of multimodal large language models, provides a comparison between decoder-only multimodal LLMs and cross-attention based models and proposes a hybrid architecture, it further introduces a 1-D title-tagging design for tile-based dynamic high resolution images. |
| [Molmo](https://ritvik19.medium.com/papers-explained-241-pixmo-and-molmo-239d70abebff) | September 2024 | A family of open-weight vision-language models that achieve state-of-the-art performance by leveraging a novel, human-annotated image caption dataset called PixMo. |
| [MM-1.5](https://ritvik19.medium.com/papers-explained-261-mm-1-5-d0dd01a9b68b) | September 2024 | A family of multimodal large language models designed to enhance capabilities in text-rich image understanding, visual referring and grounding, and multi-image reasoning, achieved through a data-centric approach involving diverse data mixtures, And specialized variants for video and mobile UI understanding. |
| [Mississippi](https://ritvik19.medium.com/papers-explained-251-h2ovl-mississippi-1508e9c8e862) | October 2024 | A collection of small, efficient, open-source vision-language models built on top of Danube, trained on 37 million image-text pairs, specifically designed to perform well on document analysis and OCR tasks while maintaining strong performance on general vision-language benchmarks. |
| [Claude 3.5 Haiku](https://ritvik19.medium.com/papers-explained-181-claude-89dd45e35d92#9637) | October 2024 | A fast and affordable language model that excels in tasks such as coding, reasoning, and content creation. |
| [Smol VLM](https://ritvik19.medium.com/papers-explained-176-smol-lm-a166d5f1facc#6245) | November 2024 | A 2B vision-language model, built using a modified Idefics3 architecture with a smaller language backbone (SmolLM2 1.7B), aggressive pixel shuffle compression, 384x384 image patches, and a shape-optimized SigLIP vision backbone, featuring a 16k token context window. |

## Retrieval and Representation Learning

| Paper | Date | Description |
|---|---|---|
| [SimCLR](https://ritvik19.medium.com/papers-explained-200-simclr-191ecf19d2fc) | February 2020 |  A simplified framework for contrastive learning that optimizes data augmentation composition, introduces learnable nonlinear transformations, and leverages larger batch sizes and more training steps. |
| [Dense Passage Retriever](https://ritvik19.medium.com/papers-explained-86-dense-passage-retriever-c4742fdf27ed) | April 2020 | Shows that retrieval can be practically implemented using dense representations alone, where embeddings are learned from a small number of questions and passages by a simple dual encoder framework. |
| [ColBERT](https://medium.com/@ritvik19/papers-explained-88-colbert-fe2fd0509649) | April 2020 | Introduces a late interaction architecture that adapts deep LMs (in particular, BERT) for efficient retrieval. |
| [SimCLRv2](https://ritvik19.medium.com/papers-explained-201-simclrv2-bc3fe72b8b48) | June 2020 | A Semi-supervised learning framework which uses unsupervised pre training followed by supervised fine-tuning and distillation with unlabeled examples. |
| [CLIP](https://ritvik19.medium.com/papers-explained-100-clip-f9873c65134) | February 2021 | A vision system that learns image representations from raw text-image pairs through pre-training, enabling zero-shot transfer to various downstream tasks. |
| [ColBERTv2](https://ritvik19.medium.com/papers-explained-89-colbertv2-7d921ee6e0d9) | December 2021 | Couples an aggressive residual compression mechanism with a denoised supervision strategy to simultaneously improve the quality and space footprint of late interaction. |
| [Matryoshka Representation Learning](https://ritvik19.medium.com/papers-explained-matryoshka-representation-learning-e7a139f6ad27) | May 2022 | Encodes information at different granularities and allows a flexible representation that can adapt to multiple downstream tasks with varying computational resources using a single embedding. |
| [E5](https://ritvik19.medium.com/papers-explained-90-e5-75ea1519efad) | December 2022 | A family of text embeddings trained in a contrastive manner with weak supervision signals from a curated large-scale text pair dataset CCPairs. |
| [SigLip](https://ritvik19.medium.com/papers-explained-152-siglip-011c48f9d448) | March 2023 | A simple pairwise Sigmoid loss function for Language-Image Pre-training that operates solely on image-text pairs, allowing for larger batch sizes and better performance at smaller batch sizes. |
| [Jina Embeddings v1](https://ritvik19.medium.com/papers-explained-263-jina-embeddings-v1-33336e9efb0f) | July 2023 | Contrastively fine tuned T5 encoder on curated high quality pairwise and triplet data specifically to sensitize the models to distinguish negations of statements from confirming statements. |
| [Jina Embeddings v2](https://ritvik19.medium.com/papers-explained-264-jina-embeddings-v2-c5d540a9154f) | October 2023 | An open-source text embedding model capable of accommodating up to 8192 tokens, trained by pre-training a modified BERT from scratch before fine tuning for embeddings objectives. |
| [SynCLR](https://ritvik19.medium.com/papers-explained-202-synclr-85b50ef0081b) | December 2023 | A visual representation learning method that leverages generative models to synthesize large-scale curated datasets without relying on any real data. |
| [E5 Mistral 7B](https://ritvik19.medium.com/papers-explained-91-e5-mistral-7b-23890f40f83a) | December 2023 | Leverages proprietary LLMs to generate diverse synthetic data to fine tune open-source decoder-only LLMs for hundreds of thousands of text embedding tasks. |
| [Nomic Embed Text v1](https://ritvik19.medium.com/papers-explained-110-nomic-embed-8ccae819dac2) | February 2024 | A 137M parameter, open-source English text embedding model with an 8192 context length that outperforms OpenAI's models on both short and long-context tasks. |
| [Nomic Embed Text v1.5](https://ritvik19.medium.com/papers-explained-110-nomic-embed-8ccae819dac2#2119) | February 2024 | An advanced text embedding model that utilizes Matryoshka Representation Learning to offer flexible embedding sizes with minimal performance trade-offs |
| [Jina Bilingual Embeddings](https://ritvik19.medium.com/papers-explained-265-jina-bilingual-embeddings-39960d6f7a7c) | February 2024 | A suite of bilingual text embedding models that support up to 8192 tokens, trained by pre-training a modified bilingual BERT from scratch before fine tuning for embeddings objectives. |
| [Jina Reranker](https://ritvik19.medium.com/papers-explained-267-jina-reranker-daf6fdf8b2a6) | February 2024 | A neural reranking model that enhances search and RAG systems by reordering retrieved documents for better alignment with search query terms. |
| [Gecko](https://ritvik19.medium.com/papers-explained-203-gecko-8889158b17e6) | March 2024 | A 1.2B versatile text embedding model achieving strong retrieval performance by distilling knowledge from LLMs into a retriever. |
| [NV Embed](https://ritvik19.medium.com/papers-explained-168-nv-embed-48bd25d83258) | May 2024 | Introduces architectural innovations and training recipe to significantly enhance LLMs performance in general-purpose text embedding tasks. |
| [Nomic Embed Vision v1 and v1.5](https://ritvik19.medium.com/papers-explained-110-nomic-embed-8ccae819dac2#486b) | June 2024 | Aligns a Vision Encoder with the existing text encoders without destroying the downstream performance of the text encoder, to attain a unified multimodal latent space. |
| [ColPali](https://ritvik19.medium.com/papers-explained-198-colpali-b3be70cbe252) | June 2024 | A retrieval model based on PaliGemma to produce high-quality contextualized embeddings solely from images of document pages, and employees late interaction allowing for efficient and effective visually rich document retrieval. |
| [Jina Reranker v2](https://ritvik19.medium.com/papers-explained-267-jina-reranker-daf6fdf8b2a6#4405) | June 2024 | Builds upon Jina Reranker v1 by adding multilingual support, function-calling capabilities, structured data querying, code retrieval, and ultra-fast inference. |
| [E5-V](https://ritvik19.medium.com/papers-explained-172-e5-v-9947d3925802) | July 2024 | A framework that adapts Multimodal Large Language Models for achieving universal multimodal embeddings by leveraging prompts and single modality training on text pairs, which demonstrates strong performance in multimodal embeddings without fine-tuning and eliminates the need for costly multimodal training data collection. |
| [Matryoshka Adaptor](https://ritvik19.medium.com/papers-explained-204-matryoshka-adaptor-c22f76488959) | July 2024 | A framework designed for the customization of LLM embeddings, facilitating substantial dimensionality reduction while maintaining comparable performance levels.  |
| [Jina Embeddings v3](https://ritvik19.medium.com/papers-explained-266-jina-embeddings-v3-9c38c9f69766) | September 2024 | A text embedding model with 570 million parameters that supports long-context retrieval tasks up to 8192 tokens, includes LoRA adapters for various NLP tasks, and allows flexible output dimension reduction from 1024 down to 32 using Matryoshka Representation Learning. |



## Parameter Efficient Fine Tuning

| Paper | Date | Description |
|---|---|---|
| [LoRA](https://ritvik19.medium.com/papers-explained-lora-a48359cecbfa) | July 2021 | Introduces trainable rank decomposition matrices into each layer of a pre-trained Transformer model, significantly reducing the number of trainable parameters for downstream tasks. |
| [DyLoRA](https://ritvik19.medium.com/papers-explained-review-06-parameter-efficient-finetuning-6934fafa74e5#7fb6) | October 2022 | Allows for flexible rank size by randomly truncating low-rank matrices during training, enabling adaptation to different rank values without retraining. |
| [AdaLoRA](https://ritvik19.medium.com/papers-explained-review-06-parameter-efficient-finetuning-6934fafa74e5#620f) | March 2023 | Dynamically allocates a parameter budget based on an importance metric to prune less important singular values during training. |
| [QLoRA](https://ritvik19.medium.com/papers-explained-146-qlora-a6e7273bc630) | May 2023 | Allows efficient training of large models on limited GPU memory, through innovations like 4-bit NormalFloat (NF4), double quantization, and paged optimizers. |
| [LoRA-FA](https://ritvik19.medium.com/papers-explained-review-06-parameter-efficient-finetuning-6934fafa74e5#c229) | August 2023 | Freezes one of the low-rank matrices and only trains a scaling vector for the other, further reducing the number of trainable parameters compared to standard LoRA. |
| [Delta-LoRA](https://ritvik19.medium.com/papers-explained-review-06-parameter-efficient-finetuning-6934fafa74e5#a4ec) | September 2023 | Utilizes the delta of the low-rank matrix updates to refine the pre-trained weights directly, removing the Dropout layer for accurate backpropagation. |
| [LongLoRA](https://ritvik19.medium.com/papers-explained-147-longlora-24f095b93611) | September 2023 | Enables context extension for large language models, achieving significant computation savings through sparse local attention and parameter-efficient fine-tuning. |
| [VeRA](https://ritvik19.medium.com/papers-explained-review-06-parameter-efficient-finetuning-6934fafa74e5#5bb3) | October 2023 | Utilizes frozen, shared random matrices across all layers and trains scaling vectors to adapt those matrices for each layer, reducing the number of trainable parameters compared to LoRA. |
| [LoRA+](https://ritvik19.medium.com/papers-explained-review-06-parameter-efficient-finetuning-6934fafa74e5#fd31) | February 2024 | Enhances LoRA by setting different learning rates for the A and B matrices based on a fixed ratio, promoting better feature learning and improved performance. |
| [MoRA](https://ritvik19.medium.com/papers-explained-review-06-parameter-efficient-finetuning-6934fafa74e5#21a4) | May 2024 | Introduces a square matrix and non-parameterized operators to achieve high-rank updating with the same number of trainable parameters as LoRA, improving knowledge memorization capabilities. |
| [DoRA](https://ritvik19.medium.com/papers-explained-review-06-parameter-efficient-finetuning-6934fafa74e5#028e) | May 2024 | Decomposes the high-rank LoRA matrix into multiple single-rank components, allowing dynamic pruning of less important components during training for a more efficient parameter budget allocation. |

## LLM Evaluation

| Paper | Date | Description |
|---|---|---|
| [Prometheus](https://ritvik19.medium.com/papers-explained-170-prometheus-5e72b8054729) | October 2023 | A 13B fully open source evaluation LLM trained on Feedback Collection curated using GPT-4 (in this work). |
| [Prometheus 2](https://ritvik19.medium.com/papers-explained-171-prometheus-2-324e9c162e18) | May 2024 | 7B & 8x7B evaluation LLMs that score high correlations with both human evaluators and proprietary LM-based judges on both direct assessment and pairwise ranking, obtained by merging Mistral models trained on Feedback Collection and Preference Collection (curated in this work. |

## Compression, Pruning, Quantization

| Paper | Date | Description |
|---|---|---|
| [LLMLingua](https://ritvik19.medium.com/papers-explained-136-llmlingua-f9b2f53f5f9b) | October 2023 | A novel coarse-to-fine prompt compression method, incorporating a budget controller, an iterative token-level compression algorithm, and distribution alignment, achieving up to 20x compression with minimal performance loss. |
| [LongLLMLingua](https://ritvik19.medium.com/papers-explained-137-longllmlingua-45961fa703dd) | October 2023 | A novel approach for prompt compression to enhance performance in long context scenarios using question-aware compression and document reordering. |
| [LLMLingua2](https://ritvik19.medium.com/papers-explained-138-llmlingua-2-510c752368a8) | March 2024 | A novel approach to task-agnostic prompt compression, aiming to enhance generalizability, using  data distillation and leveraging a Transformer encoder for token classification. |

## Vision Transformers

| Paper | Date | Description |
|---|---|---|
| [Vision Transformer](https://ritvik19.medium.com/papers-explained-25-vision-transformers-e286ee8bc06b) | October 2020 | Images are segmented into patches, which are treated as tokens and a sequence of linear embeddings of these patches are input to a Transformer |
| [DeiT](https://ritvik19.medium.com/papers-explained-39-deit-3d78dd98c8ec) | December 2020 | A convolution-free vision transformer that uses a teacher-student strategy with attention-based distillation tokens. |
| [Swin Transformer](https://ritvik19.medium.com/papers-explained-26-swin-transformer-39cf88b00e3e) | March 2021 | A hierarchical vision transformer that uses shifted windows to addresses the challenges of adapting the transformer model to computer vision. |
| [Convolutional Vision Transformer](https://ritvik19.medium.com/papers-explained-199-cvt-fb4a5c05882e) | March 2021 | Improves Vision Transformer (ViT) in performance and efficiency by introducing convolutions, to yield the best of both designs. |
| [LeViT](https://ritvik19.medium.com/papers-explained-205-levit-89a2defc2d18) | April 2021 | A hybrid neural network built upon the ViT architecture and DeiT training method, for fast inference image classification. |
| [DINO](https://ritvik19.medium.com/papers-explained-249-dino-f7e2c7f438ab) | April 2021 | Investigates whether self-supervised learning provides new properties to Vision Transformer that stand out compared to convolutional networks and finds that self-supervised ViT features contain explicit information about the semantic segmentation of an image, and are also excellent k-NN classifiers. |
| [BEiT](https://ritvik19.medium.com/papers-explained-27-beit-b8c225496c01) | June 2021 | Utilizes a masked image modeling task inspired by BERT in, involving image patches and visual tokens to pretrain vision Transformers. |
| [MobileViT](https://ritvik19.medium.com/papers-explained-40-mobilevit-4793f149c434) | October 2021 | A lightweight vision transformer designed for mobile devices, effectively combining the strengths of CNNs and ViTs. |
| [Masked AutoEncoder](https://ritvik19.medium.com/papers-explained-28-masked-autoencoder-38cb0dbed4af) | November 2021 | An encoder-decoder architecture that reconstructs input images by masking random patches and leveraging a high proportion of masking for self-supervision. |
| [DINOv2](https://ritvik19.medium.com/papers-explained-250-dino-v2-e1e6d12a5c85) | April 2022 | Demonstrates that existing self-supervised pre-training methods can produce general-purpose visual features by training on curated data from diverse sources, and proposes a new approach that combines techniques to scale pre-training with larger models and datasets. |
| [MaxViT](https://ritvik19.medium.com/papers-explained-210-maxvit-6c68cc515413) | April 2022 | Introduces multi-axis attention, allowing global-local spatial interactions on arbitrary input resolutions with only linear complexity. |
| [Swin Transformer V2](https://ritvik19.medium.com/papers-explained-215-swin-transformer-v2-53bee16ab668) | April 2022 | A successor to Swin Transformer, addressing challenges like training stability, resolution gaps, and labeled data scarcity. |
| [EfficientFormer](https://ritvik19.medium.com/papers-explained-220-efficientformer-97c91540af19) | June 2022 | Revisits the design principles of ViT and its variants through latency analysis and identifies inefficient designs and operators in ViT to propose a new dimension consistent design paradigm for vision transformers and a simple yet effective latency-driven slimming method to optimize for inference speed. |
| [FastViT](https://ritvik19.medium.com/papers-explained-225-fastvit-f1568536ed34) | March 2023 | A hybrid vision transformer architecture featuring a novel token mixing operator called RepMixer, which significantly improves model efficiency. |
| [Efficient Vit](https://ritvik19.medium.com/papers-explained-229-efficient-vit-cc87fbefbe49) | May 2023 | Employs a single memory-bound MHSA between efficient FFN layers, improves memory efficiency while enhancing channel communication. |
| [SoViT](https://ritvik19.medium.com/papers-explained-234-sovit-a0ce3c7ef480) | May 2023 | A shape-optimized vision transformer that achieves competitive results with models twice its size, while being pre-trained with an equivalent amount of compute. |


## Convolutional Neural Networks

| Paper | Date | Description |
|---|---|---|
| [Lenet](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#4f26) | December 1998 | Introduced Convolutions. |
| [Alex Net](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#f7c6) | September 2012 | Introduced ReLU activation and Dropout to CNNs. Winner ILSVRC 2012. |
| [VGG](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#c122) | September 2014 | Used large number of filters of small size in each layer to learn complex features. Achieved SOTA in ILSVRC 2014. |
| [Inception Net](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#d7b3) | September 2014 | Introduced Inception Modules consisting of multiple parallel convolutional layers, designed to recognize different features at multiple scales. |
| [Inception Net v2 / Inception Net v3](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#d7b3) | December 2015 | Design Optimizations of the Inception Modules which improved performance and accuracy. |
| [Res Net](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#f761) | December 2015 | Introduced residual connections, which are shortcuts that bypass one or more layers in the network. Winner ILSVRC 2015. |
| [Inception Net v4 / Inception ResNet](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#83ad) | February 2016 | Hybrid approach combining Inception Net and ResNet. |
| [Dense Net](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#65e8) | August 2016 | Each layer receives input from all the previous layers, creating a dense network of connections between the layers, allowing to learn more diverse features. |
| [Xception](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#bc70) | October 2016 | Based on InceptionV3 but uses depthwise separable convolutions instead on inception modules. |
| [Res Next](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#90bd) | November 2016 | Built over ResNet, introduces the concept of grouped convolutions, where the filters in a convolutional layer are divided into multiple groups. |
| [Mobile Net V1](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#3cb5) | April 2017 | Uses depthwise separable convolutions to reduce the number of parameters and computation required. |
| [Mobile Net V2](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#4440) | January 2018 | Built upon the MobileNetv1 architecture, uses inverted residuals and linear bottlenecks. |
| [Mobile Net V3](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#8eb6) | May 2019 | Uses AutoML to find the best possible neural network architecture for a given problem. |
| [Efficient Net](https://ritvik19.medium.com/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3#560a) | May 2019 | Uses a compound scaling method to scale the network's depth, width, and resolution to achieve a high accuracy with a relatively low computational cost. |
| [NF Net](https://ritvik19.medium.com/papers-explained-84-nf-net-b8efa03d6b26) | February 2021 | An improved class of Normalizer-Free ResNets that implement batch-normalized networks, offer faster training times, and introduce an adaptive gradient clipping technique to overcome instabilities associated with deep ResNets. |
| [Conv Mixer](https://ritvik19.medium.com/papers-explained-29-convmixer-f073f0356526) | January 2022 | Processes image patches using standard convolutions for mixing spatial and channel dimensions. |
| [ConvNeXt](https://ritvik19.medium.com/papers-explained-92-convnext-d13385d9177d) | January 2022 | A pure ConvNet model, evolved from standard ResNet design, that competes well with Transformers in accuracy and scalability. |
| [ConvNeXt V2](https://ritvik19.medium.com/papers-explained-94-convnext-v2-2ecdabf2081c) | January 2023 | Incorporates a fully convolutional MAE framework and a Global Response Normalization (GRN) layer, boosting performance across multiple benchmarks. |
| [Efficient Net V2](https://ritvik19.medium.com/papers-explained-efficientnetv2-a7a1e4113b89) | April 2024 | A new family of convolutional networks, achieves faster training speed and better parameter efficiency than previous models through neural architecture search and scaling, with progressive learning allowing for improved accuracy on various datasets while training up to 11x faster. |
| [MobileNetV4](https://ritvik19.medium.com/papers-explained-232-mobilenetv4-83a526887c30) | April 2024 | Features a universally efficient architecture design, including the Universal Inverted Bottleneck (UIB) search block, Mobile MQA attention block, and an optimized neural architecture search recipe, which enables it to achieve high accuracy and efficiency on various mobile devices and accelerators. |

## Object Detection

| Paper | Date | Description |
|---|---|---|
| [SSD](https://ritvik19.medium.com/papers-explained-31-single-shot-multibox-detector-14b0aa2f5a97) | December 2015 | Discretizes bounding box outputs over a span of various scales and aspect ratios per feature map. |
| [Feature Pyramid Network](https://ritvik19.medium.com/papers-explained-21-feature-pyramid-network-6baebcb7e4b8) | December 2016 | Leverages the inherent multi-scale hierarchy of deep convolutional networks to efficiently construct feature pyramids. |
| [Focal Loss](https://ritvik19.medium.com/papers-explained-22-focal-loss-for-dense-object-detection-retinanet-733b70ce0cb1) | August 2017 | Addresses class imbalance in dense object detectors by down-weighting the loss assigned to well-classified examples. |
| [DETR](https://ritvik19.medium.com/papers-explained-79-detr-bcdd53355d9f) | May 2020 | A novel object detection model that treats object detection as a set prediction problem, eliminating the need for hand-designed components. |
| [OWL ViT](https://ritvik19.medium.com/papers-explained-237-owl-vit-ea58a142de68) | May 2022 | Employs Vision Transformers, CLIP-based contrastive pre-training, and bipartite matching loss for open-vocabulary detection, utilizing image-level pre-training, multihead attention pooling, and mosaic image augmentation. |
| [Segment Anything Model](https://ritvik19.medium.com/papers-explained-238-segment-anything-model-b3960b569fce) | April 2023 | Introduces a novel image segmentation task, model, and dataset, aiming to enable prompt-able, zero-shot transfer learning in computer vision. | 
| [SAM 2](https://ritvik19.medium.com/papers-explained-239-sam-2-6ffb7f187281) | July 2024 | A foundation model towards solving promptable visual segmentation in images and videos based on a simple transformer architecture with streaming memory for real-time video processing. |

## Region-based Convolutional Neural Networks

| Paper | Date | Description |
|---|---|---|
| [RCNN](https://ritvik19.medium.com/papers-explained-14-rcnn-ede4db2de0ab) | November 2013 | Uses selective search for region proposals, CNNs for feature extraction, SVM for classification followed by box offset regression. |
| [Fast RCNN](https://ritvik19.medium.com/papers-explained-15-fast-rcnn-28c1792dcee0) | April 2015 | Processes entire image through CNN, employs RoI Pooling to extract feature vectors from ROIs, followed by classification and BBox regression. |
| [Faster RCNN](https://ritvik19.medium.com/papers-explained-16-faster-rcnn-a7b874ffacd9) | June 2015 | A region proposal network (RPN) and a Fast R-CNN detector, collaboratively predict object regions by sharing convolutional features. |
| [Mask RCNN](https://ritvik19.medium.com/papers-explained-17-mask-rcnn-82c64bea5261) | March 2017 | Extends Faster R-CNN to solve instance segmentation tasks, by adding a branch for predicting an object mask in parallel with the existing branch. |
| [Cascade RCNN](https://ritvik19.medium.com/papers-explained-77-cascade-rcnn-720b161d86e4) | December 2017 | Proposes a multi-stage approach where detectors are trained with progressively higher IoU thresholds, improving selectivity against false positives. |

## Document AI

| Paper | Date | Description |
|---|---|---|
| [Table Net](https://ritvik19.medium.com/papers-explained-18-tablenet-3d4c62269bb3) | January 2020 | An end-to-end deep learning model designed for both table detection and structure recognition. |
| [SPADE](https://ritvik19.medium.com/f564ce612501) | May 2020 | Formulates Information Extraction (IE) as a spatial dependency parsing problem. |
| [Layout Parser](https://ritvik19.medium.com/papers-explained-245-layout-parser-d29bb291890c) | March 2021 | A library integrating Detectron2, CNN-RNN OCR, layout structures, TensorFlow/PyTorch, and a Model Zoo. The toolkit features Tesseract, Google Cloud Vision for OCR, active learning tools and community platform ensures efficiency and adaptability. |
| [Layout Reader](https://ritvik19.medium.com/papers-explained-247-layout-reader-248b27db1234) | August 2021 | A seq2seq model that accurately predicts reading order, text, and layout information from document images. |
| [Donut](https://ritvik19.medium.com/papers-explained-20-donut-cb1523bf3281) | November 2021 | An OCR-free Encoder-Decoder Transformer model. The encoder takes in images, decoder takes in prompts & encoded images to generate the required text. |
| [DiT](https://ritvik19.medium.com/papers-explained-19-dit-b6d6eccd8c4e) | March 2022 | An Image Transformer pre-trained (self-supervised) on document images |
| [Pix2Struct](https://ritvik19.medium.com/papers-explained-254-pix2struct-6adc95a01586) | October 2022 | A pretrained image-to-text model designed for visual language understanding, particularly in tasks involving visually-situated language. |
| [Matcha](https://ritvik19.medium.com/papers-explained-255-matcha-d5d5fe66b039) | December 2022 | Leverages Pix2Struct, and introduces pretraining tasks focused on math reasoning and chart derendering to improve chart and plot comprehension, enhancing understanding in diverse visual language tasks. |
| [DePlot](https://ritvik19.medium.com/papers-explained-256-deplot-3e8a02eefc94) | December 2022 | Built upon MatCha, standardises plot to table task, translating plots into linearized tables (markdown) for processing by LLMs. |
| [UDoP](https://ritvik19.medium.com/papers-explained-42-udop-719732358ab4) | December 2022 | Integrates text, image, and layout information through a Vision-Text-Layout Transformer, enabling unified representation. |
| [GeoLayoutLM](https://ritvik19.medium.com/papers-explained-258-geolayoutlm-f581eec8c8a2) | April 2023 | Explicitly models geometric relations in pre-training and enhances feature representation. |
| [Nougat](https://ritvik19.medium.com/papers-explained-257-nougat-bb304f7af0a3) | August 2023 | A Visual Transformer model that performs an Optical Character Recognition (OCR) task for processing scientific documents into a markup language. |
| [LMDX](https://ritvik19.medium.com/papers-explained-248-lmdx-854c0bc771f0) | September 2023 |  A methodology to adapt arbitrary LLMs for document information extraction. |
| [DocLLM](https://ritvik19.medium.com/papers-explained-87-docllm-93c188edfaef) | January 2024 | A lightweight extension to traditional LLMs that focuses on reasoning over visual documents, by incorporating textual semantics and spatial layout without expensive image encoders. |

## Layout Transformers

| Paper | Date | Description |
|---|---|---|
| [Layout LM](https://ritvik19.medium.com/papers-explained-10-layout-lm-32ec4bad6406) | December 2019 | Utilises BERT as the backbone, adds two new input embeddings: 2-D position embedding and image embedding (Only for downstream tasks). |
| [LamBERT](https://ritvik19.medium.com/papers-explained-41-lambert-8f52d28f20d9) | February 2020 | Utilises RoBERTa as the backbone and adds Layout embeddings along with relative bias. |
| [Layout LM v2](https://ritvik19.medium.com/papers-explained-11-layout-lm-v2-9531a983e659) | December 2020 | Uses a multi-modal Transformer model, to integrate text, layout, and image in the pre-training stage, to learn end-to-end cross-modal interaction. |
| [Structural LM](https://ritvik19.medium.com/papers-explained-23-structural-lm-36e9df91e7c1) | May 2021 | Utilises BERT as the backbone and feeds text, 1D and (2D cell level) embeddings to the transformer model. |
| [Doc Former](https://ritvik19.medium.com/papers-explained-30-docformer-228ce27182a0) | June 2021 | Encoder-only transformer with a CNN backbone for visual feature extraction, combines text, vision, and spatial features through a multi-modal self-attention layer. |
| [BROS](https://ritvik19.medium.com/papers-explained-246-bros-1f1127476f73) | August 2021 | Built upon BERT, encodes relative positions of texts in 2D space and learns from unlabeled documents with area masking strategy. |
| [LiLT](https://ritvik19.medium.com/papers-explained-12-lilt-701057ec6d9e) | February 2022 | Introduced Bi-directional attention complementation mechanism (BiACM) to accomplish the cross-modal interaction of text and layout. |
| [Layout LM V3](https://ritvik19.medium.com/papers-explained-13-layout-lm-v3-3b54910173aa) | April 2022 | A unified text-image multimodal Transformer to learn cross-modal representations, that imputs concatenation of text embedding and image embedding. |
| [ERNIE Layout](https://ritvik19.medium.com/papers-explained-24-ernie-layout-47a5a38e321b) | October 2022 | Reorganizes tokens using layout information, combines text and visual embeddings, utilizes multi-modal transformers with spatial aware disentangled attention. |

## Generative Adversarial Networks

| Paper | Date | Description |
|---|---|---|
| [Generative Adversarial Networks](https://ritvik19.medium.com/papers-explained-review-05-generative-adversarial-networks-bbb51b160d5e#7041) | June 2014 | Introduces a framework where, a generative and a discriminative model, are trained simultaneously in a minimax game. |
| [Conditional Generative Adversarial Networks](https://ritvik19.medium.com/papers-explained-review-05-generative-adversarial-networks-bbb51b160d5e#86aa) | November 2014 | A method for training GANs, enabling the generation based on specific conditions, by feeding them to both the generator and discriminator networks. |
| [Deep Convolutional Generative Adversarial Networks](https://ritvik19.medium.com/papers-explained-review-05-generative-adversarial-networks-bbb51b160d5e#fe42) | November 2015 | Demonstrates the ability of CNNs for unsupervised learning using specific architectural constraints designed. |
| [Improved GAN](https://ritvik19.medium.com/papers-explained-review-05-generative-adversarial-networks-bbb51b160d5e#9a55) | June 2016 | Presents a variety of new architectural features and training procedures that can be applied to the generative adversarial networks (GANs) framework. |
| [Wasserstein Generative Adversarial Networks](https://ritvik19.medium.com/papers-explained-review-05-generative-adversarial-networks-bbb51b160d5e#6f8f) | January 2017 | An alternative GAN training algorithm that enhances learning stability, mitigates issues like mode collapse. |
| [Cycle GAN](https://ritvik19.medium.com/papers-explained-review-05-generative-adversarial-networks-bbb51b160d5e#7f8b) | March 2017 | An approach for learning to translate an image from a source domain X to a target domain Y in the absence of paired examples by leveraging adversarial losses and cycle consistency constraints, using two GANs. |


## Tabular Deep Learning

| Paper | Date | Description |
|---|---|---|
| [Entity Embeddings](https://ritvik19.medium.com/papers-explained-review-04-tabular-deep-learning-776db04f965b#932e) | April 2016 | Maps categorical variables into continuous vector spaces through neural network learning, revealing intrinsic properties. |
| [Wide and Deep Learning](https://ritvik19.medium.com/papers-explained-review-04-tabular-deep-learning-776db04f965b#bfdc) | June 2016 | Combines memorization of specific patterns with generalization of similarities. |
| [Deep and Cross Network](https://ritvik19.medium.com/papers-explained-review-04-tabular-deep-learning-776db04f965b#0017) | August 2017 | Combines the  a novel cross network with deep neural networks (DNNs) to efficiently learn feature interactions without manual feature engineering. |
| [Tab Transformer](https://ritvik19.medium.com/papers-explained-review-04-tabular-deep-learning-776db04f965b#48c4) | December 2020 | Employs multi-head attention-based Transformer layers to convert categorical feature embeddings into robust contextual embeddings. |
| [Tabular ResNet](https://ritvik19.medium.com/papers-explained-review-04-tabular-deep-learning-776db04f965b#46af) | June 2021 | An MLP with skip connections. |
| [Feature Tokenizer Transformer](https://ritvik19.medium.com/papers-explained-review-04-tabular-deep-learning-776db04f965b#1ab8) | June 2021 | Transforms all features (categorical and numerical) to embeddings and applies a stack of Transformer layers to the embeddings. |

## Datasets

| Paper | Date | Description |
|---|---|---|
| [Obelics](https://ritvik19.medium.com/papers-explained-179-obelics-idefics-a581f8d909b6) | June 2023 | An open web-scale filtered dataset of interleaved image-text documents comprising 141M web pages, 353M associated images, and 115B text tokens, extracted from CommonCrawl |
| [Dolma](https://ritvik19.medium.com/papers-explained-97-dolma-a656169269cb) | January 2024 | An open corpus of three trillion tokens designed to support language model pretraining research. |
| [Aya Dataset](https://ritvik19.medium.com/papers-explained-108-aya-dataset-9e299ac74a19) | Februray 2024 | A human-curated instruction-following dataset that spans 65 languages, created to bridge the language gap in datasets for natural language processing. |
| [WebSight](https://ritvik19.medium.com/papers-explained-177-websight-2905d0e14233) | March 2024 | A synthetic dataset consisting of 2M pairs of HTML codes and their corresponding screenshots, generated through LLMs, aimed to accelerate research for converting a screenshot into a corresponding HTML. |
| [Cosmopedia](https://ritvik19.medium.com/papers-explained-175-cosmopedia-5f7e81c76d14) | March 2024 | Synthetic Data containing over 30M files and 25B tokens, generated by Mixtral-8x7B-Instruct-v0., aimed to reproduce the training data for Phi-1.5. |
| [RewardBench](https://ritvik19.medium.com/papers-explained-226-rewardbench-31c79c15eb52) | March 2024 | A benchmark dataset and code-base designed to evaluate reward models used in RLHF. |
| [Fine Web](https://ritvik19.medium.com/papers-explained-174-fineweb-280bbc08068b) | May 2024 | A large-scale dataset for pretraining LLMs, consisting of 15T tokens, shown to produce better-performing models than other open pretraining datasets. |
| [Cosmopedia v2](https://ritvik19.medium.com/papers-explained-175-cosmopedia-5f7e81c76d14#5bab) | July 2024 | An enhanced version of Cosmopedia, with a lot of emphasis on prompt optimization. |
| [Docmatix](https://ritvik19.medium.com/papers-explained-178-docmatix-9f2731ff1654) | July 2024 | A massive dataset for DocVQA containing 2.4M images, 9.5M question-answer pairs, and 1.3M PDF documents, generated by taking transcriptions from the PDFA OCR dataset and using a Phi-3-small model to generate Q/A pairs.  |
| [Pixmo](https://ritvik19.medium.com/papers-explained-241-pixmo-and-molmo-239d70abebff) | September 2024 | A high-quality dataset of detailed image descriptions collected through speech-based annotations, enabling the creation of more robust and accurate VLMs. |
| [Smol Talk](https://ritvik19.medium.com/papers-explained-176-smol-lm-a166d5f1facc#b5e3) | November 2024 | A synthetic instruction-following dataset comprising 1 million samples, built using a fine-tuned LLM on a diverse range of instruction-following datasets and then generating synthetic conversations using various prompts and instructions to improve instruction following, chat, and reasoning capabilities. |

## LLM Training
| Paper | Date | Description |
|---|---|---|
| [Direct Preference Optimization](https://ritvik19.medium.com/papers-explained-148-direct-preference-optimization-d3e031a41be1) | December 2023 | A stable, performant, and computationally lightweight algorithm that fine-tunes llms to align with human preferences without the need for reinforcement learning, by directly optimizing for the policy best satisfying the preferences with a simple classification objective. |
| [RAFT](https://ritvik19.medium.com/papers-explained-272-raft-5049520bcc26) | March 2024 | A training method that enhances the performance of LLMs for open-book in-domain question answering by training them to ignore irrelevant documents, cite verbatim relevant passages, and promote logical reasoning. |
| [RLHF Workflow](https://ritvik19.medium.com/papers-explained-149-rlhf-workflow-56b4e00019ed) | May 2024 | Provides a detailed recipe for  online iterative RLHF and achieves state-of-the-art performance on various benchmarks using fully open-source datasets. |
| [Magpie](https://ritvik19.medium.com/papers-explained-183-magpie-0603cbdc69c3) | June 2024 | A self-synthesis method that extracts high-quality instruction data at scale by prompting an aligned LLM with left-side templates, generating 4M instructions and their corresponding responses. |
| [Instruction Pre-Training](https://ritvik19.medium.com/papers-explained-184-instruction-pretraining-ee0466f0fd33) | June 2024 | A framework to augment massive raw corpora with instruction-response pairs enabling supervised multitask pretraining of LMs. |
| [Self-Taught Evaluators](https://ritvik19.medium.com/papers-explained-276-self-taught-evaluators-8270905392ed) | August 2024 | An iterative training scheme that uses only synthetically generated preference data, without human annotations, to improve an LLM's ability to judge the quality of model responses by iteratively generating contrasting model outputs, training an LLM-as-a-Judge to produce reasoning traces and judgments, and using the improved predictions in subsequent iterations. |
| [Direct Judgement Preference Optimization](https://ritvik19.medium.com/papers-explained-228-direct-judgement-preference-optimization-6915425402bf) | September 2024 | Proposes learning through preference optimization to enhance the evaluation capabilities of LLM judges which are trained on three approaches: Chain-of-Thought Critique, Standard Judgement, and Response Deduction across various use cases, including single rating, pairwise comparison, and classification. |
| [LongCite](https://ritvik19.medium.com/papers-explained-273-longcite-4800340e51d7) | October 2024 | A system comprising LongBench-Cite benchmark, CoF pipeline for generating cited QA instances, LongCite-45k dataset, and LongCite-8B/9B models trained on this dataset to improve the trustworthiness of long-context LLMs by enabling them to generate responses with fine-grained sentence-level citations. |
| [Thought Preference Optimization](https://ritvik19.medium.com/papers-explained-274-thought-preference-optimization-4f365380ae74) | October 2024 | Iteratively trains LLMs to generate useful "thoughts" that improve response quality by prompting the model to produce thought-response pairs, scoring the responses with a judge model, creating preference pairs from the highest and lowest-scoring responses and their associated thoughts, and then using these pairs with DPO or IRPO loss to optimize the thought generation process while mitigating judge model length bias through score normalization. |
| [Self-Consistency Preference Optimization](https://ritvik19.medium.com/papers-explained-275-self-consistency-preference-optimization-ccd08f5acafb) | November 2024 | An unsupervised iterative training method for LLMs that leverages the concept of self-consistency to create preference pairs by selecting the most consistent response as the chosen response and the least consistent one as the rejected response, and then optimizes a weighted loss function that prioritizes pairs with larger vote margins, reflecting the model's confidence in the preference. |

## Miscellaneous

| Paper | Date | Description |
|---|---|---|
| [ColD Fusion](https://ritvik19.medium.com/papers-explained-32-cold-fusion-452f33101a91) | December 2022 | A method enabling the benefits of multitask learning through distributed computation without data sharing and improving model performance. |
| [Are Emergent Abilities of Large Language Models a Mirage?](https://ritvik19.medium.com/papers-explained-are-emergent-abilities-of-large-language-models-a-mirage-4160cf0e44cb) | April 2023 | This paper presents an alternative explanation for emergent abilities, i.e. emergent abilities are created by the researcher’s choice of metrics, not fundamental changes in model family behaviour on specific tasks with scale. |
| [Scaling Data-Constrained Language Models](https://ritvik19.medium.com/papers-explained-85-scaling-data-constrained-language-models-2a4c18bcc7d3) | May 2023 | This study investigates scaling language models in data-constrained regimes. |
| [RAGAS](https://ritvik19.medium.com/papers-explained-227-ragas-4594fc4d96b9) | September 2023 | A framework for reference-free evaluation of RAG systems, assessing the retrieval system's ability to find relevant context, the LLM's faithfulness in using that context, and the overall quality of the generated response.  |
| [DSPy](https://ritvik19.medium.com/papers-explained-135-dspy-fe8af7e35091) | October 2023 | A programming model that abstracts LM pipelines as text transformation graphs, i.e. imperative computation graphs where LMs are invoked through declarative modules, optimizing their use through a structured framework of signatures, modules, and teleprompters to automate and enhance text transformation tasks. |
| [An In-depth Look at Gemini's Language Abilities](https://ritvik19.medium.com/papers-explained-81-an-in-depth-look-at-geminis-language-abilities-540ca9046d8e) | December 2023 | A third-party, objective comparison of the abilities of the OpenAI GPT and Google Gemini models with reproducible code and fully transparent results. |
| [STORM](https://ritvik19.medium.com/papers-explained-242-storm-2c55270d3150) | February 2024 | A writing system that addresses the prewriting stage of long-form article generation by researching diverse perspectives, simulating multi-perspective question-asking, and curating information to create an outline, ultimately leading to more organized and comprehensive articles compared to baseline methods. |
| [PromptWizard](https://ritvik19.medium.com/papers-explained-262-promptwizard-228568783085) | May 2024 | A  framework that leverages LLMs to iteratively synthesize and refine prompts tailored to specific tasks by optimizing both prompt instructions and in-context examples, maximizing model performance. |
| [LearnLM Tutor](https://ritvik19.medium.com/papers-explained-279-learnlm-tutor-77503db05415) | May 2024 | A text-based gen AI tutor based on Gemini 1.0, further fine- tuned for 1:1 conversational tutoring with improved education-related capabilities over a prompt tuned Gemini 1.0. |
| [Monte Carlo Tree Self-refine](https://ritvik19.medium.com/papers-explained-167-monte-carlo-tree-self-refine-79bffb070c1a) | June 2024 | Integrates LLMs with Monte Carlo Tree Search to enhance performance in complex mathematical reasoning tasks, leveraging systematic exploration and heuristic self-refine mechanisms to improve decision-making frameworks. |
| [Proofread](https://ritvik19.medium.com/papers-explained-189-proofread-4e1fe4eccf01) | June 2024 | A Gboard feature powered by a server-side LLM, enabling seamless sentence-level and paragraph-level corrections with a single tap. |
| [CriticGPT](https://ritvik19.medium.com/papers-explained-224-criticgpt-6d9af57451fa) | June 2024 | A model based on GPT-4 trained with RLHF to catch errors in ChatGPT's code output, accepts a question-answer pair as input and outputs a structured critique that highlights potential problems in the answer.  |
| [Gemma APS](https://ritvik19.medium.com/papers-explained-244-gemma-aps-8fac1838b9ef) | June 2024 | Proposes a scalable, yet accurate, proposition segmentation model by modeling Proposition segmentation as a supervised task by training LLMs on existing annotated datasets. |
| [ShieldGemma](https://ritvik19.medium.com/papers-explained-243-shieldgemma-d779fd66ee3e) | July 2024 | A comprehensive suite of LLM-based safety content moderation models ranging from 2B to 27B parameters built upon Gemma2 that provide predictions of safety risks across key harm types (sexually explicit, dangerous content, harassment, hate speech) in both user input and LLM-generated output. |
| [Spreadsheet LLM](https://ritvik19.medium.com/papers-explained-271-spreadsheet-llm-25b9d70f06e3) | July 2024 | An efficient encoding method that utilizes SheetCompressor, a framework comprising structural anchor based compression, inverse index translation, and data format aware aggregation, to effectively compress spreadsheets for LLMs, and Chain of Spreadsheet for spreadsheet understanding and spreadsheet QA task. |
| [OmniParser](https://ritvik19.medium.com/papers-explained-259-omniparser-2e895f6f2c15) | August 2024 | A method for parsing user interface screenshots into structured elements, enhancing the ability of GPT-4V to generate actions grounded in the interface by accurately identifying interactable icons and understanding element semantics. |
| [Reader-LM](https://ritvik19.medium.com/papers-explained-221-reader-lm-7382b9eb6ed9) | September 2024 | Small multilingual models specifically trained to generate clean markdown directly from noisy raw HTML, with a context length of up to 256K tokens. | 
| [DataGemma](https://ritvik19.medium.com/papers-explained-212-datagemma-cf0d2f40d867) | September 2024 | A set of models that aims to reduce hallucinations in LLMs by grounding them in the factual data of Google's Data Commons, allowing users to ask questions in natural language and receive responses based on verified information from trusted sources. |
| [GSM-Symbolic](https://ritvik19.medium.com/papers-explained-260-gsm-symbolic-759d379052c7) | October 2024 | Investigates the true mathematical reasoning capabilities of LLMs by introducing GSM-Symbolic, a new benchmark based on symbolic templates, revealing that LLMs exhibit inconsistent performance, struggle with complex questions, and appear to rely on pattern recognition rather than genuine logical reasoning. |

## Auto Encoders

| Model |
|---|
| [Auto Encoders](https://ritvik19.medium.com/papers-explained-review-11-auto-encoders-3b8f08b4eac0#b8a0) |
| [Sparse Auto Encoders](https://ritvik19.medium.com/papers-explained-review-11-auto-encoders-3b8f08b4eac0#f605) |
| [K Sparse Auto Encoders](https://ritvik19.medium.com/papers-explained-review-11-auto-encoders-3b8f08b4eac0#23b0) |
| [Contractive Auto Encoders](https://ritvik19.medium.com/papers-explained-review-11-auto-encoders-3b8f08b4eac0#23b3) |
| [Convolutional Auto Encoders](https://ritvik19.medium.com/papers-explained-review-11-auto-encoders-3b8f08b4eac0#59a1) |
| [Sequence to Sequence Auto Encoders](https://ritvik19.medium.com/papers-explained-review-11-auto-encoders-3b8f08b4eac0#73e0) |
| [Denoising Auto Encoders](https://ritvik19.medium.com/papers-explained-review-11-auto-encoders-3b8f08b4eac0#1829) |
| [Variational Auto Encoders](https://ritvik19.medium.com/papers-explained-review-11-auto-encoders-3b8f08b4eac0#a626) |
| [Masked Auto Encoders](https://ritvik19.medium.com/papers-explained-review-11-auto-encoders-3b8f08b4eac0#2247) |

## Neural Network Layers

### Convolution Layers

| Layer |
|---|
| [Convolution Layer](https://ritvik19.medium.com/papers-explained-review-07-convolution-layers-c083e7410cd3#4176) |
| [Separable Convolution](https://ritvik19.medium.com/papers-explained-review-07-convolution-layers-c083e7410cd3#539f) |
| [Pointwise Convolution](https://ritvik19.medium.com/papers-explained-review-07-convolution-layers-c083e7410cd3#8f24) |
| [Depthwise Convolution](https://ritvik19.medium.com/papers-explained-review-07-convolution-layers-c083e7410cd3#20e4) |
| [Convolution Transpose](https://ritvik19.medium.com/papers-explained-review-07-convolution-layers-c083e7410cd3#a302) |

### Recurrent Layers

| Layer |
|---|
| [Simple Recurrent](https://ritvik19.medium.com/papers-explained-review-08-recurrent-layers-ff2f224af059#e405) |
| [LSTM](https://ritvik19.medium.com/papers-explained-review-08-recurrent-layers-ff2f224af059#0947) |
| [GRU](https://ritvik19.medium.com/papers-explained-review-08-recurrent-layers-ff2f224af059#4571) |

### Attention Layers

| Layer |
|---|
| [Scaled Dot Product Attention](https://ritvik19.medium.com/papers-explained-review-09-attention-layers-beeef323e7f5#c18c) |
| [Multi Head Attention](https://ritvik19.medium.com/papers-explained-review-09-attention-layers-beeef323e7f5#be63) |
| [Cross Attention](https://ritvik19.medium.com/papers-explained-review-09-attention-layers-beeef323e7f5#0f28) |
| [Causal Attention](https://ritvik19.medium.com/papers-explained-review-09-attention-layers-beeef323e7f5#14c7) |
| [Sliding Window Attention](https://ritvik19.medium.com/papers-explained-review-09-attention-layers-beeef323e7f5#324c) |
| [Multi Query Attention](https://ritvik19.medium.com/papers-explained-review-09-attention-layers-beeef323e7f5#0bfd) |
| [Grouped Query Attention](https://ritvik19.medium.com/papers-explained-review-09-attention-layers-beeef323e7f5#d5fb) |

### Normalisation Layers

| Layer | 
|---|
| [Batch Normalisation](https://ritvik19.medium.com/papers-explained-review-10-normalization-layers-56b556c9646e#00ea) |
| [Layer Normalisation](https://ritvik19.medium.com/papers-explained-review-10-normalization-layers-56b556c9646e#9439) |
| [Instance Normalisation](https://ritvik19.medium.com/papers-explained-review-10-normalization-layers-56b556c9646e#7783) |
| [Group Normalisation](https://ritvik19.medium.com/papers-explained-review-10-normalization-layers-56b556c9646e#cd7f) |
| [Weight Standardisation](https://ritvik19.medium.com/papers-explained-review-10-normalization-layers-56b556c9646e#3944) |
| [Batch Channel Normalisation](https://ritvik19.medium.com/papers-explained-review-10-normalization-layers-56b556c9646e#3944) |

---

## Literature Reviewed
- [Convolutional Neural Networks](https://medium.com/dair-ai/papers-explained-review-01-convolutional-neural-networks-78aeff61dcb3)
- [Layout Transformers](https://medium.com/dair-ai/papers-explained-review-02-layout-transformers-b2d165c94ad5)
- [Region-based Convolutional Neural Networks](https://medium.com/dair-ai/papers-explained-review-03-rcnns-42c0a3974493)
- [Tabular Deep Learning](https://medium.com/dair-ai/papers-explained-review-04-tabular-deep-learning-776db04f965b)
- [Generative Adversarial Networks](https://ritvik19.medium.com/papers-explained-review-05-generative-adversarial-networks-bbb51b160d5e)
- [Parameter Efficient Fine Tuning](https://ritvik19.medium.com/papers-explained-review-06-parameter-efficient-finetuning-6934fafa74e5)
- [Convolution Layers](https://ritvik19.medium.com/papers-explained-review-07-convolution-layers-c083e7410cd3)
- [Recurrent Layers](https://ritvik19.medium.com/papers-explained-review-08-recurrent-layers-ff2f224af059)
- [Attention Layers](https://ritvik19.medium.com/papers-explained-review-09-attention-layers-beeef323e7f5)
- [Normalisation Layers](https://ritvik19.medium.com/papers-explained-review-10-normalization-layers-56b556c9646e)
- [Auto Encoders](https://ritvik19.medium.com/papers-explained-review-11-auto-encoders-3b8f08b4eac0)
- [LLMs for Maths](https://ritvik19.medium.com/papers-explained-review-12-llms-for-maths-1597e3c7251c)

## Reading Lists
- [Language Models](https://ritvik19.medium.com/list/language-models-11b008ddc292)
- [Encoder Only Language Transformers](https://ritvik19.medium.com/list/encoderonly-language-transformers-0f2ff06e0309)
- [Decoder Only Language Transformers](https://ritvik19.medium.com/list/decoderonly-language-transformers-5448110c6046)
- [Language Models for Retrieval](https://ritvik19.medium.com/list/language-models-for-retrieval-3b6e14887105)
- [Small LLMs](https://ritvik19.medium.com/list/small-llms-41124d5c7c80)
- [LLMs for Code](https://ritvik19.medium.com/list/llms-for-code-e5360a1b353a)
- [GPT Models](https://ritvik19.medium.com/list/gpt-models-fa2cc801d840)
- [LLaMA Models](https://ritvik19.medium.com/list/llama-models-5b8ea07308cb)
- [Gemini / Gemma Models](https://ritvik19.medium.com/list/gemini-gemma-models-4cb7dfc50d42)
- [Wizard Models](https://ritvik19.medium.com/list/wizard-models-9b972e860683)
- [Orca Series](https://ritvik19.medium.com/list/orca-series-1c87367458fe)
- [BLIP Series](https://ritvik19.medium.com/list/blip-series-4b0831017c5b)
- [LLM Lingua Series](https://ritvik19.medium.com/list/llm-lingua-series-2f61b47d0343)
- [Multi Task Language Models](https://ritvik19.medium.com/list/multi-task-language-models-e6a2a1e517e6)
- [Layout Aware Transformers](https://ritvik19.medium.com/list/layout-transformers-1ce4f291a9f0)
- [Retrieval and Representation Learning](https://ritvik19.medium.com/list/retrieval-and-representation-learning-bcd23de0bd8e)
- [LLM Evaluation](https://ritvik19.medium.com/list/llm-evaluation-a011ddd1a546)
- [Vision Transformers](https://ritvik19.medium.com/list/vision-transformers-61e6836230f1)
- [Multi Modal Transformers](https://ritvik19.medium.com/list/multi-modal-transformers-67453f215ecf)
- [Convolutional Neural Networks](https://ritvik19.medium.com/list/convolutional-neural-networks-5b875ce3b689)
- [Object Detection](https://ritvik19.medium.com/list/object-detection-bd9e6e21ca3e)
- [Region Based Convolutional Neural Networks](https://ritvik19.medium.com/list/rcnns-b51467f53dc9)
- [Document Information Processing](https://ritvik19.medium.com/list/document-information-processing-3cd900a34972)

---
Reach out to [Ritvik](https://twitter.com/RitvikRastogi19) or [Elvis](https://twitter.com/omarsar0) if you have any questions.

If you are interested to contribute, feel free to open a PR.

[Join our Discord](https://discord.gg/SKgkVT8BGJ)
