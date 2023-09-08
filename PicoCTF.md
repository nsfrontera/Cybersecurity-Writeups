<H1> PicoCTF: </H1>
  <H3> 1. Magikarp Ground Mission: </H3>
    <H5>Used the command "ls" to see the various folders, and found 2 items in this initial directory, one being part of the flag and a hint to the next flag.</H5>
    <H5>Then I followed said instructions where I "ls" after using "cd" to find the second key and also found the hint for the third and last part of the flag.</H5>
  <H3> 2. Let's Warm Up: </H3>
    <H5>Searched online an ASCII table and used it to translate the hex to words.</H5>
  <H3> 3. Warmed Up: </H3>
    <H5>Found online an converter to convert 0x3D to decimal to find the flag.</H5>
  <H3> 4. 2Warm: </H3>
    <H5>Used an online converter to get the 42(base 10) to binary.</H5>
  <H3> 5. Wave a Flag: </H3>
    <H5>Downloaded the file warm and tried to run it but I was missing permission</H5>
    <H5>Then I used "chmod+x warm" to gain permission</H5>
    <H5>Open the file using "./warm -b" and got the flag</H5>
  <H3> 6. Nice netcat...: </H3>
    <H5>Ran the command "NC mercury.picoctf.net 22342"</H5>
    <H5> It displayed a big list of numbers where I opened an ASCII chart to manually convert them for learning purposes</H5>
    <H5>Which got me the flag</H5>
  <H3> 7. Tab, Tab, Attack: </H3>
    <H5>Downloaded the file Addadshanammu.zip</H5>
    <H5>Unziped the file</H5>
    <H5>I CD into the file and kept pressing Tab to autocomplete the directories names</H5>
    <H5>Where I then found a file that had the flag</H5>
  <H3> 8. Python Wrangling: </H3>
    <H5>Downloaded the 3 files: ende.py, pw.txt and flag.txt</H5>
    <H5>Opened pw.txt to get the password</H5>
    <H5> Ran the python script using the password and giving it the flag.txt to gain the flag</H5>
  <H3> 9. Obedient Cat: </H3>
    <H5>Opened the flag.txt using cat to reveal the flag</H5>
  <H3> 10. Static ain't always noise: </H3>
    <H5> downloaded 2 files: itdis.sh and static</H5>
    <H5> Tried to running itdis.sh but was missing permission so I ran "chmod +x itdish.sh"</H5>
    <H5> then I ran the file "./itdish.sh static" which created a new file</H5>
    <H5>After reading the file in a mess of sentences I found the flag</H5>
  <H3> 11. what's a net cat?: </H3>
    <H5>I used this command "nc jupiter.challenges.picoctf.org 41120"</H5>
    <H5>Which gave me the flag</H5>
  <H3> 12. Bases: </H3>
    <H5> Was given  this string to decipher "bDNhcm5fdGgzX3IwcDM1"</H5>
    <H5>Which I found an online decoder for base64 which gave me the flag</H5>
