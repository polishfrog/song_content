How run project?

First of all install NodeJS

Open terminal in project

<code>npm install</code>, but npm is install in this project

<code>npm run dev</code> now you will see some information 
First line is it a ip address, hold <code>left CTRL</code> and click <code>Left button</code>  in your mouse
Easy? Right?


If you don't want install NodeJS, You have one more option.
Open <code>package.json</code> and add the code after 9-th line

<code>"sass": "sass ./src/pages/home-page/styles/home-page.scss ./src/pages/home-page/styles/home-page.css",
    "test": "echo \"Error: no test specified\" && exit 1"</code>
    
Next in <code>index.html</code> add <code>.</code> to all link with photos (3 photos)

Great! You see song card :)
