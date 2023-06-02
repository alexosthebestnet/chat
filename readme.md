<h1>ChatGPT - JavaScript clone</h1>
<blockquote><p>Version ChatGPT 3.5 turbo, 3.5 turbo 0301.<br>
 <em>Version GPT 4 has not been tested yet.</em></p></blockquote>
<img src="https://github.com/alexsky177/chatgpt/blob/main/screen_dark.png?raw=true" alt="chatgpt"/>
<ol>
<li> Download ZIP or use git clone.</li> 
<li> Put your OpenAI AI API key in file "assets/js/chat.js" - line 10.</li> 
<li>`const strIndex = "YOUR_API_KEY";`</li>
<p>Also you can use Obfuscator to hide your api key for security reason.<br>
https://codebeautify.org/javascript-obfuscator</p>
<ul class="contains-task-list">
<li> Make path /chat on your web server.</li>
<li> Upload files to this directory.</li>
<li> Go to index.html by browser and enjoy.</li>
</ul>
<p>Used frontpage html, js and css from this project (with some mods)<br>
https://github.com/xtekky/chatgpt-clone</p>
<p>Used Javascript Openai api request<br>
https://github.com/gopinav/ai/tree/main/examples/javascript-vanilla</p>
<p>All functions are preserved, except for the web search - instead, a change in theme from dark to light has been made. Added temperature change function.</p>
<h2>Run on localhost</h2>
<p>This program runs on a laptop or desktop computer locally from a folder.</p>
<h3>How to install localhost</h3>
<p>Read this stacoverflow solution<br>
https://stackoverflow.com/questions/38497334/how-to-run-html-file-on-localhost</p>
<ul class="contains-task-list">
<li>Install Pyton - https://www.python.org</li>
<li>Сreate a directory `chat`</li>
<li>Put index.html and assets files here</li>
</ul>
<div>
On the Windows command line or in the Mac terminal, type <pre><code>cd chat</code></pre> then<pre><code>python3 -m http.server</code></pre></div>
<ul>
<li> Open in browser http://localhost:8000</li>
<li> Use program on your local computer.</li>
</ul>
<img src="https://github.com/alexsky177/chatgpt/blob/main/screen_light.png?raw=true" alt="chatgpt"/>
<p><em>Last update - added converation.<br> 
Removed all php files.<br>
Changes path for assets files.</em></p>
