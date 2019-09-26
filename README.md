#  NER-Evaluation README

## How to run
First of all to make it run faster you can enable the GPU runtime.

In order to replicate the results you must enable Google Drive in your Coolab and upload the file `expanded.txt`. Make sure tu pass your drive path in `load_data(<your_path>)` function.

## Results

**Spacy:**
TP: 2572 
TN: 0 
FP: 232 
FN: 463,
Acc: 0.7872666054484236

**Polyglot**
TP: 1736 
TN: 0 
FP: 181 
FN: 1299
Acc: 0.5398009950248757

**Pavlov**
TP: 2762 
TN: 0 
FP: 120 
FN: 273,
Acc: 0.875435816164817

