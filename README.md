<!DOCTYPE html>
<html>

<head>
    <title>Port Scanner</title>
</head>

<body>

<h1>Port Scanner</h1>

<h2>Description</h2>

<p>This is a simple Python script for scanning open ports on a target host. It supports multi-threaded scanning and can identify common services like FTP, SSH, HTTP, and HTTPS.</p>

<h2>Usage</h2>

<pre><code>python3 port_scan.py TARGET START_PORT END_PORT
</code></pre>

<ul>
    <li><code>TARGET</code>: The target host to scan.</li>
    <li><code>START_PORT</code>: The starting port for the scan range.</li>
    <li><code>END_PORT</code>: The ending port for the scan range.</li>
</ul>

<h2>Features</h2>

<ul>
    <li>Multi-threaded port scanning</li>
    <li>Service identification (FTP, SSH, HTTP, HTTPS)</li>
    <li>Banner grabbing for HTTP services</li>
    <li>...</li>
</ul>

<h2>How to Run</h2>

<ol>
    <li>Clone the repository to your local machine.</li>
    <li>Open a terminal or command prompt.</li>
    <li>Navigate to the directory where <code>port_scan.py</code> is located.</li>
    <li>Run the script with the appropriate arguments.</li>
</ol>

<h2>Example</h2>

<pre><code>python3 port_scan.py example.com 1 1024
</code></pre>

<h2>Author</h2>

<p><a href="https://github.com/rajputpritesh1">Pritesh Rajput</a></p>

</body>

</html>
