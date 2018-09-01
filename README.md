<h1><strong>Elesmer</strong> <br>Startup HTML template based on Gulp & UI Kit</h1>

<!-- <p>
	<img src="https://raw.githubusercontent.com/agragregra/Elesmer-4/master/app/img/preview.jpg" alt="Start HTML Template">
</p> -->

<p>Author: <a href="http://andriy-pavlyshyn.com/" target="_blank">Andriy Pavlyshyn</a></p>

<p>Elesmer is all-inclusive start HTML5 template with Gulp, Sass, Browsersync, Autoprefixer, Clean-CSS, Uglify, Rsync and Bower (libs path) support. The template contains a <strong>.htaccess</strong> file with caching rules for web server.</p>

<p><strong>Elesmer</strong> Start Template uses the best practices of web development.</p>

<p>Cross-browser compatibility: IE9+.</p>

<p>The template uses a Sass with <strong>Sass</strong> or <strong>Scss</strong> syntax (optional).</p>

<h2>How to use Elesmer</h2>

<ol>
	<li><a href="https:https://github.com/Elesmer/Elesmer---star-templete/archive/master.zip">Download</a> <strong>Elesmer</strong> from GitHub;</li>
	<li>Install Node Modules: <strong>npm i</strong>;</li>
	<li>Run the template: <strong>gulp</strong>.</li>
</ol>

<h2>Gulp tasks:</h2>

<ul>
	<li><strong>gulp</strong>: run default gulp task (sass, js, watch, browserSync) for web development;</li>
	<li><strong>rsync</strong>: project deployment on the server from <strong>dist</strong> folder via <strong>RSYNC</strong>;</li>
</ul>

<h2>Rules for working with the starting HTML template</h2>

<ol>
	<li>All HTML files should have similar initial content as in <strong>app/index.html</strong>;</li>
	<li><strong>Template Basic Images Start</strong> comment in app/index.html - all your custom template basic images (og:image for social networking, favicons for a variety of devices);</li>
	<li><strong>Custom Browsers Color Start</strong> comment in app/index.html: set the color of the browser head on a variety of devices;</li>
	<li><strong>Custom HTML</strong> comment in app/index.html - all your custom HTML;</li>
	<li>For installing new jQuery library, just run the command "<strong>bower i plugin-name</strong>" in the terminal. Libraries are automatically placed in the folder <strong>app/libs</strong>. Bower must be installed in the system (npm i -g bower). Then place all jQuery libraries paths in the <strong>'libs'</strong> task (gulpfile.js);</li>
	<li>All custom JS located in <strong>app/js/common.js</strong>;</li>
	<li>All Sass vars placed in <strong>app/sass/_vars.sass | app/scss/_vars.scss</strong>;</li>
	<li>All libraries CSS styles placed in <strong>app/sass/_libs.sass | app/scss/_libs.scss</strong>;</li>
	<li>Rename <strong>ht.access</strong> to <strong>.htaccess</strong> before place it in your web server. This file contain rules for files caching on web server.</li>
</ol>
