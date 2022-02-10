# Gramfromer
Gramformer
Human and machine generated text often suffer from grammatical and/or typographical errors. It can be spelling, punctuation, grammatical or word choice errors. Gramformer is a library that exposes 3 seperate interfaces to a family of algorithms to detect, highlight and correct grammar errors. To make sure the corrections and highlights recommended are of high quality, it comes with a quality estimator. You can use Gramformer in one or more areas mentioned under the "use-cases" section below or any other usecase as you see fit. Gramformer stands on the shoulders of giants, it combines some of the top notch researches in grammar correction. Note: It works at sentence levels and has been trained on 64 length sentences, so not (yet) suitable for long prose or paragraphs (stay tuned for upcoming releases)

Fine-tuning for this model is done on relatively smaller models with not-so-much of data due to compute budget constraints. So take the results with a pinch of salt and consider this as a proof-of-concept for novel method for generating grammar error correction dataset. I am working on a version based on a larger base model and lot more data if someone might want to use this in producution setup

Usecases for Gramformer
Area 1: Post-processing machine generated text

Machine-Language generation is becoming mainstream, so will post-processing machine generated text.

Conditioned Text generation output(Text2Text generation).
NMT: Machine Translated output.
ASR or STT: Speech to text output.
HTR: Handwritten text recognition output.
Text Summarisation output.
Image caption output.
Data or key to Text output.
Paraphrase generation output.
Controlled Text generation output(Text generation with PPLM) [TBD].
Free-form text generation output(Text generation)[TBD].
