# Identifying diabetes from fingerprints.

Our objective was to test if the fingerprints excluding the thumb could carries any information regarding the probabilty of diabetes, either type 1 and type 2, to the person being tested. We have used Deep Convolutional Neural Networks and obtained performance metric of prediction on 50 cross validations which revealed the fact that in the 4 finger analyzed there is infact a great deal of embedded information regarding diabetes.<br>
<br>

## Data<br>
The data for this research was collected from hospitals in Romania, by  Nicoleta Dragana, C. Vulpe, L. Guja.<br>
The data is divided into three parts, the first part consists of fingerprints from Non-diabetic patients, the second part consists of fingerprints from Type-1 diabetic patients, and the last part consits of data from Type-2 diabetic patients.

## Artificial Neural Network <br>
In order to find the difference in patterns of fingerprints for Diabetic and Non-diabetic patients, we designed a Convonutional Neural Network and a Residual Neural Network. Out of these two Convonutional Neural Network worked the best.<br>
The code for Convonutional Neural Network is here https://www.github.com/Sid2697/Diabetes_Research/blob/master/Type1VersusHealty.ipynb, and the code for Residual Neural Network is here https://github.com/Sid2697/Diabetes_Research/blob/master/ResNet%20Type1%20Vs.%20Healthy%20.ipynb.

## Publication
The results of successfully identifying Diabetic patients were published with @alexandrudaia in this paper https://www.researchgate.net/publication/324219743_Unexpected_Results_Embedded_Information_in_Fingerprints_Regarding_Diabetes
<br>
Feel free to contribute to the code for increasing the accuracy.

## License

*I'm providing the codes in this repository to you under an open source license*

MIT License

Copyright (c) 2018 Siddhant Bansal

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

