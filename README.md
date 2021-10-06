<p align="center">
  <img  src="https://user-images.githubusercontent.com/31209617/48580549-8816a200-e945-11e8-8814-7e927f7d21d7.png" />
</p>
<h1>
<p align="center"><b>CANTEEN MANAGEMENT SYSTEM</b></p>
</h1>

Developed using C++, this project can be used for digitisation of small scale canteens. It provides 10+ features like Register/Login Dashboard, Add, Search, Display, Modify & Delete Product details, Billing,
Displaying Invoice with TAX/GST included. MySQL Database is used in backend. You can also use .csv file for simple execution of the program. 


## Program Demo



## Features 

* Register.
* Login.
* Add Customers.
* Add Products.
* Customers and products search.
* Display Customer. 
* Display Product.
* Modify Customer Details.
* Modify Product Details.
* Delete Customer.
* Delete Product.
* Billing Option.
* Display Invoice. 

## Installation

You must have a C++ compiler like GCC, Visual C++, etc. already installed in your system. If you don’t have any, you can easily get them by searching on Google.

For ease, use Code::Blocks IDE


### MySQL setup in Code::Blocks.

**Follow the steps to include the mysql header and connect to mysql server.**


*  Go to https://www.dropbox.com/s/40h26grtqsggwrg/mysqlheaders.rar?dl=0&file_subpath=%2Fmysqlheaders and download 
      the header file.
* Download libmysql.a from https://www.dropbox.com/s/xj3it1pkhu2wb3h/libmysql.a.zip?dl=0
      
* Download libmysql.dll from https://www.dropbox.com/s/nktlkafhmez7c1o/libmysql.dll.zip?dl=0
      
Note: - You have to unzip the downloaded files to get above mention files.
*  Now go to C:\Program Files (x86)\CodeBlocks\MinGW\include  and paste the header files here (excluding libmysql.a and libmysql.dll).
*  Go to C:\Program Files (x86)\CodeBlocks\MinGW\lib  and paste libmysql.a file here.
*  Go to codeblocks --> file -->new -->project -->console application -->go --> and fill all the required fields.
*  Now go to your project folder --> bin --> debug --> add libmysql.dll here.
*  Copy all the codes of project and paste it in main.cpp of your project folder.
* Go to the setting tab of CodeBlocks --> compiler --> linker setting --> add --> 
     C:\Program Files (x86)\CodeBlocks\MinGW\lib\libmysql.a
* Now go to CodeBlocks --> setting -->compiler --> search directories --> add -->
     C:\Program Files (x86)\CodeBlocks\MinGW\include
*  Download XAMPP software and install it.
* Run the XAMPP control panel as an administrator.
* Start the apache server first and then mysql server.
* Click admin button.
*  Your default browser will be open and you can see the database there. i.e localhost/phpmyadmin/
*  Now you are good to go.

## Usage

```cpp
gcc main.cpp
```
#### For using .csv as backend

```cpp
gcc csvmain.cpp
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
