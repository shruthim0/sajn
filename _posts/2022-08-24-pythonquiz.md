---
keywords: fastai
description: Creating, describing, and answering a quiz on python and its syntax
title: Python Quiz
nb_path: _notebooks/2022-08-24-pythonquiz.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-08-24-pythonquiz.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="First,-answering-the-provided-questions:">First, answering the provided questions:<a class="anchor-link" href="#First,-answering-the-provided-questions:"> </a></h2>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">question_and_answer</span><span class="p">(</span><span class="n">prompt</span><span class="p">):</span>   <span class="c1"># defines question_and_answer</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Question: &quot;</span> <span class="o">+</span> <span class="n">prompt</span><span class="p">)</span>      <span class="c1"># asks the question</span>
    <span class="n">msg</span> <span class="o">=</span> <span class="nb">input</span><span class="p">()</span>                  <span class="c1"># the user&#39;s input/answer is taken</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Answer: &quot;</span> <span class="o">+</span> <span class="n">msg</span><span class="p">)</span>        <span class="c1"># prints the user&#39;s input/answer</span>

<span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;Name the Python output command mentioned in this lesson?&quot;</span><span class="p">)</span>
<span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;If you see many lines of code in order, what would College Board call it?&quot;</span><span class="p">)</span>
<span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;Describe a keyword used in Python to define a function?&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Question: Name the Python output command mentioned in this lesson?
</pre>
</div>
</div>

<div class="output_area">

<div class="output_subarea output_text output_error">
<pre>
<span class="ansi-red-fg">---------------------------------------------------------------------------</span>
<span class="ansi-red-fg">KeyboardInterrupt</span>                         Traceback (most recent call last)
<span class="ansi-green-intense-fg ansi-bold">/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb Cell 3</span> in <span class="ansi-cyan-fg">&lt;cell line: 6&gt;</span><span class="ansi-blue-fg">()</span>
<span class="ansi-green-intense-fg ansi-bold">      &lt;a href=&#39;vscode-notebook-cell://wsl%2Bubuntu/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb#W2sdnNjb2RlLXJlbW90ZQ%3D%3D?line=2&#39;&gt;3&lt;/a&gt;</span>     msg = input()                  # the user&#39;s input/answer is taken
<span class="ansi-green-intense-fg ansi-bold">      &lt;a href=&#39;vscode-notebook-cell://wsl%2Bubuntu/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb#W2sdnNjb2RlLXJlbW90ZQ%3D%3D?line=3&#39;&gt;4&lt;/a&gt;</span>     print(&#34;Answer: &#34; + msg)        # prints the user&#39;s input/answer
<span class="ansi-green-fg">----&gt; &lt;a href=&#39;vscode-notebook-cell://wsl%2Bubuntu/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb#W2sdnNjb2RlLXJlbW90ZQ%3D%3D?line=5&#39;&gt;6&lt;/a&gt;</span> question_and_answer(&#34;Name the Python output command mentioned in this lesson?&#34;)
<span class="ansi-green-intense-fg ansi-bold">      &lt;a href=&#39;vscode-notebook-cell://wsl%2Bubuntu/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb#W2sdnNjb2RlLXJlbW90ZQ%3D%3D?line=6&#39;&gt;7&lt;/a&gt;</span> question_and_answer(&#34;If you see many lines of code in order, what would College Board call it?&#34;)
<span class="ansi-green-intense-fg ansi-bold">      &lt;a href=&#39;vscode-notebook-cell://wsl%2Bubuntu/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb#W2sdnNjb2RlLXJlbW90ZQ%3D%3D?line=7&#39;&gt;8&lt;/a&gt;</span> question_and_answer(&#34;Describe a keyword used in Python to define a function?&#34;)

<span class="ansi-green-intense-fg ansi-bold">/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb Cell 3</span> in <span class="ansi-cyan-fg">question_and_answer</span><span class="ansi-blue-fg">(prompt)</span>
<span class="ansi-green-intense-fg ansi-bold">      &lt;a href=&#39;vscode-notebook-cell://wsl%2Bubuntu/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb#W2sdnNjb2RlLXJlbW90ZQ%3D%3D?line=0&#39;&gt;1&lt;/a&gt;</span> def question_and_answer(prompt):   # defines question_and_answer
<span class="ansi-green-intense-fg ansi-bold">      &lt;a href=&#39;vscode-notebook-cell://wsl%2Bubuntu/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb#W2sdnNjb2RlLXJlbW90ZQ%3D%3D?line=1&#39;&gt;2&lt;/a&gt;</span>     print(&#34;Question: &#34; + prompt)      # asks the question
<span class="ansi-green-fg">----&gt; &lt;a href=&#39;vscode-notebook-cell://wsl%2Bubuntu/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb#W2sdnNjb2RlLXJlbW90ZQ%3D%3D?line=2&#39;&gt;3&lt;/a&gt;</span>     msg = input()                  # the user&#39;s input/answer is taken
<span class="ansi-green-intense-fg ansi-bold">      &lt;a href=&#39;vscode-notebook-cell://wsl%2Bubuntu/home/shruthim/vscode/repository2/_notebooks/2022-08-24-pythonquiz.ipynb#W2sdnNjb2RlLXJlbW90ZQ%3D%3D?line=3&#39;&gt;4&lt;/a&gt;</span>     print(&#34;Answer: &#34; + msg)

