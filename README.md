svm-embed
=========
    support vector machine for embedded system.

svm_embed is a vector machine simplified for embedded system. In such systems,the computing resource is strictly constrained,like RAM,ROM and Computing. In such embedded systems,sometimes,we wanner do some simple classifications. For example,detecting the imput signal a sine wave or a squre wave. Svm_embed is the right choice. Svm_embed do the training stage off-line,after that we got a training model. Acturally it is a vector indicating the hyper plane. In the final step,it automatically generate a predicting function,which can be used directly in your program.

Usage:
------
The command line -f data 
Here,data stands for the training datasets file. In the later version,some more features will be added in.

Data sets can be any name,the data form is specified as below.

Label:value1:value2:....:valueN 

each line ended up with a 'enter' symbol, except the last line.

Finally,just include the "model.h" file in your program. 
## Reference
[1]Cortes, Corinna, and Vladimir Vapnik. "Support vector machine." Machine learning 20.3 (1995): 273-297.
[2]Suykens, Johan AK, and Joos Vandewalle. "Least squares support vector machine classifiers." Neural processing letters 9.3 (1999): 293-300.
