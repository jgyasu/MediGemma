# MediGemma

This paper did not have any code associated or results to reproduce. It presented a benchmark
and further instruction prompt tuned Flan-PaLM model to create Med-PaLM.
PaLM models are old generation closed-source models so to prove my coding proficiency, I
fine-tuned Google's Gemma on the MedQuad dataset consisting of 16000+ medical questions
and answers. Limited by the computing resource, I fine-tuned it using LoRa on 2000 questions
and answers. The notebook used for fine-tuning is present in the repository which I further plan
to share on Hugging Face so that it can be referenced as an API.