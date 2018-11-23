# Language-translation-with-deep-learning
This project uses deep learning and NLP to translate one language to other.

## Src
This has four code snippets with each with its own functionality
 1. The clean.py is used to clean the given data into readabale form and for further preprocessing.
 2. The spl is used to split the data into tokens with some text processing and NLP.
 3. The modl contains the network and saves the weights as a file named model.h5.
 4. The final part is the eval, which matches the ints to the coresponding words and combines them to a seq of words and returns an output
 as a predicted value.
 
## Dataset.
The dataset I've used can be found in the [German – English deu-eng.zip](http://www.manythings.org/anki/deu-eng.zip)

## Implementation.
```
 python clean.py
 python spl.py
 python modl.py
 python evalnet.py
 
 ```
 ## predicted output.
- src=[tom erblasste], target=[tom turned pale], predicted=[tom went pale].
- src=[bring mich nach hause], target=[take me home], predicted=[let us at].
- src=[ich bin etwas beschwipst], target=[im a bit tipsy], predicted=[i a bit bit].
- src=[das ist eine frucht], target=[its a fruit], predicted=[thats a a].
- src=[ich bin pazifist], target=[im a pacifist], predicted=[im am].
- src=[unser plan ist aufgegangen], target=[our plan worked], predicted=[who is a man].
- src=[hallo tom], target=[hi tom], predicted=[hello tom].
- src=[sei nicht nervos], target=[dont be nervous], predicted=[dont be crazy].
- src=[ich mag dich nicht], target=[i dont like you], predicted=[i dont like you].
- src=[tom stellte eine falle], target=[tom set a trap], predicted=[tom has a cough].

- BLEU-1: 0.082088.
- BLEU-2: 0.006182.
- BLEU-3: 0.046129.
- BLEU-4: 0.076238 .
