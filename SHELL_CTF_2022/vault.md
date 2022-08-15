# VAULT begginer reverse challenge

Reverse the given binary file with [Gihdra][gihdra_link]

![alt text][gihdra_decomp]

Take a look at the code and see the following

![alt text][gihdra_decomp_explained]

The programm takes the input and compares it with **0x10f2c** after which the **string** at local_78 is printed.

So possibly the **Flag** is local_78.

local_78 and following variables look like a struct of some kind.

We think it looks like this.

![alt text][flag_struct]

So we create a struct in [Gihdra][gihdra_link] and reverse the programm a bit more.

![alt text][gihdra_reversed]   

[gihdra_link]: https://ghidra-sre.org/ "gihdra link"
[gihdra_reversed]: https://github.com/DJMucki/Writeups/blob/main/SHELL_CTF_2022/.images/gihdra_reversed.png "gihdra reversed"
[gihdra_decomp]: https://github.com/DJMucki/Writeups/blob/main/SHELL_CTF_2022/.images/gihdra_decomp.png "gihdra decomp image"
[gihdra_decomp_explained]: https://github.com/DJMucki/Writeups/blob/main/SHELL_CTF_2022/.images/gihdra_explained.png "gihdra decomp image explained"
[flag_struct]: https://github.com/DJMucki/Writeups/blob/main/SHELL_CTF_2022/.images/flag_struct.png "flag struct" 