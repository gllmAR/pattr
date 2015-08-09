# Pattr

#### A State saving Preset manager with interpolation for PD Vanilla (0.46)


![https://dl.dropboxusercontent.com/u/15569938/git/web_assets/pattr/pattr_main.png](https://dl.dropboxusercontent.com/u/15569938/git/web_assets/pattr/pattr_main.png)

inspired by pattrstorage object in max msp

#### Installation :
CD in your patch directory and Git clone  (or download it and extract)
```
git clone https://github.com/gllmAR/pattr.git
```




#### Usage :

Look at [pattrstorage-help.pd] for more info


to create a storage abstraction

(nogui)
`[pattr/storage argument]`
or
`[pattr/gstorage argument]`

in the [argument] put the name of the context that the storage refere to
`[pattr/storage pattrHelp]`


Create some state saving object with a argument for the context

`pattr/sfloat pattrHelp.txt`
or with a gui
`pattr/sfloat pattrHelp.txt`

#### Features
* multi-context,
* support interpolation,  
* one save file,  
* save to textfiles  (txt)


#### todo
* save and recall symbols,  atoms,  list,  array.
* Clean up in the txt file (arrange in order)
