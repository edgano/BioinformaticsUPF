# BioinformaticsUPF #

## How to start ##

First we need to download VirtualBox software to run the image of the course. 

### Donwload VirtualBox ###

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

### Download the image ###

Go to the site

```http://edgargarriga.com/upfbioinfo.html```

And we will get a file with the extension ```.ova``` 

### Run VB with our image ###

Now, open VirtualBox and follow the steps to import the image.

Click on ```File > Import Appliance``` (Image below)

![Image 001](https://github.com/edgano/BioinformaticsUPF/blob/master/resources/001.png) 

Then click on the icon on the right and select the image you have download in the step before

![Image 002](https://github.com/edgano/BioinformaticsUPF/blob/master/resources/002.png) 

Then, is just the 1st rule of ***Installation Guide***, it means...```Import>>Next>>Next>>...>>Accept```

![Image 003](https://github.com/edgano/BioinformaticsUPF/blob/master/resources/003.png) 

The last step is to run the image. Select the image and click on ```Start``` and it will run and popup a new windows with all the enviroment and software ready to use.

![Image 004](https://github.com/edgano/BioinformaticsUPF/blob/master/resources/004.png) 

## Software Included ##
* Nextflow (ver. 0.26.4.4741)
* Python (ver. 2.7.12)
    + BioPython
* Blast (ver. 2.2.24)
* SeqAnn Package
* T_Coffee (dev_yo@20171228_16:49)
* ViennaRNA Package (ver. 2.4.3)
