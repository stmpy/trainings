<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kubernetes Engineering Lab</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h2 id="kubernetes-lab-for-engineering">Kubernetes Lab for Engineering</h2>
<p>Learning how to interact with, and use kubernetes in your daily workflow</p>
<h1 id="required-tools">Required Tools</h1>
<h2 id="git">Git</h2>
<h2 id="ssh">SSH</h2>
<h2 id="kubectl">Kubectl</h2>
<p><a href="https://kubernetes.io/docs/reference/kubectl/overview/">https://kubernetes.io/docs/reference/kubectl/overview/</a></p>
<p><code>kubectl</code> is a command line interface for running commands against Kubernetes clusters.</p>
<h3 id="install">Install</h3>
<p><code>brew install kubectl</code></p>
<h2 id="telepresence">Telepresence</h2>
<p><a href="https://www.telepresence.io/discussion/overview">https://www.telepresence.io/discussion/overview</a></p>
<p><code>telepresence</code> is an open source tool that lets you run a single service locally, while connecting that service to a remote Kubernetes cluster.</p>
<h3 id="install-1">Install</h3>
<pre><code>brew cask install osxfusectl
brew install socat datawire/blackbird/telepresence
</code></pre>
<h1 id="getting-access">Getting Access</h1>
<h1 id="cheat-sheet">Cheat Sheet</h1>
<p>How to read some of the commands</p>
<h2 id="logging">Logging</h2>
<h3 id="w-just-kubectl">W/ just kubectl</h3>
<p><code>kubectl logs -f --tail=10 &lt;pod_name&gt; [&lt;container_name&gt;]</code></p>
<p>This will follow the live logs of a container in a pod. The --tail=10 will also show the last 10 lines of the log before following.</p>
<h3 id="kail">Kail</h3>
<h3 id="kubetail">Kubetail</h3>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>
</div>
</body>

</html>
