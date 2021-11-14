# CNS150

# Educational

## _Name of Program / Application_
### “OWASP ZAP”

## _What documentation did you use as Reference_? 
####  https://www.zaproxy.org/getting-started/

## Synopsis
### ***_What does the program do_?*** OWASP ZAP is ultimately a proxy server that checks all the traffic that runs through it. This proxy server lies on auto canners that let you intercept vulnerabilities on your website and produce reports from its findings. Here is a quick diagram of how ZAP works.

### ***_What problem does the application solve_?*** This proxy server lies on auto canners that let you intercept vulnerabilities on your website and produce reports from its findings. SQL injection, data exposure, broken authentication, and cross-site scripting.


![](https://user-images.githubusercontent.com/90642764/141511130-aa63f878-cae1-4ec8-87ce-1b61e7d4a22e.png)

# ***Installation***

### We’ll start the installation of **_“OWASP Zed Attack Proxy”_**, but first start your virtual machine and click your **_“Firefox search engine”_**. 

![](https://user-images.githubusercontent.com/90642764/141512423-41b83190-0306-4957-8999-8b4b21d47f41.png)

### And go to the zap proxy home page. **_https://www.zaproxy.org/_** after you located the page click on **_“DOWNLOAD NOW”_**

![](https://user-images.githubusercontent.com/90642764/141512454-36dbad14-0eb4-4b06-8d68-19af7afd1c49.png)

### On the download page look for _“LINUX INSTALLER”_ and press _“DOWNLOAD”_

![](https://user-images.githubusercontent.com/90642764/141512455-ad650a71-72cb-477b-b2cc-b2d60de8ce59.png)

### As soon as you click _“DOWNLOAD”_ a small screen will pop up. Click on  _“Save file”_ and press _“ok”_ 

![](https://user-images.githubusercontent.com/90642764/141512458-dc90f374-4deb-41df-96e8-48e03f9eaffe.png)

### Now, we go to our download directory and  type $ _“cd Downloads/”_ please, type as shown as is case sensitive. 

```$ cd Downloads/ ``` 

![](https://user-images.githubusercontent.com/90642764/141512461-d5340696-4216-4053-a037-d551ba82e415.png)

### After you have typed the above command, you will be in the _“Downloads”_ directory type _“ls”_ and the _“ZAP_2_11_0_unix.sh”_ will be visible

```$ ls ```

```$ ZAP_2_11_0_unix.sh```

![](https://user-images.githubusercontent.com/90642764/141512463-7c3c8da4-4290-412a-bbb3-62a87dc56ee0.png)

### By default, the script “ZAP_2_11_0_unix.sh” is not executable so we have to make it executable. This is the command we will type to accomplish that.


### The command we use was “chmod u+x ZAP_2_11_0_unix.sh” after the command has been type when you type “ls” you see how the “command has turn into red meaning is has been executable”.

``` $ ZAP_2_11_0_unix.sh```

``` $ chmod u+x ZAP_2_11_0_unix.sh```

``` $ ls ```

![](https://user-images.githubusercontent.com/90642764/141512465-3b1ee570-fdd7-476f-8615-d41385fe33c3.png)

### For the download to be successful, you need to type “sudo ./ZAP_2_11_0_unix.sh” ubuntu will ask you for the “password”, type it in and just follow the wizard instruction

``` $ sudo ./ZAP_2_11_0_unix.sh```

![](https://user-images.githubusercontent.com/90642764/141512466-380d3f9f-63fc-41cd-8088-3d8722016e1e.png)

### If, after typing in your password you can’t download the file because you have received “this error massage”. Please type this command it will fix the java issues.

``` $ sudo apt-get install openjdk-8-jre```

![](https://user-images.githubusercontent.com/90642764/141512467-4cdb18de-2fdc-4472-8f7d-dd4475f44e6d.png)

### Please Click “_Next_"

![](https://user-images.githubusercontent.com/90642764/141512469-4780108d-b3dc-4b5a-8980-3b444d296f1d.png)

### Click to “_I accept the Agreement_” and click “_Next_”

![](https://user-images.githubusercontent.com/90642764/141517301-037689fe-ff35-43ee-902d-4e05682ebce8.png)

### Click on the “_Standard Installation_” then click “_Next_” 

![](https://user-images.githubusercontent.com/90642764/141512471-57cd078f-2878-40ad-b8f8-a1d6293d1557.png)

### Next, click “_Install_”

![](https://user-images.githubusercontent.com/90642764/141512472-8b8fdbd9-fd13-4274-a772-6bc391f44ec8.png)

### The next screen you will see the installation taking effect
![](https://user-images.githubusercontent.com/90642764/141512474-6500905c-8fc5-414f-99b4-eb583329aba9.png)

### As soon as the installation is done, please press “_Finish_” 
![](https://user-images.githubusercontent.com/90642764/141512518-6b891a50-7162-4620-ac0e-ef04fd5ef27c.png)

### Now, we are done running the program. To run the proxy, we need to run it from the installation directory. So please open your ubuntu to locate the installation directory, and type “_sudo updated_” and type in your “_password_”.

``` $ sudo updated```

```password```

![](https://user-images.githubusercontent.com/90642764/141512557-c380cfd8-2d1f-4087-95d5-c24bed08ad0f.png)

### If the “_[sudo] password for tj:_” shows up, you are good to run the command.

![](https://user-images.githubusercontent.com/90642764/141512561-4abf1916-c7c6-430a-8c91-9c852803836c.png)

### Next type the “_locate zaproxy_” after you have type command you will see scripts running.

``` $ locate zaproxy``` 

![](https://user-images.githubusercontent.com/90642764/141512583-9ca23a2f-cc6b-455b-ba87-3d4e763302ed.png)

### Here, if for some reason you receive a massage  saying. “_command  ‘locate’ not found, but can be installed with_” this command will help Please type			

``` $ sudo apt install mlocate```

![](https://user-images.githubusercontent.com/90642764/141512594-24fe6176-fcbe-484e-8df9-efd1781df3fc.png)

### After executing the above command type again “_locate zaproxy_”  and look for  the “_/opt/zaproxy/xml/config.xml_”

``` $ locate zaproxy```

![](https://user-images.githubusercontent.com/90642764/141512604-f3151c1d-a55a-47cc-bd37-78e85f7aa2b9.png)

### Now, we will change into it directory which is “_cd /opt/zaproxy/_” after we type “_ls_”  we can see the “_zap.sh_” in red and now we excute the command

``` $ cd /opt/zaproxy/ ```

``` $ ls ```

![](https://user-images.githubusercontent.com/90642764/141512623-ef6f1144-3d65-4d9b-992c-c5b67de8f408.png)

### Now we run the installer by typing “_sudo ./zap.sh_” place in the “_password_” and let it run

``` $ sudo ./zap.sh``` 

![](https://user-images.githubusercontent.com/90642764/141512637-42e252a1-04b9-47d9-a5d1-76deeaae3061.png)

### Now is running the java runtime environment

![](https://user-images.githubusercontent.com/90642764/141512643-459cec58-73f8-4f07-b277-499abdb25c22.png)

### Now it will use and load the jar files and will take a few Min

![](https://user-images.githubusercontent.com/90642764/141512649-7e712c4a-82f7-42de-8dc2-38fbfeaf2bc5.png)

### On the figure below you will the “_welcome to OWAS_” and in front of that window you will see the “_persist Zap Session_” click as you please for now I’m pressing “_NO…_” and click “_Start_”
![](https://user-images.githubusercontent.com/90642764/141512676-404d176b-0826-42ce-926a-79c9ace1306b.png)

### The first time you run “_Zap_” you might see some “_plugin massages that are been download_”. They might be popping up or flashing on the “_foreground_”. Once is done downloading all will disappeared

![pic 27](https://user-images.githubusercontent.com/90642764/141512698-42447337-02aa-4bff-897d-d0a77feb3e76.png)

## _Final Review_

### _Is this software any good?_

OWASP ZAP is a valuable and simple instrument for new learners to understand how to browser across websites. Very simple to set up and incredibly details. There are other answers for more mature, skilled security analysts and testers, who can expand the coverage of a security evaluation.It is most often used to check HTTP techniques, how are they built and if there is delicate information in the traffic, such as how HTTPS certifications work on the website, scanning open ports visible via the web, and trying to adjust HTTP approaches to add or delete requests.

### _What are its pros and cons?_   

***_Pro_-*** it is free, its open source, is actively supported by a very hard-working community, and even us a user’s can get engaged and help the community. 

***_Cons_-*** I just wish the way they handle the file information online would be a little easier to follow” Can you see yourself using this tool in the future? Yes, once in your system is very easy to be maintained and fallow. What did you learn from using this software? 
