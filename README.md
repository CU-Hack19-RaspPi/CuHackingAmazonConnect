# Hacker Pizza Order System - cuHacking 2019
* InGenius CU Hacking Challenge
* By Songmi Wu, Yichen Lian ,Keith Huang, Yiwei Zhang

## Amazon Connect Streams
* Integratre the amazon connect streaming api
* The api can be found here [here](https://github.com/aws/amazon-connect-streams)

## part1 Pizza Phone call Ordering System for customers
![](https://github.com/zywkloo/CuHackingAmazonConnect/raw/master/CallSystemScreenShot.png)
* Please visit https://ottawa.recipes , then call +1 866-846-5640
* Supporing 3 languages including English, French and Chinese.
* The website will display a phone UI.
* All hosts connecting to the amazon instance have to be on https. you should ublock all popups
* This is a HTTPS website, hosted on vultr server 1. repository is here.

## part2 Pizza Phone Call Ordering Monitor for restaurants
![](https://github.com/zywkloo/CuHackingAmazonConnect/raw/master/CallMoniterScreenshot.jpeg)
* Please visit http://hacker-pizza.herokuapp.com , then call +1 877-373-3618. 
* The website will display the result of your order on runtime, only for demoing the mechanisem .(For now just support small pizza or small salade)
* This is a HTTP website using socket.io , hosted on vultr server 2. The part 2 repository is not on git hub.

## Tips:
* You do not need to clone and deploy this repo locally or anywhere else, since most of the logic and source codes are stored on Amazon Lambda, and Amazon Connect. However, we have no approaches to public these source out of the AWS ecosystem for now.
* Supported browse: Chrome only. May have problems with mobile Chrome browser.
