# BioinformaticsUPF
How to start

First we need to download VirtualBox software to run the image of the course. 

To donwload VirtualBox

First we will add the source list of VB to our host

```sudo nano /etc/apt/sources.list```

Then we will append the following line

```deb http://download.virtualbox.org/virtualbox/debian xenial contrib```

Press ```Ctrl+0``` to save and ```Ctrl+X``` to close the file

Now, we need the Oracle public key

```wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -```

And finally, we will updater the index and install VB

```
sudo apt update
sudo apt install virtualbox-5.1
```

The next step is to download the image we have prepared for the course.

Go to the site

```http://edgargarriga.com/upfbioinfo.html```

And we will get a file with the extension ```.ova``` 

Now, open VirtualBox and follow the steps to import the image.

