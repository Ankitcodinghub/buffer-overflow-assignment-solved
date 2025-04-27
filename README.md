# buffer-overflow-assignment-solved
**TO GET THIS SOLUTION VISIT:** [Buffer Overflow Assignment Solved](https://www.ankitcodinghub.com/product/buffer-overflow-assignment-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;102168&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Buffer Overflow Assignment Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (5 votes)    </div>
    </div>
<strong>Look at main.c.&nbsp; Describe what it does.</strong>

<strong><em>Task 1 – Compile main.c</em></strong>

Compile the program using the following command:

<strong><em>gcc -o main&nbsp; main.c&nbsp; -g&nbsp; </em></strong>

Type in or copy/paste this command

Notice that you get a warning.

Show a screen shot with your name somewhere in the screenshot, the compile command, and the warning.

&nbsp;

<strong><em>Task 2 – Run main from the debugger, without causing buffer overflow</em></strong>

<strong>Use the following command to enter the debugger </strong>

<strong><em>gdb main</em></strong>

Set breakpoints with the following commands

&nbsp;

<strong><em>b get_input</em></strong>

<strong><em>b benign_function</em></strong>

<strong>&nbsp;</strong>

Run the following command

&nbsp;

<strong><em>disassemble main</em></strong>

&nbsp;

This provides the assembly ARM code that was created from the c code in main.&nbsp; It also provides the address in memory for each ARM instruction.

&nbsp;

Fill in the following table with the addresses of the branch and link instructions.&nbsp; Give the hexadecimal representation, not decimal. The address of the instruction is on the left.

<table>
<tbody>
<tr>
<td width="208"><strong>Instruction</strong></td>
<td width="208"><strong>Address</strong></td>
</tr>
<tr>
<td width="208">bl benign_function</td>
<td width="208"></td>
</tr>
<tr>
<td width="208">bl get_input</td>
<td width="208"></td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

Table 1

&nbsp;

Note that in the first line of the disassembly code that the stp function is run.&nbsp; stp is store pair and places two registers at the memory location given.&nbsp; &nbsp;x29 and x30 are placed on the stack.

What are x29 and x30?&nbsp; Why are they placed on the stack?

&nbsp;

Run the program with the following command

&nbsp;

<strong><em>r</em></strong>

<strong><em>&nbsp;</em></strong>

You are now at the first line of benign_function.&nbsp; Display hexadecimal register values with the following command.

&nbsp;

<strong><em>i r</em></strong>

<strong><em>(hit enter to see the rest of the registers)</em></strong>

<strong><em>&nbsp;</em></strong>

Fill in the following table with register values (hexadecimal not decimal)

<table>
<tbody>
<tr>
<td width="208">Register</td>
<td width="208">Value</td>
</tr>
<tr>
<td width="208">x29</td>
<td width="208"></td>
</tr>
<tr>
<td width="208">x30</td>
<td width="208"></td>
</tr>
<tr>
<td width="208">SP</td>
<td width="208"></td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Table 2

&nbsp;

&nbsp;

We are now in the function benign_function.&nbsp; When benign_function was called, new values were written into the x29 and x30 registers. Before benign_function was called, the previous values of the x29 and x30 registers were saved on the stack.

&nbsp;

We have two stack frames on the stack right now, one for main, and one for benign_function.&nbsp; The values of x29 and sp in table 2 above are the boundaries of benign_function’s stack frame.&nbsp; The stack frame for main should have the values of x29 and x30 when the program first started.&nbsp; (Recall that we saw in the disassembly where these values got written to the stack.)

&nbsp;

Look at the contents of the stack with the following command

&nbsp;

<strong><em>x/4gx $sp</em></strong>

&nbsp;

Note that the TOP of the stack is in the TOP row of the table.&nbsp; So benign_function stack frame is at the top, then main stack frame.

&nbsp;

You can figure out the boundaries of each stack frame using the current values of stack pointer and frame pointer, and by noticing the frame pointer value placed on the stack at the beginning of main.

&nbsp;

Each row in the following table represents 16 bytes starting at the address shown.&nbsp; Copy the values for the bytes into Table 3.&nbsp; Each column with a value is 8 bytes.&nbsp; A register is 8 bytes.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<table>
<tbody>
<tr>
<td width="174">Memory Address</td>
<td width="186">Value</td>
<td width="233">Value</td>
</tr>
<tr>
<td width="174"></td>
<td width="186"></td>
<td width="233"></td>
</tr>
<tr>
<td width="174"></td>
<td width="186"></td>
<td width="233"></td>
</tr>
</tbody>
</table>
Table 3

&nbsp;

&nbsp;

Figure 2

&nbsp;

Figure 2 shows a schematic of the stack frames.&nbsp; Using the values you entered into Table 2, what are the addresses pointed to by A and B in Figure 2?

&nbsp;

Given this information, use the values you entered into Table 3 to determine the previous values of x29 and x30 when they were written to the stack frame early in the execution of main:

&nbsp;

&nbsp;

Using this information, what is the address pointed to by C in Figure 2?

&nbsp;

&nbsp;

Type <strong><em>n</em></strong> repeatedly until you have entered get_input, main.c:45

&nbsp;

Type

&nbsp;

<strong><em>i r</em></strong>

&nbsp;

Fill in the following table with hexadecimal register values

<table>
<tbody>
<tr>
<td width="208">Register</td>
<td width="208">Value</td>
</tr>
<tr>
<td width="208">x29</td>
<td width="208"></td>
</tr>
<tr>
<td width="208">x30</td>
<td width="208"></td>
</tr>
<tr>
<td width="208">SP</td>
<td width="208"></td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Table 4

&nbsp;

Type <strong><em>n </em></strong>repeatedly until the program is waiting for input.

&nbsp;

<strong>Type in the first 8 characters of your name and hit enter.</strong>

Now type <strong><em>x/6gx $sp</em></strong>

<strong><em>&nbsp;</em></strong>

Fill in the following table.

&nbsp;

<table>
<tbody>
<tr>
<td width="144">Memory Address</td>
<td width="192">Value</td>
<td width="266">Value</td>
</tr>
<tr>
<td width="144"></td>
<td width="192"></td>
<td width="266"></td>
</tr>
<tr>
<td width="144"></td>
<td width="192"></td>
<td width="266"></td>
</tr>
<tr>
<td width="144"></td>
<td width="192"></td>
<td width="266"></td>
</tr>
</tbody>
</table>
Table 5

&nbsp;

What does the data in memory shown in the top row represent?&nbsp; (What registers have been saved to memory?)

&nbsp;

Circle or highlight the input you typed. (For reference, A will show up as 41, B as 42, and so on).

&nbsp;

Type <strong><em>n</em></strong> enough times to finish execution.

Note that the program exited normally.

&nbsp;

<strong><em>Task 3 – Run main.c from the debugger, causing buffer overflow</em></strong>

<strong>Type </strong><strong><em>r </em></strong><strong>to run the program again</strong>

<strong>Type </strong><strong><em>n</em></strong><strong> repeatedly until the program is waiting for input.</strong>

<strong>Input a string that is 18 characters and press enter.&nbsp; </strong>

<strong>Type </strong><strong><em>n</em></strong>

<strong>Type </strong>

<strong><em>x/6gx $sp</em></strong>

<strong><em>&nbsp;</em></strong>

Fill in the following table

&nbsp;

<table>
<tbody>
<tr>
<td width="138">Memory Address</td>
<td width="90">Value</td>
<td width="90">Value</td>
</tr>
<tr>
<td width="138"></td>
<td width="90"></td>
<td width="90"></td>
</tr>
<tr>
<td width="138"></td>
<td width="90"></td>
<td width="90"></td>
</tr>
<tr>
<td width="138"></td>
<td width="90"></td>
<td width="90"></td>
</tr>
<tr>
<td width="138"></td>
<td width="90"></td>
<td width="90"></td>
</tr>
<tr>
<td width="138"></td>
<td width="90"></td>
<td width="90"></td>
</tr>
</tbody>
</table>
Table 6

<strong>What has happened to our stack frame for main</strong>?

Type <strong><em>n</em></strong> repeatedly until you get some question marks

Display register values with the following command

&nbsp;

<strong><em>i r</em></strong>

&nbsp;

Fill in the following table with register values

<table>
<tbody>
<tr>
<td width="208">Register</td>
<td width="208">Value</td>
</tr>
<tr>
<td width="208">x29</td>
<td width="208"></td>
</tr>
<tr>
<td width="208">x30</td>
<td width="208"></td>
</tr>
<tr>
<td width="208">SP</td>
<td width="208"></td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Table 7</strong>

<strong>&nbsp;</strong>

<strong>What happened to our x29 and x30 value?</strong>

<strong>Type </strong><strong><em>n</em></strong>

<strong>What is the result?&nbsp; Why did this happen?</strong>

<strong>Type </strong><strong><em>q</em></strong>

<strong>Type </strong><strong><em>y</em></strong>

<strong><em>Task 4 – record address for arbitrary_code function</em></strong>

<strong>Now we are going to record the starting address for the arbitrary_code function.&nbsp; We are going to craft a buffer overflow attack that causes the x30 value that main saved to the stack to be overwritten with this address.</strong>

<strong>Type </strong><strong><em>gdb main</em></strong>

<strong>Type </strong><strong><em>disassemble arbitrary_code</em></strong>

<strong>What is the address in memory of the first line of the arbitrary_code function?</strong>

<strong>Type </strong><strong><em>q</em></strong><strong> to exit the debugger</strong>

<strong><em>Task 5 – Run main from command line, overflow the buffer</em></strong>

Now we’re back at the command line.

Run the main executable.

<strong><em>./main</em></strong>

Provide input that is 20 characters.&nbsp; What happens?

Provide a screen shot with your name somewhere in the screen shot, the command to run main, and the result.

<strong><em>Task 6 – Run main from command line, craft input to main to execute arbitrary_code function</em></strong>

We’re going to have the program jump to our arbitrary code function.

<strong>Type </strong><strong><em>echo 0 &gt; /proc/sys/kernel/randomize_va_space</em></strong>

This command turns off ASLR.&nbsp; Research this and describe what it is and why we need to do this to make arbitrary_code function run.

&nbsp;

Now we will put an address into the buffer.&nbsp; We need to send hex characters.&nbsp; Do this with a command like this:

<strong><em>echo -e “ABCDEFGHIJKLMNOP\x78\xa8\xaa\xaa\xaa\xaa” | ./main</em></strong>

This pipes input to your program.&nbsp; The \x indicates a hex byte is coming.&nbsp; Craft your input so it goes to the address for arbitrary_code that you recorded in Task 3.&nbsp; Since we are doing little endian, the address has to be backwards in bytes.

What happens?

(Control C to make execution stop)

<strong>Task 7 – Turn ASLR back on</strong>

Type <strong><em>echo 1 &gt; /proc/sys/kernel/randomize_va_space</em></strong>

Type <strong><em>echo -e “ABCDEFGHIJKLMNOP\x78\xa8\xaa\xaa\xaa\xaa” | ./main</em></strong>

<strong>What happens?</strong>

<strong>&nbsp;Task 8 – Fix the vulnerability</strong>

Write a new version of main.c, where gets(buffer) is replaced with fgets(buffer, 8, stdin)

Run your new main function with an input greater than 8 characters.&nbsp; What happens?

<strong><em>Task 9</em></strong>

Go to https://cve.mitre.org

Find a stack buffer overflow vulnerability.&nbsp; Give the CVE number, the name of the vulnerability and the affected software.Look at the reference.&nbsp; How was it reported (e.g. GitHub, SourceForge)?&nbsp; Briefly describe the vulnerability (one sentence).&nbsp; Why do you think there are still vulnerabilities like this?

<strong>&nbsp;</strong>

&nbsp;
