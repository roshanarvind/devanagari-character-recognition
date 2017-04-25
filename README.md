# Devanagari (Script) Character Recognition Using Machine Learning

## Introduction
This is a Character Recognition System which I developed for Devanagari Script. The learning model was trained on over 92 thousand images (32x32 pixels) of 46 characters, digits 0 to 9 and consonants “ka” to “gya”. The optimal result, 91% accuracy, was obtained using Random Decision Forest regression algorithm. The source code is available on Github (under GPLv3 license), and the dataset is available on Kaggle. [See links below]

## What is Devanagari?
Devanagari is an Indic script and forms a basis for over 100 languages spoken in India and Nepal including Hindi, Marathi, Sanskrit and Maithili. It comprises of 47 primary alphabets, 14 vowels, and 33 consonants, and 10 digits. In addition, the alphabets are modified when a vowel is added to a consonant. There is no capitalization of alphabets, unlike Latin languages.

## What is Machine Learning?
Machine learning is a practical approach for Artificial Intelligence. It uses concepts of Statistics, Probability, Data Science, Computer Algorithms, and Programming. The goal of a machine learning model is to make predictions using data. It is one of the most exciting fields in academic and industrial research.
Machine Learning finds various applications in
1. Driverless cars (Google, Tesla)
2. Digital Assistants (OK Google, Siri, Cortana)
3. Recommendation systems (Amazon, Netflix)
4. Spam/Fraud detection (Email, Payment Gateways)
5. Computer vision (OCR, Image Transcription)
6. Various other automation

## What is Character Recognition?
Character Recognition is the identification of printed characters from an image, a book, a handwritten note, cheques, or letters. It is similar to using a handheld scanner to read a barcode, or reading OMR exam sheets, but it can distinguish between different letters.

## [Technical] Project Walkthrough
### Part 1
Created a CSV file for the complete dataset (about 92,000 images).
Created sample datasets containing one-half, one-third, and one-tenth data.

### Part 2
Created a model using one-tenth dataset, with Random Decision Forest classification algorithm, 64 and 128 trees.
Accuracy (64 trees) - 23%
Accuracy (128 trees) - 23%

### Part 3
Created a model using one-tenth dataset, with Multi-Layer Perceptron classification algorithm.
Accuracy - 28%

### Part 4
Created a model using one-tenth dataset, with Random Decision Forest regression algorithm, 64 and 128 trees.
Accuracy (64 trees) - 44%
Accuracy (128 trees) - 45%

### Part 5
Created a model using one-third dataset, with Random Decision Forest regression algorithm, 64 and 128 trees.
Accuracy (64 trees) - 66%
Accuracy (128 trees) - 67%

### Part 6
Created a model using the whole dataset, with Random Decision Forest regression algorithm, 64 and 128 trees.
Accuracy (64 trees) - 89%
Accuracy (128 trees) - 91%

## Conclusions
The regression models perform surprisingly well compared to classifier models. The reason is that there are too many classes, 46 precisely. The accuracy score of above 90% is satisfactory for most cases, and comparable to best systems in the world. I have performed a grid search to find the optimizing parameter, however, the objective of this study is to find how best results can be obtained and not to find the best result.
Convolution Neural Networks are basically a variation of Multi-Layer Perceptron, and although it may give a better result, neural networks are computationally very expensive and such a study was outside the scope.

## What's next!
I intend to expand the study by creating or obtaining, the complete dataset, vowels are missing right now. The complete model will then be used to create an application which can read any language in Devanagari script from a book or a handwritten note.

## References
The dataset was originally created by Computer Vision Research Group, Nepal. In a similar study, a student from Kathmandu, Subhigya Nepal used Neural Network on the digits classes, 0 to 9, obtaining an accuracy of 95% (unverified).

## Getting Involved
The code, as well as the dataset, is available freely, under GNU GPLv3, and all further development will remain free. You may use the dataset to build your own models or use the existing models to improve it, on the condition that you also keep it free (GPLv3 clause).

## External Links
Github Source Repository - https://github.com/rishianand9/devanagari-character-recognition
Kaggle Database Repository - https://www.kaggle.com/rishianand/devanagari-character-set
Computer Vision Research Group - [website archive] (https://web.archive.org/web/20160105230017/http://cvresearchnepal.com/wordpress/dhcd/)
Subhigya Nepal - [blog] (http://www.thelacunablog.com/)

## Contact
Email ID - rishianand54@gmail.com

