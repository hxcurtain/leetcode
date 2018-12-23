<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    Openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

## 483. Smallest Good Base (Hard)

<p>For an integer n, we call k>=2 a <i><b>good base</b></i> of n, if all digits of n base k are 1.</p>
<p>Now given a string representing n, you should return the smallest good base of n in string format. <br/></p>

<p><b>Example 1:</b><br />
<pre>
<b>Input:</b> "13"
<b>Output:</b> "3"
<b>Explanation:</b> 13 base 3 is 111.
</pre>
</p>

<p><b>Example 2:</b><br />
<pre>
<b>Input:</b> "4681"
<b>Output:</b> "8"
<b>Explanation:</b> 4681 base 8 is 11111.
</pre>
</p>

<p><b>Example 3:</b><br />
<pre>
<b>Input:</b> "1000000000000000000"
<b>Output:</b> "999999999999999999"
<b>Explanation:</b> 1000000000000000000 base 999999999999999999 is 11.
</pre>
</p>

<p><b>Note:</b><br>
<ol>
<li>The range of n is [3, 10^18].</li>
<li>The string representing n is always valid and will not have leading zeros.</li>
</ol>
</p>