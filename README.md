# Readme info:

Version: 1.5.0 <br/>
Authors: Keith Sterling <br/>
Date: 12th December 2017 <br/>

### What's new in 1.5
This version sees a huge increase in the number of categories, adding an additional 45K to the Y-Bot bain
Also in this release sees the socket bot client first major outing and updates to the get/set nodes to support multi 
threading and multi client support, fixing an issue in the sanic rest client along the way
Finally this release also sees the webchat client get multi user support through the use of session cookies

### What's New in 1.4
The next stage of refactoring sees defaults.aiml and personality.aiml refactored out into specific files grouped around 
topics, subjects and patterns.
In the same way that 1.3 introduced a easier way to manage reductions, 1.4 introduces the same easy way to manage actual 
responses.
Subsequent point releases will see this refactoring continue.

### What's New in 1.3
1.3 saw the compete refactoring of the reductions AIML files. These contained over 27K lines of AIML, making
it almost impossible to edit and maintain. This releases breaks these files into subject specific files.
Further releases will see the refactoring continue in more detail

### What's New in 1.2
* RDF Engine completely rewritten to be fully compatible with Alice grammar
* Refactored Y-Bot triples.txt into more understandable and workable files based on category
* New RDF Formatter  tool in utils 
* Updated use of file handling to open all but neccassary files in readonly mode
* Conversations now persistent between bot restarts
 
### What's New in 1.1
* CSV Output.
* Default Variables

# Introduction

Program Y is an AIML interpretor written in Python. It includes an entire Python 3 framework for building you own chat bots using
Artificial Intelligence Markup Language, or AIML for short. 

Programy-Y is fully cross plaform, running on 

* Mac OSX
* Linux
* Windows

100% Support for all AIML 2.0 Tags plus all Pandora bot ones they never documented

* Full support for al AIML 2.0 Tags
* RDF Support through addtriple, deletetriple, select, uniq and uniq
* List processing with First and Rest
* Advanced learn support including resetlearn and resetlearnf
* Full Out Of Band Support
* Full embedded XML/HTML Support
* Dynamic Sets, Maps and Variables

Program Y is extremely extensible, you can

* Add you own AIML tags
* Add you own Spelling Checker
* Support User Authorisation
* Support User Authentication
* Add your own Out Out Band (OOB) tags
* Add Dynamic Sets in Python
* Add Dynamic Maps in Python
* Add Dynamic Variables in Python
* Run a variety of clients, including
  * Console
  * REST
  * Web Chat
  * Twitter
  * Google Hangouts (XMPP)
  * SMS ( coming soon )
  * Facebook ( coming )
  * Slack ( coming soon )

Program-Y comes with a base set of grammars for various industry sectors, including

* Energy Industry
* Banking
* Telecoms
* Weather
* Surveys
* News Feeds
* Maps


# System Requirements

Program Y is built using Python 3.6 and has dependencies upon the following Python libraries

* requests
* flask
* python-dateutil
* beautifulsoup4
* lxml
* wikipedia
* pylint
* nose
* coverage
* pyyaml
* tweepy
* sleekxmpp

In addition, there are a number of additional libraries for use with Sanic version of the REST server, specifically

* sanic

# Using Program-Y

Full documentation is available on [Program Y Wiki](https://github.com/keiffster/program-y/wiki)

After installation from the Github repository you can chat with your Program Y by running one of the many bots found in the 
\bot folder. These include

* Y-Bot - My own bot under development
* Professor - A huge knowledge base of questions and answers
* Alice2 - AIML 2 version of the famous Alice chat bot
* Roise - An AIML base set of grammars for creating your own bot

See the individual folders for unix and windows scripts required to run a bot.

# Tutorial

Once you have got the system installed and have run one or more of the bots, head over to the [Tutorial](https://github.com/keiffster/program-y/wiki/AIML-Tutorial) on the Wiki for a full 
run down of everything possible in AIML





