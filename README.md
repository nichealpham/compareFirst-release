# Compare First

<img align="right" src="http://namtech.com.au/wp-content/uploads/2017/04/color-logo.svg" hspace="20" vspace="10" width="320">

A desktop application to automatically crawl data from Compare First and save result to AWS EC2 

* Visit original: [http://www.comparefirst.sg/wap/homeEvent.action](http://www.comparefirst.sg/wap/homeEvent.action)
* Visit database server (available soon): [http://13.228.111.11/api/product/list](http://13.228.111.11/api/product/list)

### Features

* Natively withdraw data from Compare First
* Automatic backup data to Amazon EC2 Server
* Database management with Robo 3T
* Automatic deploy to AWS Code Pipeline with AWS CodeCommit, CodeBuild and CodeDeploy

### Usage

#### Installation

1. Download the `release-*.*.zip` file

2. Extract it into a folder and run the `compareFirst.exe` file

Here is a screen shot of the app:

![Image structure not found](https://github.com/nguyenpham95/compareFirst-release/blob/master/shot/app.PNG)<br/>

#### Actions

To manually search and save data to server, follow these steps:

```sh

+ First: click LOAD PAGE button (right pannel)
+ Second: insert searching criteria into the page (left pannel)
+ Third: click MODIFY SEARCH button on the page (left pannel)
+ Final: review result returned on the page and click SAVE DATA button (right pannel)

```

To automatically search and save data to server, follow these steps:

```sh

+ First: in the PRODUCT GROUP (right pannel), select a GROUP that correspond
to either 1 of the 5 groups in the original page
+ Second: input date to search, from which day to which day (right pannel)
+ Third: Hit START (right pannel) and see the result crawled and migrated to EC2 server
+ Final: Hit STOP (right pannel) at anytime to stop the operation

```

### Contact information

![Image structure not found](http://namtech.com.au/wp-content/uploads/2017/04/color-logo.svg)<br/>

#### N.A.M Technology Company Limited

##### R.802, 8th Floor, Vietnam Business Centre
##### 57-59 Ho Tung Mau Str., Ben Nghe Ward, D.1
##### PHONE: (+84) 862.866.262
##### HOTLINE: (+84) 935.036.896
##### TAX: 0 3 1 3 9 5 9 9 0 1
##### FAX: (+84) 886.885.138
##### EMAIL: john@namtech.com.au
