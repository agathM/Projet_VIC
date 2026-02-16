# Unsupervised Texture Segmentation using Wavelet Transform

This project aims at replicate and compare solutions from the litterature to the problem of unsupervised texture segmentation

The repository is organised as follow :
```
\-- data
    \-- homemade                # homemade textures mix
    \-- PASTIS_small            # subset of PASTIS dataset
    \-- Prague_Colour_small     # small synthetic colour dataset from Prague generator
    \-- Prague_Grayscal_small   # same but grayscale
    \-- segmentation            # segmentation results
+-- Co-occurences.ipynb         # Co-occurence matrix method
+-- homemade_data_generator.ipynb
+-- neutrosophic_set_wv.ipynb   # Neutrosophic set method
+-- Unser_1995.ipynb            # Unser method
```

To get the necessary libraries (in Python 3.12.8)
```
pip install requirements.txt
```