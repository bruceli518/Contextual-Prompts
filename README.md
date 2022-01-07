# Contextual-Prompts

[General Information]
There are three data files. They are collected from pediatrics, cardivascular and andrology department respectively.
Each row in one data file stands for one patient's diagnosis record. And each data file contains the same columns: 
disease_desc, conversation and disease_label.

[Column Description]
The column 'disease_desc' records the patients' self-described condition.

The column 'conversation' records the doctor-patient conversation happened during the process of diagnosis. The 
words said by patients start with symbol '/pati:', and the words said by doctors begin with '/doct:'. The symbol '&&' is
used to segment the patients' words and doctors' words.

What the clomun 'disease_label' contains is the disease class for the corresponding row. But it is worth to notice that not
every row has label.  


