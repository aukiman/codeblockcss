# codeblockcss
Codeblock CSS for use in web pages

https://github.com/aukiman/codeblockcss/blob/e09fd64bb98a634e7a579c1cce225c59b86b66a6/codeblock-example.html

https://github.com/aukiman/codeblockcss/blob/1013cc56b66f8a698889ddeffb4dd6e574c85cae/codeblock-example.html

To use this CSS, you can wrap your code blocks in <pre> and <code> tags as follows:
#
[<pre class="line-numbers">
  <code class="language-bash">
    0 22 * * * /sbin/shutdown -r now
  </code>
</pre>](https://github.com/aukiman/codeblockcss/blob/1013cc56b66f8a698889ddeffb4dd6e574c85cae/codeblock-example.html)

Make sure to include the Prism.js library for syntax highlighting, as shown in the following example:

html
Copy code
<link rel="stylesheet" href="path/to/prism.css" />
<script src="path/to/prism.js"></script>
You can download the Prism.js library and find more information on their official website: Prism.js

Remember to replace "path/to/prism.css" and "path/to/prism.js" with the actual paths to the Prism library files on your server.

This CSS and syntax highlighting setup will give your code blocks a visually appealing and readable style, enhancing the overall presentation of your blog post.
