<h2>Ready to use commands</h3>
<h3>Find and exec</h3>
<p>
  Find all files in the current folder and execute
</p>
<code>
  $ find . -name "*.*" -exec cat {} \;
</code>
<h3>Count lines</h3>
<p>
  Get the total number of lines of all files in current repository
</p>
<code>
  $ find . -name "*.*" | xargs wc -l
</code>
<p>Add an extension to all files in a given directory</p>
<code>
  find . -name "*.*" -exec mv {} {}.some_extension \;
</code>
