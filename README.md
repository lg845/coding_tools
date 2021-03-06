# Coding Tools
Crow tools to assist human coders with coding and tag checking.

## Crow Output Coding Tool

[Open Coding Tool](http://htmlpreview.github.io/?https://github.com/writecrow/coding_tools/blob/master/Crow%20Output%20Coding%20Tool/index.html)

Input files: csv files exported (i.e., downloaded) from Crow online platform.

Output file: tab separated text file that can be opened using Excel

## Subset tag Checker

[Open Tag Checker](http://htmlpreview.github.io/?https://github.com/writecrow/coding_tools/blob/master/subset_tag_checker/index.html)

Input files: text files tagged with Biber tagger (one token per line, each line contains token and Biber tag separated by space)

Output file: tab separated text file that can be opened using Excel

The tool highlights a subset of tags (the regex to grab these tags can be found on line 112, filter variable), in case the human tag checker needs to change that tag. 

## That tag Checker
[Open Tag Checker](http://htmlpreview.github.io/?https://github.com/writecrow/coding_tools/blob/master/that_tag_checker/index.html)

Input files: text files tagged with Biber tagger (one token per line, each line contains token and Biber tag separated by space)

Output file: tab separated text file that can be opened using Excel

The tool highlights all "that" tags (every tag that contains that, omitted or not) and lists all possible that tags, in case the human tag checker needs to change that tag. Multiple text files can be loaded at once.

![alt text](https://github.com/writecrow/coding_tools/blob/master/that_tag_checker/screenshot.png)

## Citation Coder
[Open Citation Coder](http://htmlpreview.github.io/?https://github.com/writecrow/coding_tools/blob/master/citation_coder/index.html)

Input files: plain text files with optional metadata (i.e., all information between angled brackets: <metadata>)
  
Output file: tab separated text file that can be opened using Excel
  
The tool separates the texts into individual sentence. Each sentence can be coded as containing a reference to an external source. Then, if that is the case, it can be codes as Integral, Non-Integral, or Hybrid. References can also be tagged

![alt text](https://github.com/writecrow/coding_tools/blob/master/citation_coder/screenshot_citationcoder.png)
