# Social Network Graph

> Representing Instagram users and exploring the connections between them 
> by presenting them in an interactive graph.

The work of many programs and applications is based on the analysis of data 
received from users, as well as on their interactions with each other, which 
allows developers to create a more convenient program that adapts to the user 
according to his preferences, and so on. Our project is a branch of this topic.

Our project aims to analyze connections between users by visualizing them in a 
graph, thus allowing users to see their audience and how it is connected to the 
audience of our friends in the social network. 

We provide opportunities such as:
* finding common acquaintances,
* tracking certain connections,
* increasing socialization.

We present the project as a site where the user will be able to enter a certain 
nickname and trace the user's connections with other people with the help of 
the graph, which will be generated.


![](https://www.how2shout.com/wp-content/uploads/2018/01/Best-open-source-Software-platforms.jpg)


## Instructions
To use the program you need:
1. Select the operating mode
2. Enter the nickname of the certain user (or two users in according to the mode)
3. Wait a few seconds to build a graph

## Structure
* `app.py` - module with application
* `config.py` - module for receiving data to log into an Instagram account
* `data_loader.py` - module for getting data about Instagram users
* `image_processing.py` - module with functions for working with images
* `soc_graph.py` - module with SocialGraph data structure
* `user.py` - module for storing basic information about Instagram users

## Usage example
### Graph of user followers:
![graph_Nick](https://user-images.githubusercontent.com/44781809/118534587-14da8a80-b752-11eb-9a9d-2ac64528b161.png)

### Search for the shortest path between users:
![graph_short](https://user-images.githubusercontent.com/44781809/118534690-30459580-b752-11eb-9d03-3b7a9741c838.png)


## Licence

```
Copyright (c) 2021 Social Network Graph

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
```

<!-- Markdown link & img dfn's -->
[wiki]: https://github.com/yourname/yourproject/wiki/home/
