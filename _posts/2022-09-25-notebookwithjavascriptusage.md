---
keywords: fastai
description: Using Jupyter JavaScript kernel
title: Using JavaScript
nb_path: _notebooks/2022-09-25-notebookwithjavascriptusage.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-25-notebookwithjavascriptusage.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-javascript"><pre><span></span><span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="s2">&quot;Fruits&quot;</span><span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Fruits
</pre>
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
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">var</span> <span class="nx">msg</span> <span class="o">=</span> <span class="s2">&quot;I love fruits&quot;</span><span class="p">;</span>
<span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="nx">msg</span><span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>I love fruits
</pre>
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
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">function</span> <span class="nx">Fruit</span><span class="p">(</span><span class="nx">name</span> <span class="p">,</span> <span class="nx">color</span><span class="p">)</span> <span class="p">{</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">name</span> <span class="o">=</span> <span class="nx">name</span><span class="p">;</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">color</span> <span class="o">=</span> <span class="nx">color</span><span class="p">;</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">role</span> <span class="o">=</span> <span class="s2">&quot;&quot;</span><span class="p">;</span>
<span class="p">}</span>

<span class="nx">Fruit</span><span class="p">.</span><span class="nx">prototype</span><span class="p">.</span><span class="nx">setRole</span> <span class="o">=</span> <span class="kd">function</span><span class="p">(</span><span class="nx">role</span><span class="p">)</span> <span class="p">{</span>
    <span class="k">this</span><span class="p">.</span><span class="nx">role</span> <span class="o">=</span> <span class="nx">role</span><span class="p">;</span>
<span class="p">}</span>

<span class="nx">Fruit</span><span class="p">.</span><span class="nx">prototype</span><span class="p">.</span><span class="nx">toJSON</span> <span class="o">=</span> <span class="kd">function</span><span class="p">()</span> <span class="p">{</span>
    <span class="kr">const</span> <span class="nx">obj</span> <span class="o">=</span> <span class="p">{</span><span class="nx">name</span><span class="o">:</span> <span class="k">this</span><span class="p">.</span><span class="nx">name</span><span class="p">,</span> <span class="nx">color</span><span class="o">:</span> <span class="k">this</span><span class="p">.</span><span class="nx">color</span><span class="p">};</span>
    <span class="kr">const</span> <span class="nx">json</span> <span class="o">=</span> <span class="nx">JSON</span><span class="p">.</span><span class="nx">stringify</span><span class="p">(</span><span class="nx">obj</span><span class="p">);</span>
    <span class="k">return</span> <span class="nx">json</span><span class="p">;</span>
<span class="p">}</span>

<span class="kd">var</span> <span class="nx">x</span> <span class="o">=</span> <span class="k">new</span> <span class="nx">Fruit</span><span class="p">(</span><span class="s2">&quot;Apple&quot;</span><span class="p">,</span> <span class="s2">&quot;red&quot;</span><span class="p">);</span>
<span class="nx">logItType</span><span class="p">(</span><span class="nx">x</span><span class="p">);</span>
<span class="nx">logItType</span><span class="p">(</span><span class="nx">x</span><span class="p">.</span><span class="nx">toJSON</span><span class="p">());</span>

<span class="nx">scrollX</span><span class="p">.</span><span class="nx">setRole</span><span class="p">(</span><span class="s2">&quot;x&quot;</span><span class="p">);</span> 
<span class="nx">logItType</span><span class="p">(</span><span class="nx">x</span><span class="p">);</span> 
<span class="nx">logItType</span><span class="p">(</span><span class="nx">x</span><span class="p">.</span><span class="nx">toJSON</span><span class="p">());</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

</div>
 

