# CS4263 Random Timing

This project takes in a text file of URLs and records the response time of each website. Currently, the script records the response times of the four different implementations of the Random Number Generator website from Project 1 of CS4263/FA19.

## Prerequisites

This project will require access to Python. To install, enter:

```
$ sudo apt-get install python-setuptools python-dev build-essential
```

It will also require the <code>requests</code> library. To install, enter:

```
$ sudo pip install requests
```

At multiple points, you may be asked if you would like to proceed ("Do you want to continue?"). Simply answer "Y" and press enter to continue. If at any point you would like to quit the installation mid-process, enter "CTRL+C".

## Installation

To install, simply open up a terminal and clone the repository from github.

```
$ git clone https://github.com/nullpoynter/CS4263-Random-Timing.git
```

From there, you can run the program with

```
$ python main.py
```

You can modify which URLs are accessed by modifying the file <code>ips.txt</code>. 

Alternatively, you may change the file path in <code>main.py</code> from <code>ips.txt</code> to your own text file of URLs.

## Built With

* Google Cloud Platform

## Authors

* James Marwitz - <a href="https://github.com/marwitz93j">marwitz93j</a>
* Adrienne Poynter - <a href="https://github.com/nullpoynter">nullpoynter</a>
* Devendra Thapa - <a href="https://github.com/thapadevendra">thapadevendra</a>
* Nathan Vanderheiden - <a href="https://github.com/Nathanv97">Nathanv97</a>

## Citations

* PurpleBooth's <a href="https://gist.github.com/PurpleBooth/109311bb0361f32d87a2">README-Template.md</a> 
