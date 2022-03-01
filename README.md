# Improve performances in Node.js

Using `pm2` and clusters

## INSTALLING PM2
<pre><code>npm i pm2
</code></pre>

or globally
<pre><code>npm i pm2 -g
</code></pre>

## RUN SERVER
<pre><code>pm2 start server.js
</code></pre>

## LIST SERVER STATUS
<pre><code>pm2 list
</code></pre>
or
<pre><code>pm2 ls
</code></pre>
or
<pre><code>pm2 status
</code></pre>

## STOP PROCESS
<pre><code>pm2 stop [pid]
</code></pre>
or
<pre><code>pm2 stop [processName]
</code></pre>

## RESTART A PROCESS
<pre><code>pm2 start [pid]
</code></pre>
or
<pre><code>pm2 start [processName]
</code></pre>

## DELETE PROCESS
<pre><code>pm2 delete [pid]
</code></pre>
or
<pre><code>pm2 delete [processName]
</code></pre>

## INITIALIZE CLUSTERING WITH PM2
<pre><code>pm2 start server.js -i [numberClusters|max]
</code></pre>

## SHOW LOGS
<pre><code>pm2 logs
</code></pre>
or a fixed number of lines
<pre><code>pm2 logs --lines [numberLines]
</code></pre>


## RESTART SERVER
<pre><code>pm2 restart server
</code></pre>
