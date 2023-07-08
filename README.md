# BooleanRetrievalModel
In this project of Information Retrieval, an information retrieval model called Boolean Information Retrieval Model is implemented. There is a collection of 30 documents on which it is implemented. It can handle
a simplified Boolean user query that can only be formed by joining three terms (t1, t2 and t3) with (AND, OR and NOT) Boolean operators. For example, a user query may be of the form (t1 AND t2 AND t3). For positional queries, the query text contains “/” along with a k intended to return
all documents that contains t1 and t2, k words apart on either side of the text. Also GUI is implemented for friendly interface.
It is implemented on jupyter notebook . Following libraries must be installed using :
'pip install lib_name'

from termcolor import colored
import math
import nltk
import math
import re
import string
import numpy as np
from nltk.stem import WordNetLemmatizer
from nltk.stem.snowball import SnowballStemmer
from tqdm import tqdm
