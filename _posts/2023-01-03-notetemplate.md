---
keywords: fastai
title: Note Template
comments: true
nb_path: _notebooks/2022-12-1-notetemplate.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-12-1-notetemplate.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Take-some-additional-notes-that-you-would-like-here-for-3.12-and-3.13.-We-will-be-looking-for-additional-notes-from-the-presentation.">Take some additional notes that you would like here for 3.12 and 3.13. We will be looking for additional notes from the presentation.<a class="anchor-link" href="#Take-some-additional-notes-that-you-would-like-here-for-3.12-and-3.13.-We-will-be-looking-for-additional-notes-from-the-presentation."> </a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="What-are-procedures?">What are procedures?<a class="anchor-link" href="#What-are-procedures?"> </a></h1><p><strong>Fill in the blanks please:</strong></p>
<p>Procedure: a named group of programming instructions that may have parameters and return values.</p>
<p>Parameters:  input values of a procedure</p>
<p>Arguments: specify the values of the parameters when a procedure is called</p>
<p>Modularity: Separating a program's functions into independent pieces or blocks</p>
<p>Procedural Abstraction: provides a name for a process that allows a procedure to be used only knowing WHAT it does, not HOW it does it</p>
<p>What are some other names for procedures?: Functions and methods</p>
<p>Why are procedures effective?: Convenient to change errors, ability to alter the result without actually changing the calls to the program</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Additional-Notes">Additional Notes<a class="anchor-link" href="#Additional-Notes"> </a></h1><ul>
<li>procedures are functions</li>
<li>procedures simplify programs</li>
<li>procedures split tasks into individual components that need to be done</li>
<li>procedures have parameters (what the procedure is going to work on/convert/etc)</li>
<li>seperating program to procedures in order to simplify it is called modularity</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Challenge-1-below:-Add-the-command-that-will-call-the-procedure."><mark>Challenge 1</mark> below: Add the command that will <strong>call</strong> the procedure.<a class="anchor-link" href="#Challenge-1-below:-Add-the-command-that-will-call-the-procedure."> </a></h2>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">num</span> <span class="o">=</span> <span class="mi">7</span>
<span class="k">def</span> <span class="nf">convert</span><span class="p">(</span><span class="n">num</span><span class="p">):</span>
	
	<span class="k">if</span> <span class="n">num</span> <span class="o">&gt;=</span> <span class="mi">1</span><span class="p">:</span>
		<span class="n">convert</span><span class="p">(</span><span class="n">num</span> <span class="o">//</span> <span class="mi">2</span><span class="p">)</span>  <span class="c1"># double slash : divide the first number by the second, rounds to the nearest integer</span>
	<span class="nb">print</span><span class="p">(</span><span class="n">num</span> <span class="o">%</span> <span class="mi">2</span><span class="p">,</span> <span class="n">end</span> <span class="o">=</span> <span class="s1">&#39;&#39;</span><span class="p">)</span> <span class="c1"># end = &#39;&#39; signifies what will come between each printed num</span>
 
<span class="c1"># Driver Code</span>
<span class="n">convert</span><span class="p">(</span><span class="n">num</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>0111</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Challenge-2-below:-Complete-the-Min-and-Max-procedure-in-either-JavaScript-and-Python-using-the-instructions-from-the-JavaScript-page.-(JavaScript-will-get-you-a-extra-0.1)"><mark>Challenge 2</mark> below: Complete the Min and Max procedure in either JavaScript and Python using the instructions from the JavaScript page. (JavaScript will get you a extra 0.1)<a class="anchor-link" href="#Challenge-2-below:-Complete-the-Min-and-Max-procedure-in-either-JavaScript-and-Python-using-the-instructions-from-the-JavaScript-page.-(JavaScript-will-get-you-a-extra-0.1)"> </a></h2>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">findMax</span> <span class="o">=</span> <span class="n">function</span><span class="p">(</span><span class="n">numberA</span><span class="p">,</span> <span class="n">numberB</span><span class="p">){</span>
    <span class="k">if</span> <span class="p">(</span><span class="n">numberA</span><span class="o">&gt;</span><span class="n">numberB</span><span class="p">)</span> <span class="p">{</span>
        <span class="nb">max</span> <span class="o">=</span> <span class="n">numberA</span><span class="p">;</span>
    <span class="p">}</span> <span class="k">else</span> <span class="p">{</span>
        <span class="nb">max</span> <span class="o">=</span> <span class="n">numberB</span><span class="p">;</span>
    <span class="p">}</span>
    <span class="n">console</span><span class="o">.</span><span class="n">log</span><span class="p">(</span><span class="s2">&quot;The max is &quot;</span> <span class="o">+</span> <span class="nb">max</span><span class="p">);</span>
<span class="p">};</span>

<span class="n">findMin</span> <span class="o">=</span> <span class="n">function</span><span class="p">(</span><span class="n">numberA</span><span class="p">,</span> <span class="n">numberB</span><span class="p">){</span>
    <span class="k">if</span> <span class="p">(</span><span class="n">numberA</span><span class="o">&lt;</span><span class="n">numberB</span><span class="p">)</span> <span class="p">{</span>
        <span class="nb">min</span> <span class="o">=</span> <span class="n">numberA</span><span class="p">;</span>
    <span class="p">}</span> <span class="k">else</span> <span class="p">{</span>
        <span class="nb">min</span> <span class="o">=</span> <span class="n">numberB</span><span class="p">;</span>
    <span class="p">}</span>
    <span class="n">console</span><span class="o">.</span><span class="n">log</span><span class="p">(</span><span class="s2">&quot;The min is &quot;</span> <span class="o">+</span> <span class="nb">min</span><span class="p">);</span>
<span class="p">};</span>

<span class="n">findMax</span><span class="p">(</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">)</span>


<span class="n">findMin</span><span class="p">(</span><span class="mi">6</span><span class="p">,</span><span class="mi">10</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>The max is 3
The min is 6
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Homework/Hacks:-For-the-hw,-you-have-two-options,-easy-or-hard.-The-easy-hack-is-for-a-2.7-+-extra-work-for-the-full-3.-The-easy-hack-is-simply-creating-your-own-procedure-with-your-own-creativity.-Since-there-is-a-lot-of-leeway-for-this-one,-you-must-do-additional-work-to-get-a-3.-For-the-hard-hack,-below-is-the-start-to-a-character-to-binary-convertor.-This-is-just-a-template,-but-the-goal-is-to-translate-&quot;APCSP&quot;-into-binary.-You-can-delete-the-existing-code-if-you-want.-The-only-contraint-is-that-you-must-use-a-procedure.-Doing-this-will-get-you-a-3."><mark>Homework/Hacks</mark>: For the hw, you have two options, easy or hard. The easy hack is for a 2.7 + extra work for the full 3. The easy hack is simply creating your own procedure with your own creativity. Since there is a lot of leeway for this one, you must do additional work to get a 3. For the hard hack, below is the start to a character to binary convertor. This is just a template, but the goal is to translate "APCSP" into binary. You can delete the existing code if you want. The only contraint is that you must use a procedure. Doing this will get you a 3.<a class="anchor-link" href="#Homework/Hacks:-For-the-hw,-you-have-two-options,-easy-or-hard.-The-easy-hack-is-for-a-2.7-+-extra-work-for-the-full-3.-The-easy-hack-is-simply-creating-your-own-procedure-with-your-own-creativity.-Since-there-is-a-lot-of-leeway-for-this-one,-you-must-do-additional-work-to-get-a-3.-For-the-hard-hack,-below-is-the-start-to-a-character-to-binary-convertor.-This-is-just-a-template,-but-the-goal-is-to-translate-&quot;APCSP&quot;-into-binary.-You-can-delete-the-existing-code-if-you-want.-The-only-contraint-is-that-you-must-use-a-procedure.-Doing-this-will-get-you-a-3."> </a></h2>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">convert</span><span class="p">(</span><span class="n">num</span><span class="p">):</span>
    <span class="k">if</span> <span class="n">num</span> <span class="o">&gt;=</span> <span class="mi">1</span><span class="p">:</span>
        <span class="n">convert</span><span class="p">(</span><span class="n">num</span> <span class="o">//</span> <span class="mi">2</span><span class="p">)</span>  <span class="c1"># double slash : divide the first number by the second, rounds to the nearest integer</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">num</span> <span class="o">%</span> <span class="mi">2</span><span class="p">,</span> <span class="n">end</span> <span class="o">=</span> <span class="s1">&#39;&#39;</span><span class="p">)</span> <span class="c1"># end = &#39;&#39; signifies what will come between each printed num</span>


<span class="k">def</span> <span class="nf">wordtobin</span><span class="p">(</span><span class="n">word</span><span class="p">):</span>
    <span class="n">word</span> <span class="o">=</span> <span class="nb">str</span><span class="p">(</span><span class="n">word</span><span class="p">)</span>
    <span class="nb">list</span> <span class="o">=</span> <span class="p">[]</span>
    <span class="k">for</span> <span class="n">letter</span> <span class="ow">in</span> <span class="n">word</span><span class="p">:</span>
        <span class="nb">list</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">letter</span><span class="p">)</span>
    <span class="k">for</span> <span class="n">item</span> <span class="ow">in</span> <span class="nb">list</span><span class="p">:</span>
        <span class="n">index</span> <span class="o">=</span> <span class="nb">list</span><span class="o">.</span><span class="n">index</span><span class="p">(</span><span class="n">item</span><span class="p">)</span>
        <span class="n">new</span> <span class="o">=</span> <span class="nb">ord</span><span class="p">(</span><span class="n">item</span><span class="p">)</span>
        <span class="nb">list</span><span class="p">[</span><span class="n">index</span><span class="p">]</span> <span class="o">=</span> <span class="n">new</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">list</span><span class="p">:</span>
        <span class="n">z</span> <span class="o">=</span> <span class="nb">list</span><span class="o">.</span><span class="n">index</span><span class="p">(</span><span class="n">i</span><span class="p">)</span>
        <span class="n">new</span> <span class="o">=</span> <span class="n">convert</span><span class="p">(</span><span class="n">i</span><span class="p">)</span>
        <span class="nb">list</span><span class="p">[</span><span class="nb">int</span><span class="p">(</span><span class="n">z</span><span class="p">)]</span> <span class="o">=</span> <span class="n">new</span>

<span class="n">word</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;What word would you like to convert to binary?&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">word</span><span class="p">,</span> <span class="s2">&quot; to binary is:&quot;</span><span class="p">)</span>
<span class="n">wordtobin</span><span class="p">(</span><span class="n">word</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>APCSP  to binary is:
0100000101010000010000110101001101010000</pre>
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">word</span> <span class="o">=</span> <span class="s2">&quot;APCSP&quot;</span>
<span class="n">conversion</span> <span class="o">=</span> <span class="s1">&#39;-&#39;</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="nb">format</span><span class="p">(</span><span class="nb">ord</span><span class="p">(</span><span class="n">x</span><span class="p">),</span> <span class="s1">&#39;b&#39;</span><span class="p">)</span> <span class="k">for</span> <span class="n">x</span> <span class="ow">in</span> <span class="n">word</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">word</span> <span class="p">,</span> <span class="s2">&quot;to binary is:&quot;</span> <span class="p">,</span> <span class="n">conversion</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>APCSP to binary is: 1000001-1010000-1000011-1010011-1010000
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="The-Ord-Function">The Ord Function<a class="anchor-link" href="#The-Ord-Function"> </a></h3><ul>
<li>built in (don't have to import it)</li>
<li>It takes one character in input (unicode) and outputs decimal number</li>
<li>inverse of chr function</li>
</ul>

</div>
</div>
</div>
</div>
 
