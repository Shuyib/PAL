# PAL - Program Aided Language Model (PAL)
Using streamlit, openai 'text-davinci-003' and Langchain to create a program aided language model. They are achieve state of the art results on math word problems. This project is a proof of concept to see if we can make an application to help people with their math problems by using a language model to help them understand the problem better.   

Use an LLM -> decompose the problem into runnable steps -> run program in PY IDE -> return results to user.   

Learn more by reading the [paper](https://arxiv.org/pdf/2211.10435.pdf) or visiting the [website](https://reasonwithpal.com/).   

## Installation
To install requirements, make a virtual environment and run:
```bash
make venv/bin/activate

# activate the virtual environment
source venv/bin/activate

make install
```

## Usage
To run the app, make sure you are in the virtual environment and run:
```bash
make run
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. 

## License
[Apache 2.0](https://github.com/Shuyib/PAL/blob/main/LICENSE)
