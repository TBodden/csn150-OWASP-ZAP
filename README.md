### csn150-OWASP-ZAP
## Educational


_So, what is “OWASP ZAP? is an Open-source Web Application Security Project” along with the ZAP a Zed Attack Proxy is an online group that produces freely accessible editorials, practices, documentation, tools, and bits of knowledge in the field of web appliance security. The Open Web Application Security Project offers free and open resources. It is led by a non-profit called The OWASP Institution. The OWASP ZAP of 2021 is the available result of the latest research centered on a deep examination of data compiled from over forty partner organizations. It is aimed to be used equally to those new to application security as well as professional infiltration testers._


An OWASP ZAP check can reveal issues relating to SQL injection, wrecked authentication, complex data exposure, broken access controls, security misconfigurations, Cross-Site Scripting (XSS), insecure deserialization, components with known vulnerabilities, and any missing security headers.

OWASP ZAP is ultimately a proxy server that scans all the traffic that runs through it. This proxy server consists of auto canners that let you intercept vulnerabilities on your website and produce reports from its findings. Here is a quick diagram of how ZAP works.


![](https://user-images.githubusercontent.com/90642764/141511130-aa63f878-cae1-4ec8-87ce-1b61e7d4a22e.png)

## We’ll start the installation of **_“OWASP Zed Attack Proxy”_**, but first start your virtual machine and click your **_“Firefox search engine”_**. 

![](https://user-images.githubusercontent.com/90642764/141512423-41b83190-0306-4957-8999-8b4b21d47f41.png)

## And go to the zap proxy home page. **_https://www.zaproxy.org/_** after you located the page click on **_“DOWNLOAD NOW”_**

![](https://user-images.githubusercontent.com/90642764/141512454-36dbad14-0eb4-4b06-8d68-19af7afd1c49.png)

## On the download page look for _“LINUX INSTALLER”_ and press _“DOWNLOAD”_

![](https://user-images.githubusercontent.com/90642764/141512455-ad650a71-72cb-477b-b2cc-b2d60de8ce59.png)

## As soon as you click _“DOWNLOAD”_ a small screen will pop up. Click on  _“Save file”_ and press _“ok”_ 

![](https://user-images.githubusercontent.com/90642764/141512458-dc90f374-4deb-41df-96e8-48e03f9eaffe.png)

Now, we go to our download directory and  type $ _“cd Downloads/”_ please, type as shown as is case sensitive. 

```$ “cd Downloads/” ``` 

![](https://user-images.githubusercontent.com/90642764/141512461-d5340696-4216-4053-a037-d551ba82e415.png)

## After you have typed the above command, you will be in the _“Downloads”_ directory type _“ls”_ and the _“ZAP_2_11_0_unix.sh”_ will be visible

``` ls ```

```ZAP_2_11_0_unix.sh```

![](https://user-images.githubusercontent.com/90642764/141512463-7c3c8da4-4290-412a-bbb3-62a87dc56ee0.png)

## By default, the script “ZAP_2_11_0_unix.sh” is not executable so we have to make it executable. This is the command we will type to accomplish that.


## The command we use was “chmod u+x ZAP_2_11_0_unix.sh” after the command has been type when you type “ls” you see how the “command has turn into red meaning is has been executable”.

```ZAP_2_11_0_unix.sh```

```chmod u+x ZAP_2_11_0_unix.sh```

``` ls ```

![](https://user-images.githubusercontent.com/90642764/141512465-3b1ee570-fdd7-476f-8615-d41385fe33c3.png)

## For the download to be successful, you need to type “sudo ./ZAP_2_11_0_unix.sh” ubuntu will ask you for the “password”, type it in and just follow the wizard instruction

```sudo ./ZAP_2_11_0_unix.sh```

![](https://user-images.githubusercontent.com/90642764/141512466-380d3f9f-63fc-41cd-8088-3d8722016e1e.png)

## If, after typing in your password you can’t download the file because you have received “this error massage”. Please type this command it will fix the java issues.

```sudo apt-get install openjdk-8-jre```

![](https://user-images.githubusercontent.com/90642764/141512467-4cdb18de-2fdc-4472-8f7d-dd4475f44e6d.png)

## Please Click “_Next_"
![](https://user-images.githubusercontent.com/90642764/141512469-4780108d-b3dc-4b5a-8980-3b444d296f1d.png)


