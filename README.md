# NanoCode
gpt2 finetuned for code

## Features
 - code in multiple languages
 - 5GB dataset

## how does it work?

Format inspired by `oasst-pythia-12b` 
```
<human> ... <endOfText>
<Bot> ... <endOfText>
<human> ... <endOfText>
<Bot> ... <endOfText>
```

## whats in the data
 - theblackcat102/evol-codealpaca-v1
 - sahil2801/CodeAlpaca-20k
 - nickrosh/Evol-Instruct-Code-80k-v1
 - jinaai/code_exercises
 - ChrisHayduk/Llama-2-Code-Dataset
 - neural_code_search
 - codeparrot/xlcost-text-to-code
 - Arjun-G-Ravi/Python-codes

#### Limitations 

I did not make the data dumps/corpuses that make up this data, and can't account for any biases. The model is meant for academic research purposes, and isn't meant for any important or high risk scenarios. Do not follow its advice
