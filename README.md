# business_firm_color_dictionary_json
A dictionary of colors associated with business firms

For example: 
* IBM is $\textsf{\textcolor{darkblue}{darkblue}}$
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
Simply load the file using a json api from your favorit programming language 

## How to us it as a dictionary associating firms to colors in python 

``` py
import json

# Read JSON file

with open('business_firm_color_dictionary_json/firm_color_dict.json', 'r') as file:
    firm_color = json.load(file)

# Now, data is a Python dictionary
print(firm_color)

# Print the color value for key ibm 
print(f'\n The color of ibm is {firm_color["ibm"]}')


```

# How to contribute or expand the dictionary 

Please create a new branch for any new feature. Branch or fork, code, test, then pull request. Please follow the basic guide on [https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project). 

Simply edit the json file. I will merge it. 

Jose Teixeira, currently the only maintainer,  will review and merge pull requests, update the ChangeLog.txt, aknowledge the contribuitions and work on documentation on free-time from work. 

# Contributors 
Jose Teixeira

# Maintainers  
Jose Teixeira

# License 
GNU General Public License v3.0