File <span class="ansi-green-fg">~/.local/lib/python3.8/site-packages/ipykernel/kernelbase.py:1177</span>, in <span class="ansi-cyan-fg">Kernel.raw_input</span><span class="ansi-blue-fg">(self, prompt)</span>
<span class="ansi-green-intense-fg ansi-bold">   1173</span> if not self._allow_stdin:
<span class="ansi-green-intense-fg ansi-bold">   1174</span>     raise StdinNotImplementedError(
<span class="ansi-green-intense-fg ansi-bold">   1175</span>         &#34;raw_input was called, but this frontend does not support input requests.&#34;
<span class="ansi-green-intense-fg ansi-bold">   1176</span>     )
<span class="ansi-green-fg">-&gt; 1177</span> return self._input_request(
<span class="ansi-green-intense-fg ansi-bold">   1178</span>     str(prompt),
<span class="ansi-green-intense-fg ansi-bold">   1179</span>     self._parent_ident[&#34;shell&#34;],
<span class="ansi-green-intense-fg ansi-bold">   1180</span>     self.get_parent(&#34;shell&#34;),
<span class="ansi-green-intense-fg ansi-bold">   1181</span>     password=False,
<span class="ansi-green-intense-fg ansi-bold">   1182</span> )

File <span class="ansi-green-fg">~/.local/lib/python3.8/site-packages/ipykernel/kernelbase.py:1219</span>, in <span class="ansi-cyan-fg">Kernel._input_request</span><span class="ansi-blue-fg">(self, prompt, ident, parent, password)</span>
<span class="ansi-green-intense-fg ansi-bold">   1216</span>             break
<span class="ansi-green-intense-fg ansi-bold">   1217</span> except KeyboardInterrupt:
<span class="ansi-green-intense-fg ansi-bold">   1218</span>     # re-raise KeyboardInterrupt, to truncate traceback
<span class="ansi-green-fg">-&gt; 1219</span>     raise KeyboardInterrupt(&#34;Interrupted by user&#34;) from None
<span class="ansi-green-intense-fg ansi-bold">   1220</span> except Exception:
<span class="ansi-green-intense-fg ansi-bold">   1221</span>     self.log.warning(&#34;Invalid Message:&#34;, exc_info=True)

<span class="ansi-red-fg">KeyboardInterrupt</span>: Interrupted by user</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">getpass</span><span class="o">,</span> <span class="nn">sys</span>

<span class="k">def</span> <span class="nf">question_with_response</span><span class="p">(</span><span class="n">prompt</span><span class="p">):</span>    <span class="c1"># defines question_and_answer </span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Question: &quot;</span> <span class="o">+</span> <span class="n">prompt</span><span class="p">)</span>       <span class="c1"># asks the question</span>
    <span class="n">msg</span> <span class="o">=</span> <span class="nb">input</span><span class="p">()</span>                      <span class="c1"># the user&#39;s input/answer is taken</span>
    <span class="k">return</span> <span class="n">msg</span>                         <span class="c1"># returns as string value</span>

<span class="n">questions</span> <span class="o">=</span> <span class="mi">3</span>        <span class="c1"># total number of questions</span>
<span class="n">correct</span> <span class="o">=</span> <span class="mi">0</span>          <span class="c1"># number that is initially correct (before any questions are answered)</span>

<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Hello, &#39;</span> <span class="o">+</span> <span class="n">getpass</span><span class="o">.</span><span class="n">getuser</span><span class="p">()</span> <span class="o">+</span> <span class="s2">&quot; running &quot;</span> <span class="o">+</span> <span class="n">sys</span><span class="o">.</span><span class="n">executable</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You will be asked &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">questions</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot; questions.&quot;</span><span class="p">)</span>
<span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;Are you ready to take a test?&quot;</span><span class="p">)</span>

<span class="n">rsp</span> <span class="o">=</span> <span class="n">question_with_response</span><span class="p">(</span><span class="s2">&quot;What command is used to include other functions that were previously developed?&quot;</span><span class="p">)</span>
<span class="k">if</span> <span class="n">rsp</span> <span class="o">==</span> <span class="s2">&quot;import&quot;</span><span class="p">:</span>       <span class="c1"># establishing if/else statement; if user&#39;s input is &quot;import&quot;</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is correct!&quot;</span><span class="p">)</span>  <span class="c1"># then it is correct</span>
    <span class="n">correct</span> <span class="o">+=</span> <span class="mi">1</span>                 <span class="c1"># one point is added to number correct score</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is incorrect!&quot;</span><span class="p">)</span>  <span class="c1"># if user&#39;s input is not &quot;import,&quot; than user is incorrect</span>

<span class="n">rsp</span> <span class="o">=</span> <span class="n">question_with_response</span><span class="p">(</span><span class="s2">&quot;What command is used to evaluate correct or incorrect response in this example?&quot;</span><span class="p">)</span>
<span class="k">if</span> <span class="n">rsp</span> <span class="o">==</span> <span class="s2">&quot;if&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is correct!&quot;</span><span class="p">)</span>
    <span class="n">correct</span> <span class="o">+=</span> <span class="mi">1</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is incorrect!&quot;</span><span class="p">)</span>

<span class="n">rsp</span> <span class="o">=</span> <span class="n">question_with_response</span><span class="p">(</span><span class="s2">&quot;Each &#39;if&#39; command contains an &#39;_________&#39; to determine a true or false condition?&quot;</span><span class="p">)</span>
<span class="k">if</span> <span class="n">rsp</span> <span class="o">==</span> <span class="s2">&quot;expression&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is correct!&quot;</span><span class="p">)</span>
    <span class="n">correct</span> <span class="o">+=</span> <span class="mi">1</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is incorrect!&quot;</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="n">getpass</span><span class="o">.</span><span class="n">getuser</span><span class="p">()</span> <span class="o">+</span> <span class="s2">&quot; you scored &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">correct</span><span class="p">)</span> <span class="o">+</span><span class="s2">&quot;/&quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">questions</span><span class="p">))</span>  <span class="c1"># print&#39;s user&#39;s score</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Hello, shruthim running /usr/bin/python3
