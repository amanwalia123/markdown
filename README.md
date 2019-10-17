
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
      <img src="https://media.licdn.com/dms/image/C510BAQHDjJMzWUhMfg/company-logo_200_200/0?e=2159024400&v=beta&t=19_Z0-NTcopvhaoVQcyP-75Mhkp9Fh5jHEixMRSTZBc
      ">
      ```

      <img src="https://media.licdn.com/dms/image/C510BAQHDjJMzWUhMfg/company-logo_200_200/0?e=2159024400&v=beta&t=19_Z0-NTcopvhaoVQcyP-75Mhkp9Fh5jHEixMRSTZBc">



- ## Code and Syntax Highlighting

    - Python
        ```
            ```python
            def markdown():
                print("Markdown is good")
            ```
        ```
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
