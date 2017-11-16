# Julia [![Demo](https://img.shields.io/badge/julia-demo-green.svg)](http://kuoa.github.io)

A minimalistic jekyll theme

---------------------------
Home page

![about-page](https://raw.githubusercontent.com/kuoa/julia/master/assets/home.png)
---------------------------

Part one of a long post
![post-1](https://raw.githubusercontent.com/kuoa/julia/master/assets/post_1.png)
---------------------------

Part two of a long post
![post-2](https://raw.githubusercontent.com/kuoa/julia/master/assets/post_2.png)
---------------------------

Posts will be listed by category in the `Archive` page alongside with their tags
![archive-page](https://raw.githubusercontent.com/kuoa/julia/master/assets/archive.png)

---------------------------

How to use it
=========


### Install from github

1. [Fork this repository](https://github.com/kuoa/julia/fork)

2. Clone the repository to your computer and run it

    ``` sh
    $ git clone https://github.com/kuoa/julia.git
    $ bundler install
    $ jekyll serve
    ```

---------------------------

### Configurations
Edit the `_config.yml` file and make the theme yours.
 * Change the base color in */css/main.sccs*  ```$brand-color:      new-color;```
 * To enable comments modify the ```disqus_shortname```
 * To enable google-analytics set ```google-analytics``` to true and paste your tracking code in ```/_inludes/google_analytics.html```
 * To add links to the navbar edit the ```links``` section

---------------------------
### Author  [![Twitter](https://img.shields.io/badge/kuoa-<3-66BAB7.svg)](https://github.com/kuoa)

---------------------------
### License  [![License](https://img.shields.io/npm/l/express.svg)](https://github.com/kuoa/julia/blob/master/LICENSE)






Below is just about everything you'll need to style in the theme. Check the source code to see the many embedded elements within paragraphs.

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### Body text

Lorem ipsum dolor sit amet, test link adipiscing elit. **This is strong**. Nullam dignissim convallis est. Quisque aliquam.

This is a image.

![panda]({{ site.url }}/assets/logo.png)


*This is emphasized*. Donec faucibus. Nunc iaculis suscipit dui. 53 = 125. Water is H<sub>2</sub>O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. The New York Times <cite>(That’s a citation)</cite>. <u>Underline</u>. Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.

HTML and <abbr title="cascading stylesheets">CSS<abbr> are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus.

### Blockquotes

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists

* Item one
* Item two
* Item three

## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## Code Snippets

Syntax highlighting via Rouge

```css
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
```

Non Rouge code example

    <div id="awesome">
        <p>This is great isn't it?</p>
    </div>
