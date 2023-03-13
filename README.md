# Image Caption Generator

This is a deep learning project that generates textual descriptions of images. The model is trained using the [Flickr8k dataset](https://forms.illinois.edu/sec/1713398)  and uses the InceptionV3 architecture to extract features from input images, which are then fed into a long short-term memory (LSTM) network to generate captions.
## Requirements
- Python 3.7 or higher
- TensorFlow 2.x
- NumPy
- Pandas
- Pillow
- Matplotlib
- NLTK
- Jupyter Notebook

You can install these dependencies using the following command:

```bash
pip install -r requirements.txt
```


## Running the Notebook 
1. Download the [Flickr8k dataset](https://forms.illinois.edu/sec/1713398)  and extract the files to a directory named `Flickr8k`. 
2. Open a terminal and navigate to the directory where the Jupyter notebook file is located. 
3. Run the following command to start Jupyter Notebook:

```bash
jupyter notebook
``` 
4. In your web browser, open the `Caption_Generator.ipynb` file. 
5. Follow the instructions in the notebook to train the model and generate captions for input images.
## Want to Contribute?

If you find a bug or would like to suggest a new feature, please feel free to open an issue or submit a pull request.
## License

This project is licensed under the MIT License