You will be asked 3 questions.
Question: Are you ready to take a test?
Answer: yes
Question: What command is used to include other functions that were previously developed?
import is correct!
Question: What command is used to evaluate correct or incorrect response in this example?
if is correct!
Question: Each &#39;if&#39; command contains an &#39;_________&#39; to determine a true or false condition?
expression is correct!
shruthim you scored 3/3
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Creating-my-own-quiz-(based-on-CollegeBoard's-vocabulary):">Creating my own quiz (based on CollegeBoard's vocabulary):<a class="anchor-link" href="#Creating-my-own-quiz-(based-on-CollegeBoard's-vocabulary):"> </a></h2>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span> <span class="p">(</span><span class="s2">&quot;Hello World&quot;</span><span class="p">)</span>         <span class="c1"># image 1</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">msg</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Enter a greeting: &quot;</span><span class="p">)</span>          <span class="c1">#image 2</span>
<span class="nb">print</span><span class="p">(</span><span class="n">msg</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">getpass</span><span class="o">,</span> <span class="nn">sys</span>

<span class="k">def</span> <span class="nf">question_with_response</span><span class="p">(</span><span class="n">prompt</span><span class="p">):</span>     <span class="c1"># defines question_and_answer</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Question: &quot;</span> <span class="o">+</span> <span class="n">prompt</span><span class="p">)</span>        <span class="c1"># asks the question</span>
    <span class="n">msg</span> <span class="o">=</span> <span class="nb">input</span><span class="p">()</span>                       <span class="c1"># the user&#39;s input/answer is taken</span>
    <span class="k">return</span> <span class="n">msg</span>                          <span class="c1"># returns as string value</span>

<span class="n">questions</span> <span class="o">=</span> <span class="mi">5</span>            <span class="c1"># total number of questions</span>
<span class="n">correct</span> <span class="o">=</span> <span class="mi">0</span>              <span class="c1"># number that is initially correct (before any questions are answered)</span>

<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Hello, &#39;</span> <span class="o">+</span> <span class="n">getpass</span><span class="o">.</span><span class="n">getuser</span><span class="p">()</span> <span class="o">+</span> <span class="s2">&quot; running &quot;</span> <span class="o">+</span> <span class="n">sys</span><span class="o">.</span><span class="n">executable</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You will be asked &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">questions</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot; questions!&quot;</span><span class="p">)</span>
<span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;Are you ready to take this fun test on Python syntax?&quot;</span><span class="p">)</span>

