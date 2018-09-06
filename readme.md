# DSC FUNAAB website members list

Members list for the dsc funaab website

## Getting Started

This repository contains the list of all members of DSC FUNAAB . In order to add your name to the list you must follow the instructions below carefully . If you make a mistake and mess the list up , this is git , we will catch you and deal with you ( Lol just kidding ) . Seriously though , please do not mess anything up .

### Prerequisites

1. Basic knowedge of json syntax . Not needed though , if you follow the instructions carefully , you would do fine .

2. Basic knowledge of git .


### !!!! INSTRUCTIONS !!!

Alright , so firstly you would have to fork this repository . After doing that , you edit the members-list.json file as such ;

The file contains a json object which houses the information of the members . You should see something like this 

```
{
	   "Ademola Abisayo Paul":{
	   	  "name": "Ademola Abisayo Paul",
	      "twitter":"sayo_paul",
	      "github":"sayopaul"
	   }
 }
```

To add your name , use the following template and fill in your information appropriately . Please do note that you must put a comma before the previous entry before you put your own . For example , this is wrong

```
{
	   "Ademola Abisayo Paul":{
	   	  "name": "Ademola Abisayo Paul",
	      "twitter":"sayo_paul",
	      "github":"sayopaul"
	   } //notice that there is no comma here 
	   "Your Name Here":{
	   	"name":"Your full name here",
		"twitter":"your twitter handle/username here",
		"github":"your github username here"
		}
}
```

and this on the other hand is correct
```
{
	   "Ademola Abisayo Paul":{
	      "twitter":"sayo_paul",
	      "github":"sayopaul"
	   },
	   "Your Name Here":{
	   	"name":"Your full name here",
		"twitter":"your twitter handle/username here",
		"github":"your github username here"
		}
	  
}
```

 When you are done , submit a pull request and we'll merge if you did it right .
 
 I would say good luck , but since we are FUNAABites , permit me to say ;
 
 
 All the very best for you oo
 
 If you don't understand anything here , ask on the group or search Google ( it's how we all learn new stuff ) .
