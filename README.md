Scripts used to convert midi files to something that text-based neural networks can understand, and vice versa.

### How to use
Install [python-midi](https://github.com/vishnubob/python-midi), then flatten midi files with `demidi.py`
```
python3 demidi.py --mididir "/path/to/your/midis" --outdir "/path/to/output"
```

Run `remidi.py` to create a midi file that uses the same syntax
```
python3 --datafile "/path/to/datafile.txt" --outfile "/path/to/outfile.mid"
```

### Samples

[Here are some samples](https://soundcloud.com/user-122134918/sets/ai-generated-music) that were generated by a [textgenrnn](https://github.com/minimaxir/textgenrnn) neural net. It was trained with Undertale/Deltarune music at 20 epochs/6 layers and is bidirectional.
