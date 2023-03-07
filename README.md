# tp-docs-and-diagrams
Contains diagrams for technical documentations and covers:
- Creating diagrams using Mermaid 
- Diagrams of standard software development and data engineering concepts


# Using Mermaid diagrams
## Simple flow chart
Here is a simple flow chart:

![image](https://user-images.githubusercontent.com/78715852/223324797-904b348f-0223-4688-af0a-cd715e999688.png)


```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

# Markdown Cheatsheet

## Lines/ dividers
Creating lines means you can use three or more of the following symbols:
```
Hyphens
---


Asterisks

***

Underscores
___

```

## Code blocks - highlighting syntax

  ![image](https://user-images.githubusercontent.com/78715852/223323143-eae3c764-5a5d-463f-92a2-ef7d80ebdc29.png)

  Inline `code` has `back-ticks around` it.


## Code blocks - entire block for copying and pasting
Triple back ticks ` ``` ` create code blocks

![image](https://user-images.githubusercontent.com/78715852/223323281-25d83e63-fac4-48bb-98c4-299dac31e8b2.png)

```
python
s = "Python syntax highlighting"
print s
```

## Embedding URLS
Embedding URLS
```
[Go to the Support Web Site](https://support.west-wind.com)
```

Embedding local links using relative paths
```
[Download Page](./product/download.html)
```

## **Resources**
---
- [Markdown cheatsheet - introduction](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Markdown cheatsheet - detailed](https://markdownmonster.west-wind.com/docs/_4ne1eu2cq.htm)
- [GitHub's docs on Mermaid](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams)
- [Mermaid Live Editor](https://mermaid.live/edit#pako:eNpVkE1rwzAMhv-K0WmDtlmSLW1zGKwfsMNg0PXW5ODaSmJI7ODI60qS_z5nZbDpZD3PayG7B2EkQgpFbS6i4pbY2yHTzNfL6ZVbmbP5_Hk44hcNbHN3ME7L-5vfTIZt-x0K1Smjxxve_lx41ziw3emAnauJhflfd7yYge1_XZTDDBq0DVfS79FPyQyowgYzSP1RYsF9MINMjz7KHZmPqxaQknU4A9dKTrhTvLS8-Q_3UpGxkBa87jysDZfo2x7o2k5vLlVHfqIwulDlxJ2tPa6I2i4NgkkvSkWVOy-EaYJOyemDqs91EiRRsuJRjMky5k9xLMU5XK-K6DEs5PIhjDiM4_gNmllwJg)
