## The Game

### Scenario:
<p> Cipher has gone dark, but intel reveals he’s hiding critical secrets inside Tetris, a popular video game. Hack it and uncover the encrypted data buried in its code. </p>

## Solution:
<img width="648" height="45" alt="image" src="https://github.com/user-attachments/assets/3f9a68cb-ec26-49ed-a8d8-858a6648d6d0" />
<p> I downloaded the zip file to my parrot OS vm. From there, I went to the folder where the executable is located. </p>

<img width="656" height="77" alt="image" src="https://github.com/user-attachments/assets/1a13c3ca-065f-41e5-9e46-bad71d70989f" />

Afterwards, I used the command **"strings -n 6 Tetrix.exe| grep -i "THM{"** to locate the flag.

<ul>
  <li>**strings**: scan binary fiule and looks for printable char</li>
  <li>**-n 6**: show string that are atleast 6 char long</li>
  <li>**|**: take input from strings and feed to the next input</li>
  <li>**grep**: search pattern of text</li>
  <li>**-i**: makes teh search case sentive</li>
</ul>
