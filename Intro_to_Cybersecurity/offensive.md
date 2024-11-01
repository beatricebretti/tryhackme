Use GoBuster to find hidden website pages
`gobuster -u http://fakebank.thm -w wordlist.txt dir`
In the command above, `-u` is used to state the website we're scanning, `-w` takes a list of words to iterate through to find hidden pages.

Should have found a secret bank transfer page that allows you to transfer money between bank accounts `/bank-transfer`

answer: `BANK-HACKED`