#Pattr

####A State saving Preset manager for PD Vanilla (0.46)


![https://dl.dropboxusercontent.com/u/15569938/quickshare/git/pattr_main.png](https://dl.dropboxusercontent.com/u/15569938/quickshare/git/pattr_main.png)


#####Inspired from  

[http://pattr.ru/puredata-preset-manager.html](http://pattr.ru/puredata-preset-manager.html)



####Installation :
Git clone to your main patch directory (or download it and extract)





####Usage :
creating a storage abstraction

`[pattr/storage argument]`

in the [argument] put the name of the context that the storage refere to

`[pattr/storage main]`


Create some state saving object with a argument for the context

`pattr/sfloat main`
`pattr/slist main`

#### Features
multi-context,  multi save,  save to textfiles  (txt)
