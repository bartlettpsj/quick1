# quick1

This is based on article:  https://stackoverflow.com/questions/58363577/create-react-app-is-too-slow-and-creates-messy-apps

I wanted to see how big a base react project is.  So this template is using Webpack and super basic.  

du -h -d1 .  reports that its 77MB

Compared to a basic vite project which comes out at 69M

Compared to a basic vite project with typescript which comes out at 97M

A basic create react app without typescript comes in at 347MB

A basic create react app with typescript comesin at 344MB (wierd its a bit smaller!).


My conclusion is that the lightest workable option is actually vite.  Adding typescript isnt too bad either as it adds another 28MB only.
