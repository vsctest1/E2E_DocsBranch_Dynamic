# Basic Markdown Syntax Test Page

# Heading Syntax
***
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
***
**Bold1**
__Bold2__

# Italic Syntax
*Italic1*
_Italic2_

# Bold & Italic Syntax
***
***Bold&Italic1***
**_Bold&Italic2_**
__*Bold&Italic3*__
___Bold&Italic4___

# Blockquote Syntax
***
## 510056-p1-null
>aaa   
> bbb   
> ccc

## 510057-p3-null
>aaa   
>>bbb   
>ccc   

## 510058-p2-null
>1. *aaa*   
>**bbb**   
>
>* ___ccc___ 


# Bulleted list Syntax
***
## 510059-p1-null
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

## 510060-p3-null
### 3 spaces
   * aaa
   * bbb
   * ccc

### 4 spaces
    * aaa
    * bbb
    * ccc

## 510061-p3-null
*aaa
*bbb
*ccc

## 510062-p3-null
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
***
## 510063-p3-null
## Ordered list1
1. aaa
2. bbb
3. ccc

## 510064-p2-null
1. aaa
5. bbb
7. ccc

## 510065-p3-null
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
***
## 510066-p2-null
1. aaa   
>2. bbb
>5. ccc
3. ddd

# Mark Syntax
***
## 510081 - Verify the mark syntax is available
Use the `printf()` function.

## 510082 - Verify the mark syntax: mark words/sentences in marked sentences
``There is a literal backtick (`printf()`) here.``

# Escape Syntax
***
## 510089
\*literal asterisks\*      

\`literal asterisks\`  

\_literal asterisks\_   

# Split line Syntax
***
## 510068-p1
111

***
222

------
333

___
444

*-_

## 510069-p3-null
* *   *
1*2*3*
1* * *

# Table Syntax
***
## 510070-p1
 | Tables        | Are           | Cool  |
 | ------------- |:-------------:| -----:|
 | col 3 is      | right-aligned | $1600 |
 | col 2 is      | centered      |   $12 |
 | zebra stripes | are neat      |    $1 |

## 510072-p3-null
 | Tables        | Are           | Cool  |
 | ------------- |:-------------:| -----:|
 | col 3 is      | right-aligned | $1600 |

 | col 2 is      | centered      |   $12 |
 | zebra stripes | are neat      |    $1 |
 
## 510073-p3-null
| Tables        | Are           | Cool  |
                                | ------------- |:-------------:| -----:|
            | col 3 is      | right-aligned | $1600 |
                                            | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |
    
## 510074-p2-null
| Tables        | Are           | Cool  |
| -------------: |:-------------|:-----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## 510075-p3-null
 | Tables        | Are           | Cool  |
 | ------------- |:-------------:| -----:|
 | col 3 is      | right-aligned | $1600 |
 | | | |
 | col 2 is      | centered      |   $12 |
 | zebra stripes | are neat      |    $1 |

# Image Syntax
***
## 510083-p1-null
![Image](https://www.baidu.com)