<h1 align="center">Sensitive Image Shield</h1>

![ImgShield Demo](https://github.com/theamanstark/sensitive-image-shield/raw/main/.gitassets/demo.gif)

### # Demo 👉 [click here](https://imgshield.amanstark.com). 

<br>

<h1 align="center">Documentation</h1>

1. Just add the CSS using any one of the following methods below above the `</head>`

    (i) Using inline CSS Style 👇

    ```html
    <style>
    .image-wrapper,.mature-content{margin:0;padding:0;vertical-align:top}.image-wrapper{position:relative;display:inline-block;overflow:hidden}.mature-content{display:block;max-width:100%}.blur-layer,.content-layer{position:absolute;top:0;left:0;right:0;bottom:0;transition:opacity .5s,border-radius;border-radius:30px}.blur-layer{background-color:rgba(255,255,255,.5);-webkit-backdrop-filter:blur(20px);backdrop-filter:blur(20px);z-index:1}.content-layer{display:flex;flex-direction:column;align-items:center;justify-content:center;z-index:2;background-color:rgba(0,0,0,.1)}.mature-icon{height:100px;width:100px}.mature-content-heading{font-size:40px!important;margin-bottom:-10px!important;margin-top:25px!important;font-family:cursive!important}.mature-content-description{margin-top:20px!important;font-size:larger!important;font-family:cursive!important}.bubbly-button{font-family:Helvetica,Arial,sans-serif;display:inline-block;font-size:1em;padding:.8em 1em;-webkit-appearance:none;appearance:none;background-color:#ff344e;color:#fff;border-radius:15px;border:none;cursor:pointer;position:relative;transition:transform .1s ease-in,box-shadow .25s ease-in;box-shadow:0 2px 25px rgba(255,0,130,.5)}.bubbly-button:focus{outline:0}.bubbly-button:after,.bubbly-button:before{position:absolute;content:"";width:140%;height:100%;left:-20%;z-index:-1000;transition:.5s ease-in-out;background-repeat:no-repeat}.bubbly-button:before{display:none;top:-75%;background-image:radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,transparent 20%,#ff344e 20%,transparent 30%),radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,transparent 10%,#ff344e 15%,transparent 20%),radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,#ff344e 20%,transparent 20%);background-size:10% 10%,20% 20%,15% 15%,20% 20%,18% 18%,10% 10%,15% 15%,10% 10%,18% 18%}.bubbly-button:after{display:none;bottom:-75%;background-image:radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,transparent 10%,#ff344e 15%,transparent 20%),radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,#ff344e 20%,transparent 20%),radial-gradient(circle,#ff344e 20%,transparent 20%);background-size:15% 15%,20% 20%,18% 18%,20% 20%,15% 15%,10% 10%,20% 20%}.bubbly-button:active{transform:scale(.9);background-color:#e60074;box-shadow:0 2px 25px rgba(255,0,130,.2)}.bubbly-button.animate:before{display:block;animation:.75s ease-in-out forwards topBubbles}.bubbly-button.animate:after{display:block;animation:.75s ease-in-out forwards bottomBubbles}@keyframes topBubbles{0%{background-position:5% 90%,10% 90%,10% 90%,15% 90%,25% 90%,25% 90%,40% 90%,55% 90%,70% 90%}50%{background-position:0 80%,0 20%,10% 40%,20% 0,30% 30%,22% 50%,50% 50%,65% 20%,90% 30%}100%{background-position:0 70%,0 10%,10% 30%,20% -10%,30% 20%,22% 40%,50% 40%,65% 10%,90% 20%;background-size:0 0,0 0,0 0,0 0,0 0,0 0}}@keyframes bottomBubbles{0%{background-position:10% -10%,30% 10%,55% -10%,70% -10%,85% -10%,70% -10%,70% 0}50%{background-position:0 80%,20% 80%,45% 60%,60% 100%,75% 70%,95% 60%,105% 0}100%{background-position:0 90%,20% 90%,45% 70%,60% 110%,75% 80%,95% 70%,110% 10%;background-size:0 0,0 0,0 0,0 0,0 0,0 0}}@media (max-width:767px){.mature-icon{height:15vw!important;width:15vw!important}.mature-content-heading{font-size:5.5vw!important;margin-bottom:-10px!important;margin-top:10px!important;font-family:cursive!important}.mature-content-description{margin-top:20px!important;font-size:2.8vw!important;font-family:cursive!important}.bubbly-button{font-size:3vw!important;padding:2.8vw 3vw!important}}
    </style>
    ```

    (ii) Using an external CSS style cdn link 👇

    ```html
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/theamanstark/sensitive-image-shield@main/assets/style.min.css" />
    ```

2. Now, put the following javascript above: `</body>`, either at the root of your site or in the post where the widget will be used.

   ```html
   <script src='https://cdn.jsdelivr.net/gh/theamanstark/sensitive-image-shield@main/assets/script.min.js'></script>
   ```

3. Finally, use the HTML below to place the sensitive image shield widget on your image.

   ```html
   <div class="image-wrapper">
   <img src="path_to_image.jpg" alt="Description" class="mature-content" />
   <div class="blur-layer"></div>
   <div class="content-layer">
   <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" style="fill: #ff344e;" class="mature-icon">
   <path d="M38.8 5.1C28.4-3.1 13.3-1.2 5.1 9.2S-1.2 34.7 9.2 42.9l592 464c10.4 8.2 25.5 6.3 33.7-4.1s6.3-25.5-4.1-33.7L525.6 386.7c39.6-40.6 66.4-86.1 79.9-118.4c3.3-7.9 3.3-16.7 0-24.6c-14.9-35.7-46.2-87.7-93-131.1C465.5 68.8 400.8 32 320 32c-68.2 0-125 26.3-169.3 60.8L38.8 5.1zM223.1 149.5C248.6 126.2 282.7 112 320 112c79.5 0 144 64.5 144 144c0 24.9-6.3 48.3-17.4 68.7L408 294.5c8.4-19.3 10.6-41.4 4.8-63.3c-11.1-41.5-47.8-69.4-88.6-71.1c-5.8-.2-9.2 6.1-7.4 11.7c2.1 6.4 3.3 13.2 3.3 20.3c0 10.2-2.4 19.8-6.6 28.3l-90.3-70.8zM373 389.9c-16.4 6.5-34.3 10.1-53 10.1c-79.5 0-144-64.5-144-144c0-6.9 .5-13.6 1.4-20.2L83.1 161.5C60.3 191.2 44 220.8 34.5 243.7c-3.3 7.9-3.3 16.7 0 24.6c14.9 35.7 46.2 87.7 93 131.1C174.5 443.2 239.2 480 320 480c47.8 0 89.9-12.9 126.2-32.5L373 389.9z" /></svg>
   <h2 class="mature-content-heading">Warning: Sensitive Content!!</h2>
   <p class="mature-content-description">This image contains content that may be disturbing.</p>
   <button class="bubbly-button">View Photo</button>
   </div>
   </div>
   ```

**Credits**: Sensitive Image Shield created by [Aman Singh](https://www.amanstark.com).
