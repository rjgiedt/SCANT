# SCANT
Computer algorithms associated with analysis and processing of data for the SCANT method.

# Project Abstract
Serial tissue sampling has become essential in guiding modern targeted and
personalized cancer treatments. An alternative to image guided core biopsies are fine
needle aspirates (FNA) that yield cells rather than tissues but are much better tolerated
and have lower complication rates. The efficient pathway analysis of such cells in the
clinic has been difficult, time consuming and costly. Here we developed an antibody-
DNA barcoding approach where harvested cells can be rapidly re-stained through the
use of custom designed oligonucleotide-fluorophore conjugates. We show that this
approach can be used to interrogate drug-relevant pathways in scant clinical samples.
Using the PI3K/PTEN/CDK4/6 pathways in breast cancer as an example, we
demonstrate how analysis can be performed in tandem with trial enrollment and can
evaluate downstream signaling following therapeutic inhibition. This approach should
allow more widespread use of scant single cell material in clinical samples.

# Code Explanation
Key components of this project included computational methods for 1. Segmenting individual cells
from fine needle aspirates, 2. Classifying cells from fine needle aspirates as either host or tumor cells, 
and 3. Creation of a training data set for classification of these cells. Included here are python notebooks
illustrating in a step-by-step manner, how computational analysis was completed for these goals. 

# Required Python packages
To run this code, Keras/Tensorflow backend, Pandas, scikit-learn, scikit-image, OpenCV, and pillow are required. 

