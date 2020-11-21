# Welcome to my Lacrosse Interest Page

My interest page aims to educate people about the game of lacrosse and hopefully garner more interest for the sport. There is a podcast to listen to, a video to watch, and some interesting blogs to read about while wandering through the website.

## Follow These Steps to Build the Website Yourself:

1. Ensure that you have the appropriate files and that they are in the right folders:
    * views folder with ejs files for the index, about, and blog posts
    * LESS folder with a style file
    * a website_generator.js file
    * a data folder with the blog posts saved as a JSON file
2. If you have not already, download Node.js using the following link: https://nodejs.org/en/download/.
3. Install the necessary packages for fs, ejs, and LESS by using the following commands when you are in your interest site folder in the Terminal:
    * `npm install fs --save`
    * `npm install ejs --save`
    * `npm install less --save`
4. Turn the LESS code into CSS using the following command line when you are in your interest site folder in the Terminal:
    * './node_modules/less/bin/lessc ./LESS/styles.less ./build/css/styles.css'
5. Compile the ejs files and create the html web pages using the following command line while in your interest page in the Terminal:
    * 'node website_generator.js'
6. Open one of the html files in a browser and play around with it!  Enjoy my Interest Page!
