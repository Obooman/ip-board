THIS show your computer ip address directly in your desktop without ifconfig cases.

[![Demo Gif](https://s4.postimg.org/gbw0043bx/8_19_2016_17_21_20.gif)](https://postimg.org/image/wa4pq8xjt/)

Based on nw.js.

#### To release this as a real app,you have to do

1. download nw.js package
2. zip `index.html` & `package.json` with `$ zip -r ../${PWD##*/}.nw *`
3. rename the `.nw` file to `app.nw`
4. right-click the unzipped executable `nwjs` and choose `show content`
5. move app.nw to `Content/Resources`
6. double click the nwjs file and you will see the little window with your ip address and copy button.
