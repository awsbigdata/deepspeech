# deepspeech
how to infer speech to text using opensource model 


1.Download the model 
wget https://github.com/mozilla/DeepSpeech/releases/download/v0.5.1/deepspeech-0.5.1-models.tar.gz
tar xvfz deepspeech-0.5.1-models.tar.gz
2.download clinet.py and change the path according to yours.

python client.py --model models/output_graph.pbmm --alphabet models/alphabet.txt --lm models/lm.binary --trie models/trie --audio input/

--audio  - folder which contains audio files (16khz only)

