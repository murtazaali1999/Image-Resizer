# Image-Resizer 
An app that resizes images, That also consumes less space
Dated: 6/12/2021

Now, I was trying to make this project as part of my course but could'nt complete it because, It has taken a lot of time to resolve its Issue's
.As I have came to know recently,That esm and electron do not work together friendly. Electron and esm are quite unstable in their latest version's as 
per my speculation.Tried to use many npm packages like esm, And also the packages like

- imagemin-pngquant
- imagemin-mozjpeg 

They Have vulnerablities in their current version and haven't been resolved yet. So Im currently putting this project on hold,On a side note I have given
this project to some devs to resolve but most of them either didn't respond,Because the level of unstablity.The devs and the community have discussed about 
this problem,But either the issue is closed or suggest to use older versions of :

- Nodejs 
- ElectronJs
- ES6
- JS version e.g: suggested in an article to use V7 engine of javascript


 The main problem that I think resides in the 
 
 - loader
 
 That resides in the electron module
 
 That is making it difficult to resolve the issues that might come after this problem has been tackeled
 
 To resolve this issue, Electron's handler should make a module or functionality to allow devs to customize their loader to use either cjs(common javscript)/js or 
 mjs(modern javacript/ecmascript)
