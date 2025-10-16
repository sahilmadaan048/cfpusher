<h3><a href="https://codeforces.com/contest/1385/problem/A" target="_blank" rel="noopener noreferrer">Three Pairwise Maximums</a></h3>

<div class="header"><div class="title">A. Three Pairwise Maximums</div><div class="time-limit"><div class="property-title">time limit per test</div>1 second</div><div class="memory-limit"><div class="property-title">memory limit per test</div>256 megabytes</div><div class="input-file input-standard"><div class="property-title">input</div>standard input</div><div class="output-file output-standard"><div class="property-title">output</div>standard output</div></div><div><p>You are given three positive (i.e. strictly greater than zero) integers $$$x$$$, $$$y$$$ and $$$z$$$.</p><p>Your task is to find positive integers $$$a$$$, $$$b$$$ and $$$c$$$ such that $$$x = \max(a, b)$$$, $$$y = \max(a, c)$$$ and $$$z = \max(b, c)$$$, or determine that it is impossible to find such $$$a$$$, $$$b$$$ and $$$c$$$.</p><p>You have to answer $$$t$$$ independent test cases. Print required $$$a$$$, $$$b$$$ and $$$c$$$ in any (arbitrary) order.</p></div><div class="input-specification"><div class="section-title">Input</div><p>The first line of the input contains one integer $$$t$$$ ($$$1 \le t \le 2 \cdot 10^4$$$) — the number of test cases. Then $$$t$$$ test cases follow.</p><p>The only line of the test case contains three integers $$$x$$$, $$$y$$$, and $$$z$$$ ($$$1 \le x, y, z \le 10^9$$$).</p></div><div class="output-specification"><div class="section-title">Output</div><p>For each test case, print the answer:</p><ul> <li> "<span class="tex-font-style-tt">NO</span>" in the only line of the output if a solution doesn't exist; </li><li> or "<span class="tex-font-style-tt">YES</span>" in the first line and <span class="tex-font-style-bf">any</span> valid triple of positive integers $$$a$$$, $$$b$$$ and $$$c$$$ ($$$1 \le a, b, c \le 10^9$$$) in the second line. You can print $$$a$$$, $$$b$$$ and $$$c$$$ <span class="tex-font-style-bf">in any order</span>. </li></ul></div><div class="sample-tests"><div class="section-title">Example</div><div class="sample-test"><div class="input"><div class="title">Input<div title="Copy" data-clipboard-target="#id003743243373104521" id="id0011399622309400503" class="input-output-copier">Copy</div></div><pre id="id003743243373104521">5
3 2 3
100 100 100
50 49 49
10 30 20
1 1000000000 1000000000
</pre></div><div class="output"><div class="title">Output<div title="Copy" data-clipboard-target="#id007816661051002102" id="id0037201446762199386" class="input-output-copier">Copy</div></div><pre id="id007816661051002102">YES
3 2 1
YES
100 100 100
NO
NO
YES
1 1 1000000000
</pre></div></div></div>