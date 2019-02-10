# pmars-round-change <br />
Patch for pmars-0.9.2 to increase amount of rounds possible. <br />
Example: <br />
pmars -r 100000 &lt;warrior1&gt; &lt;warrior2&gt; <br />
It is possible to use a million rounds now though the example uses one hundred thousand. <br />

To patch put in same directory as the src directory. <br />
For Linux: <br />
patch -p1 < pmars.diff <br />
<br />
For Minix 3: <br />
patch -p1 < pmars-minix3.diff <br />

For clang on Linux:
To patch put in same directory as the directory of the src directory <br />
patch -p1 < pmars-clang.diff

