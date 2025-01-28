# NACHA ACH parser
This simple sattic HTML website with some JavaScript will parser your NACHA ACH payment instruction files. No dependencies were used in creating this project.

You can try it [here](https://imretomosvari.github.io/ach-parser-web/) with this completely fake file:

```
101 77665544311223344552401290600A094101SOME COOL BANK         MY COOL BANK           00000000
5225MY COOL BANK    1                   1122334455WEBBANK      240129240129   1112333440000001
6270210000211111111111       0000050000reference-1    John H Smith            0112333440000001
822500000100021334320000000500000000000000001122334455                         112333440000001
5225MY COOL BANK    4                   1122334455WEBBANK      240129240129   1112333440000002
6370260730081234111333       0000050000reference-1    John H Smith            0112333440000002
822500000100028173400000000500000000000000001122334455                         112333440000002
9000002000002000000020614307420000000550000000000000000
9999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999
9999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999
```

I advise not to input real files on the github hosted version, but you can download the index.html, and run it in your own browser from your computer.

**Currently works with:**
- Domestic ACH files as described [here](https://achdevguide.nacha.org/ach-file-details)


# Disclaimer
I take no responsibility for the correctness of the parsing. While I try my best to validate it, mistakes happen
