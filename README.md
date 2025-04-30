# FilmComposer: LLM-Driven Music Production for Silent Film Clips

[[Paper]](https://arxiv.org/abs/2503.08147) [[Project Page]](https://apple-jun.github.io/FilmComposer.github.io/) [[Dataset]](https://huggingface.co/datasets/apple-jun/MusicPro-7k)

## Dataset
* The MusicPro-7k dataset will be released on [Hugging Face](https://huggingface.co/datasets/apple-jun/MusicPro-7k). Please sign the [MusicPro-7k Terms of Use](https://github.com/Apple-jun/FilmComposer/blob/main/MusicPro-7k_Terms_of_Use.pdf) and send email to `heqi389973717@gmail.com`.

Model coming soon...

## Preparation

* Clone this repo

* Download the training data

* CRT requires Python 3.8, PyTorch 1.9. Install dependencies `pip install -r crt_requirements.txt`

* FilmComposer require Python 3.9, PyTorch 2.1. you first can run the following:
    ```shell
    python -m pip install 'torch==2.1.0'
    python -m pip install setuptools wheel
    python -m pip install -U audiocraft
    sudo apt-get install ffmpeg
    ```
Then install other dependencies by `pip install -r filmcomposer_requirements.txt`

* Obtain your OpenAI api_key and check `agents/config.json`

* To run the agents, you need midi2abc to covert midi file to ABC notation. Please refer to [abcmidi](https://github.com/xlvector/abcmidi).

## Training
coming soon...

## Pipeline
coming soon...
