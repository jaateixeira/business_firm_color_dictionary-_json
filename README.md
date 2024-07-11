# business_firm_color_dictionary_json
A dictionary of colors associated with business firms

For example: 
* IBM is $\textsf{\textcolor{blue}{darkblue}}$
* Nvidia is $\textsf{\textcolor{limegreen}{limegreen}}$
* RedHat is $\textsf{\textcolor{red}{red}}$


# Content 

- The content is a key-value dictionary according to the JSON spec— A very friendly format for Python or JavaScript. 

- Keys are firm names as "Textual Strings" in Unicode to map the JSON spec (http://www.ietf.org/rfc/rfc4627.txt) -- "JSON text SHALL be encoded in Unicode". 
Values are colours accepted by MatplotLib (see https://matplotlib.org/stable/users/explain/colors/colors.html). Those can be X11/CSS4 and xkcd colors, RGB tuples among many other ways of specifying colors. 

Sample from the firm_color_dict.json file containing the dictionary 
```
{"google": "red", "nvidia": "limegreen", "intel": "lightblue", "amd": "black", "arm": "steelblue", "amazon": "orange", "ibm": "darkblue", "linaro": "pink", "bytedance": "gray"} 
```

# How to use it

First close the repository 
```
git clone https://github.com/jaateixeira/business_firm_color_dictionary_json.git
```
Simply load the file using a json api 

## How to us it as a dictionary associating firms to colors in python 



### First, clone the repository into your working directory 

### Second, load it using the following code 


# How to contribute / expand business_firm_color_dictionary_json


