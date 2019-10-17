
# Markdown Tutorial



## What is markdown?

Markdown is a writing tool which lets you write plain text while tagging the formatting.



## Why use Markdown?



- Easy to write

- Consistent formatting

- Easy to read marked up text

- Widely supported (Github & Gitlab)

- Free

- Cross-platform

<img  src="github.png"  width="80">    <img  src="gitlab.png"  width="100">    <img  src="jupyter.png"  width="60">

___

## Preferred tools to use Markdown

Personally I prefer VS Code to write markdown, as it provide helpful extensions to generate HTML and PDF from markdown files very easily. Alot of other advanced text editors like Sublime text, Atom, and eclipse(This is a IDE) do provide their own markdown support but I found usage with VS Code to be more smooth.

You can download Visual studio code on windows using the following link:

[https://az764295.vo.msecnd.net/stable/6ab598523be7a800d7f3eb4d92d7ab9a66069390/VSCodeUserSetup-x64-1.39.2.exe](https://az764295.vo.msecnd.net/stable/6ab598523be7a800d7f3eb4d92d7ab9a66069390/VSCodeUserSetup-x64-1.39.2.exe)

and then run the installer to install it on local machine.

Two helpful extensions for writing markdown are as follows:

1. __Markdown PDF__ : https://marketplace.visualstudio.com/_apis/public/gallery/publishers/yzane/vsextensions/markdown-pdf/1.3.1/vspackage

2. __Markdown All in One__ : https://marketplace.visualstudio.com/_apis/public/gallery/publishers/yzhang/vsextensions/markdown-all-in-one/2.5.1/vspackage


Once you install VS Code and download the two extensions, follow the steps to install these extensions:

1. Open Visual Studio Code.

2. Press `Ctrl+Shift+p`. A header pop-up will appear. In there type : `>Extensions:Install from VSIX` and press `Enter`.

3. This will open a file manager window asking for where the extensions are downloaded. Goto the particular location and select the extension one by one. It will automatically install them.

4. __`Markdown PDF`__ depeends on Google Chrome/Chromium to convert markdown. To make it point to already installed Google chrome, again press `Ctrl+Shift+p` to open header pop-up. In there type : `>Open Settings(JSON)` and press `Enter`.

5. On the very top of the file add the following line ` "markdown-pdf.executablePath": "C:\\Program Files (x86)\\Google\\Chrome\\Application\\chrome.exe",` like this:
![alt text](json.png)

6. Restart VS Code.

### Contents


-  ## Headings

   -  # Heading 1 -> ` # Heading 1`

   -  ## Heading 2 -> ` ## Heading2 `

   -  ### Heading 3 -> `### Heading 3`

   -  #### Heading 4 -> `#### Heading 4`

   -  ##### Heading 5 -> `##### Heading 5`

   -  ###### Heading 6 -> `###### Heading 6`



- ## Phrase emphasis

    -  ### Bold text

    `That's how you write **bold** or like this __bold__`

    That's how you write **bold** or like this __bold__



    -  ### Italic text

    `That's how you write *italic* or like this _italic_`

    That's how you write *italic* or like this _italic_



    -  ### Strikethrough

    `That's how you ~~strikethrough text~~`

    That's how you ~~strikethrough text~~.



    -  ### Combined Emphasis

    `This text uses _combination of **emphasis** for ~~dem~~ demo_`

    This text uses _combination of **emphasis** for ~~dem~~ demo_



-  ## Lists

   -  ### Unordered list

   ```

   - first item

   - second item

   - third item

   - fourth item

   ```



   - first item

   - second item

   - third item

   - fourth item

   We can also use `*` or `+`

   ```

   + first item also

   * second item also

   ```



   + first item also

   * second item also



   -  #### Nested Lists

   - item 1

   - item2

   - item 3



   -  ### Ordered List



   ```

   1. first item

   2. second item

   3. Third item

   - Nested item

   1. Another item

   ```



   1. first item

   2. second item

   3. Third item

   - Nested item

   - Very Nested item

   1. Another item

-  ## Links



    Links can be put like :

    -  ### Inline style web link

    ```

    [I am inline style link](http://www.google.com)

    ```

    [I am inline style link](http://www.google.com)

    -  ### Inline style web link with title

    ```

    [I am inline style link](http://www.google.com "Your awesome title here")

    ```

    [I am inline style link](http://www.google.com  "Your awesome title here")

    -  ### Reference Links

    ```

    [google] http://www.google.com

    [Google webpage][google]



    [Huawei Webpage][huawei]

    [huawei]: http://www.huawei.com

    ```

    [google]: http://www.google.com



    [Google webpage][google]



    [Huawei Webpage][huawei]



    [huawei]: http://www.huawei.com



    -  ### File Links



    ```
    [Gitlab logo](./gitlab.png)
    ```

    [Gitlab logo](./gitlab.png)

    - ### Within document links

    ```
    - [Phrase Emphasis](#phrase-emphasis)
    - [Lists](#lists)
    - [Links](#links)
    - [Images](#images)
    - [Code and Syntax Highlighting](#code-and-syntax-highlighting)
    - [Tables](#tables)
    - [Block Quotes](#block-quotes)
    - [Horizontal rule](#horizontal-rule)
    ```
    - [Phrase Emphasis](#phrase-emphasis)
    - [Lists](#lists)
    - [Links](#links)
    - [Images](#images)
    - [Code and Syntax Highlighting](#code-and-syntax-highlighting)
    - [Tables](#tables)
    - [Block Quotes](#block-quotes)
    - [Horizontal rule](#horizontal-rule)


- ## Images



  -  ### Inline style

      ```
      ![alt text](https://media.licdn.com/dms/image/C510BAQHDjJMzWUhMfg/company-logo_200_200/0?e=2159024400&v=beta&t=19_Z0-NTcopvhaoVQcyP-75Mhkp9Fh5jHEixMRSTZBc "Huawei Logo")
      ```

      ![alt text](https://media.licdn.com/dms/image/C510BAQHDjJMzWUhMfg/company-logo_200_200/0?e=2159024400&v=beta&t=19_Z0-NTcopvhaoVQcyP-75Mhkp9Fh5jHEixMRSTZBc  "Huawei Logo")


  - ### Reference-style:
      ```
      ![alt text][logo]

      [logo]: https://media.licdn.com/dms/image/C510BAQHDjJMzWUhMfg/company-logo_200_200/0?e=2159024400&v=beta&t=19_Z0-NTcopvhaoVQcyP-75Mhkp9Fh5jHEixMRSTZBc
      ```
      ![alt text][logo]

      [logo]: https://media.licdn.com/dms/image/C510BAQHDjJMzWUhMfg/company-logo_200_200/0?e=2159024400&v=beta&t=19_Z0-NTcopvhaoVQcyP-75Mhkp9Fh5jHEixMRSTZBc

  - ### HTML Style

      ```html
      <img src="https://media.licdn.com/dms/image/C510BAQHDjJMzWUhMfg/company-logo_200_200/0?e=2159024400&v=beta&t=19_Z0-NTcopvhaoVQcyP-75Mhkp9Fh5jHEixMRSTZBc">
      ```

      <img src="https://media.licdn.com/dms/image/C510BAQHDjJMzWUhMfg/company-logo_200_200/0?e=2159024400&v=beta&t=19_Z0-NTcopvhaoVQcyP-75Mhkp9Fh5jHEixMRSTZBc
      ">



- ## Code and Syntax Highlighting

    - Python
        ```
            ```python
            def markdown():
                print("Markdown is good")
            ```
        ```
        *Output* :
        ```python
            def markdown():
                print("Markdown is good")
        ```
    - C++
        ```
            ```CPP
            #include <iostream>

            int main(){
                std::cout<<"Markdown is good"<<std::endl;
                return 0;
            }
            ```   
        ```

        *Output* :
        ```CPP
        #include <iostream>

        int main(){
            std::cout<<"Markdown is good"<<std::endl;
            return 0;
        }
        ```

    - Shell

        ```
          ```bash
            echo "Markdown is good "
            mkdir markdown
            cd ./markdown
           ```   
        ```
      *Output* :
      ```bash
        echo "Markdown is good "
        mkdir markdown
        cd ./markdown
      ```

- ## Tables

    __Tables are only supported by Github flavoured markdown.__

     Colons can be used to align columns.
    ```

    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |

    |   Col1                     | Col2  |
    |:--------------------------:|-------|
    | cell 1 is longer than usual| cell 2|

    ```

    Colons can be used to align columns.

    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |


    |   Col1                     | Col2  |
    |:--------------------------:|-------|
    | cell 1 is longer than usual| cell 2|

- ## Block Quotes
  ```
  > We are almost about to finish this.
  ```
  > We are almost about to finish this.

- ## Horizontal Rule

  Both `-` and `_` can be used to make ruler lines.
  ```
  ---
  This is between border.
  ___
  ```

  ---
  This is between border.
  ___