<span class="n">rsp</span> <span class="o">=</span> <span class="n">question_with_response</span> <span class="p">(</span><span class="s2">&quot;In image 1, Hello, World is what kind of text?&quot;</span><span class="p">)</span>
<span class="k">if</span> <span class="n">rsp</span> <span class="o">==</span> <span class="s2">&quot;static&quot;</span> <span class="ow">or</span> <span class="n">rsp</span> <span class="o">==</span> <span class="s2">&quot;output&quot;</span><span class="p">:</span>      <span class="c1"># establishing if/else statement; if user&#39;s input is &quot;static&quot; or &quot;output&quot;</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is correct!&quot;</span><span class="p">)</span>       <span class="c1"># then it is correct</span>
    <span class="n">correct</span> <span class="o">+=</span> <span class="mi">1</span>                      <span class="c1"># one point is added to number correct score</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is incorrect :(&quot;</span><span class="p">)</span>   <span class="c1"># if user&#39;s input is not &quot;import,&quot; than user is incorrect</span>

<span class="n">rsp</span> <span class="o">=</span> <span class="n">question_with_response</span><span class="p">(</span><span class="s2">&quot;In image 1, what is the output?&quot;</span><span class="p">)</span>
<span class="k">if</span> <span class="n">rsp</span> <span class="o">==</span> <span class="s2">&quot;Hello World&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is correct!&quot;</span><span class="p">)</span>
    <span class="n">correct</span> <span class="o">+=</span> <span class="mi">1</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is incorrect :(&quot;</span><span class="p">)</span>

<span class="n">rsp</span> <span class="o">=</span> <span class="n">question_with_response</span><span class="p">(</span><span class="s2">&quot;In image 2, because the inputs and outputs can ______, the code is _______ &quot;</span><span class="p">)</span>
<span class="k">if</span> <span class="n">rsp</span> <span class="o">==</span> <span class="s2">&quot;change and dynamic&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is correct!&quot;</span><span class="p">)</span>
    <span class="n">correct</span> <span class="o">+=</span> <span class="mi">1</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is incorrect :(&quot;</span><span class="p">)</span>

<span class="n">rsp</span> <span class="o">=</span> <span class="n">question_with_response</span><span class="p">(</span><span class="s2">&quot;The variable, msg, is then used as a _______ to the print command&quot;</span><span class="p">)</span>
<span class="k">if</span> <span class="n">rsp</span> <span class="o">==</span> <span class="s2">&quot;parameter&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is correct!&quot;</span><span class="p">)</span>
    <span class="n">correct</span> <span class="o">+=</span> <span class="mi">1</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is incorrect :(&quot;</span><span class="p">)</span>

<span class="n">rsp</span> <span class="o">=</span> <span class="n">question_with_response</span><span class="p">(</span><span class="s2">&quot;What is it grouping a sequence of commands, often used repeatedly, called?&quot;</span><span class="p">)</span>
<span class="k">if</span> <span class="n">rsp</span> <span class="o">==</span> <span class="s2">&quot;procedural abstraction&quot;</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is correct!&quot;</span><span class="p">)</span>
    <span class="n">correct</span> <span class="o">+=</span> <span class="mi">1</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is incorrect :(&quot;</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="n">getpass</span><span class="o">.</span><span class="n">getuser</span><span class="p">()</span> <span class="o">+</span> <span class="s2">&quot; you scored &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">correct</span><span class="p">)</span> <span class="o">+</span><span class="s2">&quot;/&quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">questions</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot;!!&quot;</span><span class="p">)</span>     <span class="c1"># print&#39;s user&#39;s score</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Hello, shruthim running /usr/bin/python3
You will be asked 5 questions!
Question: Are you ready to take this fun test on Python syntax?
Answer: yes
Question: In image 1, Hello, World is what kind of text?
static is correct!
Question: In image 1, what is the output?
Hello World is correct!
Question: In image 2, because the inputs and outputs can ______, the code is _______ 
change and dynamic is correct!
Question: The variable, msg, is then used as a _______ to the print command
parameter is correct!
Question: What is it grouping a sequence of commands, often used repeatedly, called?
procedural abstraction is correct!
shruthim you scored 5/5!!
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

