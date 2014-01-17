<h1>Grain Theme Template</h1>
<p>The theme template is a starting point for creating new Grain themes. It provides all the necessary source and
configuration files to help Groovy developers to build Grain themes from scratch.</p>
<p>Please, refer to the <a href="http://sysgears.com/grain/docs/latest/">documentation</a> for further details.</p>
<h1>Contributing</h1>
<p>Any person or company wanting to contribute to this project should follow
the following rules in order to their contribution being accepted.</p>
<h2>Sign your Work</h2>
<p>We require that all contributors "sign-off" on their commits.  This
certifies that the contribution is your original work, or you have rights to
submit it under the same license, or a compatible license.</p>
<p>Any contribution which contains commits that are not Signed-Off will not be
accepted.</p>
<p>To sign off on a commit you simply use the <code>--signoff</code> (or <code>-s</code>) option when
committing your changes:</p>
<pre><code>$ git commit -s -m "Adding a new widget driver for cogs."
</code></pre>
<p>This will append the following to your commit message:</p>
<pre><code>Signed-off-by: Your Name &lt;your@email.com&gt;
</code></pre>
<p>By doing this you certify the below:</p>
<pre><code>Developer's Certificate of Origin 1.1
</code></pre>
<p>If you wish to add the signoff to the commit message on your every commit
without the need to specify -s or --signoff, rename
.git/hooks/commit-msg.sample to .git/hooks/commit-msg and uncomment the lines:</p>
<figure class='code'><div class="highlight"><table><tr><td class="gutter"><pre class="line-numbers"><span class='line-number'>1</span>
<span class='line-number'>2</span>
</pre></td><td class='code'><pre><code class='sh'><span class='line'><span class="nv">SOB</span><span class="o">=</span><span class="k">$(</span>git var GIT_AUTHOR_IDENT | sed -n <span class="s1">&#39;s/^\(.*&gt;\).*$/Signed-off-by: \1/p&#39;</span><span class="k">)</span>
</span><span class='line'>grep -qs <span class="s2">&quot;^$SOB&quot;</span> <span class="s2">&quot;$1&quot;</span> <span class="o">||</span> <span class="nb">echo</span> <span class="s2">&quot;$SOB&quot;</span> &gt;&gt; <span class="s2">&quot;$1&quot;</span>
</span></code></pre></td></tr></table></div></figure>
<h2>Developer's Certificate of Origin</h2>
<p>To help track the author of a patch as well as the submission chain,
and be clear that the developer has authority to submit a patch for
inclusion into this project please sign off your work.  The sign off
certifies the following:</p>
<pre><code>Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.

(e) I hereby grant to the project, SysGears, LLC and its successors; 
    and recipients of software distributed by the Project a perpetual,
    worldwide, non-exclusive, no-charge, royalty-free, irrevocable
    copyright license to reproduce, modify, prepare derivative works of,
    publicly display, publicly perform, sublicense, and distribute this
    contribution and such modifications and derivative works consistent
    with this Project, the open source license indicated in the previous
    work or other appropriate open source license specified by the Project
    and approved by the Open Source Initiative(OSI)
    at http://www.opensource.org.
</code></pre>
<h1>License</h1>
<p>Grain Theme Template is licensed under the terms of the
<a href="https://github.com/sysgears/grain-theme-template/UNLICENSE">Public Domain License</a>.</p>
