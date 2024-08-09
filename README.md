## TermsConversionAssistant TOOLS


### Structure

-- TermsConversionAssistant.exe

-- originalText.txt

-- TermsTemplate.excel



### How to use it
Open CMD command line：
	
```
TermsConversionAssistant.exe -t [txt path] -e [excel file path]
```

```
TermsConversionAssistant.exe -t originalText.txt -e TermsTemplate.excel
```

### Regarding "TermsTemplate.excel"
**The first row of this Excel is the header, please be careful not to modify it. **
Starting from the second row, add the corresponding string you want to change.


### Result
A new TXT file is generated：**fileNew.txt**
