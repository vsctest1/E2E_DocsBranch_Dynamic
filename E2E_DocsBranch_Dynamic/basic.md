# Basic Markdown Syntax Test Page - P1 Scenario

# Heading Syntax
Heading1_1
==
Heading2_1
--

# Heading1_2
## Heading2_2
### Heading3
#### Heading4
##### Heading5
###### Heading6

# Bold Syntax
**Bold1**
__Bold2__

# Italic Syntax
*Italic1*
_Italic2_

# Bold & Italic Syntax
***Bold&Italic1***
**_Bold&Italic2_**
__*Bold&Italic3*__
___Bold&Italic4___

# Blockquote Syntax
## 510056 - Verify blockquote syntax of insert blockquote with ">"
>aaa   
> bbb   
> ccc

## 510057 - Verify blockquote syntax of insert different ">"
>aaa   
>> bbb   
> ccc   

## 510058 - verify the blockquote syntax: nested with other element
>1. *aaa*   
>**bbb**   
>
>* ___ccc___ 


# Bulleted list Syntax
## 510059 - erify the bulleted list syntax start with "*"/"+"/"-"
### with "*"
* aaa
* bbb
* ccc

### with "+"
+ aaa
+ bbb
+ ccc

### with "-"
- aaa
- bbb
- ccc

### with "*+-"
* aaa
+ bbb
- ccc

## 510060 - Verify the bulleted list syntax: the max number of space in the indent after the "*"/"+"/"-"
### 3 spances
   * aaa
   * bbb
   * ccc

### 4 spances
    * aaa
    * bbb
    * ccc

## 510061 - Verify the bulleted list syntax: error when no indenting after "*"/"+"/"-"
*aaa   
*bbb   
*ccc   

## 510062 - Verify the bulleted list syntax: the max number of space in the indent between tag and message
### 4 spaces
*    aaa
*    bbb
*    ccc

### 1 tab
*	aaa
*	bbb
*	ccc

### 5 spaces
*     aaa
*     bbb
*     ccc

### 2 tabs
*		aaa
*		bbb
*		ccc

# Ordered list Syntax
## 510063 - Verify the ordered list syntax: Start with number and a dot
## Ordered list1
1. aaa
2. bbb
3. ccc

## 510064 - Verify the ordered list syntax: the list numbers are not ordered
1. aaa
5. bbb
7. ccc

## 510065 - Verify the ordered list syntax: the max number of space in the indent between tag and message
### 4 spaces
1.    aaa
2.    bbb
3.    ccc

### 1 tab
1.	aaa
2.	bbb
3.	ccc

### 5 spaces
1.     aaa
2.     bbb
3.     ccc

### 2 tabs
1.		aaa
2.		bbb
3.		ccc

# Nested list Syntax
## 510066 - Verify nested list syntax: Indent with ">" for sub list
 1. aaa

 >2. bbb
 
 >5. ccc
 
 3. ddd

# Mark Syntax
## 510081 - Verify the mark syntax is available
Use the `printf()` function.

## 510082 - Verify the mark syntax: mark words/sentences in marked sentences
``There is a literal backtick (`printf()`) here.``

# Escape Syntax
## 510089
\*literal asterisks\*      

\`literal asterisks\`  

\_literal asterisks\_   

# Split line Syntax
## 510068 - Verify the Split Line with  3 or more "*"/"-"/"_"
111

***
222

------
333

___
444

*-_

## 510069 - Verify the Split Line: other character except space is not allowed in Split line
* *   *
1*2*3*
1* * *

# Table Syntax
 | Tables        | Are           | Cool  |
 | ------------- |:-------------:| -----:|
 | col 3 is      | right-aligned | $1600 |
 | col 2 is      | centered      |   $12 |
 | zebra stripes | are neat      |    $1 |

## 510072 - Insert table with blank lines
 | Tables        | Are           | Cool  |
 | ------------- |:-------------:| -----:|
 | col 3 is      | right-aligned | $1600 |

 | col 2 is      | centered      |   $12 |
 | zebra stripes | are neat      |    $1 |
 
## 510073 - Content of each line unaligned
| Tables        | Are           | Cool  |
                                | ------------- |:-------------:| -----:|
            | col 3 is      | right-aligned | $1600 |
                                            | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |
    
## 510074 - Align Right + Align Left + Align Center
| Tables        | Are           | Cool  |
| -------------: |:-------------|:-----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## 510075 - No content Line with only dash
 | Tables        | Are           | Cool  |
 | ------------- |:-------------:| -----:|
 | col 3 is      | right-aligned | $1600 |
 | | | |
 | col 2 is      | centered      |   $12 |
 | zebra stripes | are neat      |    $1 |

# Image Syntax
![Image](https://www.baidu.com)