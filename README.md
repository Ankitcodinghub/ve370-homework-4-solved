# ve370-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [VE370 Homework 4 Solved](https://www.ankitcodinghub.com/product/ve370-homework-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99100&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;VE370 Homework 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<ol>
<li>&nbsp;Given this instruction:
lw x5, -4(x2)

As the instruction goes through the pipeline, what will be stored in the pipeline registers: IF: what’s in PC

ID: what’s in IF/ID

EX: what’s in ID/EX?

MEM: what’s in EX/MEM WB: what’s in MEM/WB?
</li>
<li>Assume that individual stages of the RISC-V pipelined datapath have the following latencies:
IF ID EX MEM WB 250ps 350ps 150ps 300ps 200ps
</li>
</ol>
Also, assume that instructions executed by the processor are broken down as follows:

ALU/Logic Jump/Branch Load Store 45% 20% 20% 15%

<ol>
<li>(1) &nbsp;What is the clock cycle time? (2 points)</li>
<li>(2) &nbsp;What is the execution time of a sw instruction in the pipelined processor? (3 points)</li>
<li>(3) &nbsp;If we can split one stage of the pipelined datapath into two new stages, each with half the
latency of the original stage, which stage would you split and what is the new clock cycle

time of the processor? (5 points)
</li>
<li>(4) &nbsp;Using the processor to run a program of 1,000 instructions, what is the total execution time?
What is the CPI? (10 points)
</li>
</ol>
3. (10 points) Assume that x11 is initialized to 11 and x12 is initialized to 22. Suppose you executed the code below on a pipelined processor that does not handle data hazards at all. L1: addi x11, x12, 5

L2: add x13, x12, x11

<pre>  L3: addi x14, x11, 15
</pre>
(1) Indicate data dependencies, if any, in above instruction sequence. (which register between which instructions) (5 points)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
(2) What would the final values of registers x13 and x14 be? (5 points)

<ol start="4">
<li>(30 points) Given the following instructions:
<pre>  L1: sw  x18,–12(x8)
  L2: lw  x3,8(x18)
  L3: add x6,x3,x3
  L4: or  x8,x9,x6
</pre>
<ol>
<li>a) &nbsp;Assume there is no forwarding in this pipelined processor. Indicate hazards and add NOP instructions to eliminate them. How many clock cycles will it take to execute the instructions? (10 points)</li>
<li>b) &nbsp;Assume there is ALU-ALU forwarding. Indicate hazards and add NOP instructions to eliminate them. How many clock cycles will it take to execute the instructions? (10 points)</li>
<li>c) &nbsp;Assume there is full forwarding. Indicate hazards and add NOP instructions to eliminate them. How many clock cycles will it take to execute the instructions? (10 points)</li>
</ol>
</li>
<li>(25 points) Given this assembly instruction sequence executed by the pipelined processor:
<pre>  sub x6, x2, x1
  lw  x3, 8(x6)
  lw  x2, 0(x6)
  or  x3, x5, x3
  sw  x3, 0(x5)
</pre>
<ol>
<li>a) &nbsp;If the processor has forwarding, but we forgot to implement the hazard detection unit, what
happens when this code executes? (5 points)
</li>
<li>b) &nbsp;If there is forwarding, for the first five cycles during the execution of this code, specify
which signals are asserted in each cycle by hazard detection and forwarding units. (10

points)
</li>
<li>c) &nbsp;If there is no forwarding, what new inputs and output signals do we need for the hazard
detection unit? Using this instruction sequence as an example, explain why each signal is needed. (10 points)
</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
