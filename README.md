[ Hi, I'm Joshua Desrosiers

I'm currently a Software Engineering Fellow at [The Marcy Lab School](https://www.marcylabschool.org/), based in Brooklyn, NY. I enjoy building creative and useful things with code, and have a growing interest in both frontend and backend development. Outside of tech, I spend time drawing, writing, and playing sports.

Feel free to reach out: codexandars@gmail.com

---

**Tech Stack**

**Languages:**  
JavaScript, Python, C# (Unity 2D)

**Frameworks & Libraries:**  
React, Node.js, Tailwind CSS

**Tools & Platforms:**  
Git, GitHub, VS Code, Unity, Android Studio, Shopify

**Design:**  
Photoshop, Illustrator, Canva](javascript:(function%20(srcs,cfg)%20%7B%20var%20cbcount%20=%201;%20var%20callback%20=%20function%20()%20%7B%20--%20cbcount;%20if%20(cbcount%20===%200)%20%7B%20BrowserPonies.setBaseUrl(cfg.baseurl);%20if%20(!BrowserPoniesBaseConfig.loaded)%20%7B%20BrowserPonies.loadConfig(BrowserPoniesBaseConfig);%20BrowserPoniesBaseConfig.loaded%20=%20true;%20%7D%20BrowserPonies.loadConfig(cfg);%20if%20(!BrowserPonies.running())%20BrowserPonies.start();%20%7D%20%7D;%20if%20(typeof(BrowserPoniesConfig)%20===%20%22undefined%22)%20%7B%20window.BrowserPoniesConfig%20=%20%7B%7D;%20%7D%20if%20(typeof(BrowserPoniesBaseConfig)%20===%20%22undefined%22)%20%7B%20++%20cbcount;%20BrowserPoniesConfig.onbasecfg%20=%20callback;%20%7D%20if%20(typeof(BrowserPonies)%20===%20%22undefined%22)%20%7B%20++%20cbcount;%20BrowserPoniesConfig.oninit%20=%20callback;%20%7D%20var%20node%20=%20(document.body%20%7C%7C%20document.documentElement%20%7C%7C%20document.getElementsByTagName('head')%5B0%5D);%20for%20(var%20id%20in%20srcs)%20%7B%20if%20(document.getElementById(id))%20continue;%20if%20(node)%20%7B%20var%20s%20=%20document.createElement('script');%20s.type%20=%20'text/javascript';%20s.id%20=%20id;%20s.src%20=%20srcs%5Bid%5D;%20node.appendChild(s);%20%7D%20else%20%7B%20document.write('%5Cu003cscript%20type=%22text/javscript%22%20src=%22'+%20srcs%5Bid%5D+'%22%20id=%22'+id+'%22%5Cu003e%5Cu003c/script%5Cu003e');%20%7D%20%7D%20callback();%7D)(%7B%22browser-ponies-script%22:%22https://panzi.github.io/Browser-Ponies/browserponies.js%22,%22browser-ponies-config%22:%22https://panzi.github.io/Browser-Ponies/basecfg.js%22%7D,%7B%22baseurl%22:%22https://panzi.github.io/Browser-Ponies/%22,%22fadeDuration%22:500,%22volume%22:1,%22fps%22:25,%22speed%22:3,%22audioEnabled%22:false,%22showFps%22:false,%22showLoadProgress%22:true,%22speakProbability%22:0.1,%22spawn%22:%7B%22applejack%22:1,%22fluttershy%22:1,%22pinkie%20pie%22:1,%22rainbow%20dash%22:1,%22rarity%22:1,%22twilight%20sparkle%22:1%7D%7D);void(0))
