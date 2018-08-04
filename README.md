# dotFiles

## Hacker's way to configure Alpine

1. Clone dotFiles (see below)
1. Edit PatchGD to reflect your name etc. Make changes in lines started with >
1. I used vi editor, you may replece it with, whatever you use.
1. The editor you use to compose mails, will be pico, vi, emacs. I use rotator, which is used to have dynamic sigtaure with different quote below your signature. (If you need to use it, then visit: [LOST site](http://lost.sourceforge.net/) )
1. Put your signature in file ~/.signature
1. Follow steps given below.

```git clone https://github.com/GreatDevelopers/dotFiles.git
cd dotFiles/
cd AlPine/
vi PatchGD 
patch dPineRC  -i PatchGD  -o pineGD
mv pineGD ~/.pinerc
```
