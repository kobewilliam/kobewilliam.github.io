## Welcome to SustainKG Guide

This system aims to provide a tool for users to create their own concept map. This document can help you learn about the functions used in the system. The system is based on Apache Server and uses Shibboleth module for protecting the users' login information. Please remember to open the UCI VPN to use or develop SustainKG project.

The project urls are below:

SustainKG Projects: https://xxxx.com

Apache and Shibboleth Configuration: https://xxx.com

### Installation of VUE-CLI

Please download Node.js and NPM first, the website is https://nodejs.org/en/

check the version of Node.js and NPM if download successfully

```

node -v

npm -v


```
Install VUE-CLI and check its version using the following commands:

```

npm install -g @vue/cli

vue --version

```
### Set Up Docker Container

For the SustainKG project, the docker container uses Ubuntu as the platform and Apache as the server. At the same time, it uses Shibboleth module to protect the users' login information. The details are here:

https://github.com/kobewilliam/Ubuntu-shibboleth


### Functions

```markdown

#renderGraph()

"""

Input: Concept Map (json format [nodes:[...], links:[...]]) 
Usage: This functions read the json format data to show a concept map in the website canvas. 
       If you would like to learn more about the d3, please check the website of d3-force document.
       When modifications are made for the concept map, this function will be called to update the concept map.
"""


#doubleClick()

"""

Input: info, node, node_name, snippet
Usage: Users can double click the blanket part in the website to create a node and select its name.
       If the name has already existed, the node will not be created. 
       
"""

#submitData()

"""

Usage: Submit the data to the database as the json format.

"""

#mounted()

"""

Usage: Call the functions when the front-end server starts. 


"""

#Search()

"""

Usage: Search the node name from Wikipedia for users to select as the current node name

"""

#handleShow()

"""

Usage: After the user log in the system, it will get the data from the backend and show a concept map to users
       in the front end. 

"""

#selectClear()

"""

Usage: clear all the input variable value for the element.

"""

#change_node_name()

"""

Usage: Change the node name by right clicking the node

"""

#change_link_name()

"""

Usage: Change the link name by right clicking the link

"""

#drag_addLinks()

"""

Usage: Users can make a single click to a node and drag a link to another node to create a link. 

"""

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kobewilliam/kobewilliam.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
