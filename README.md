angular-readmore
================

Angular Read More Directive

Simple and easy-to-implement angular read more directive.

#### Demo
[http://plnkr.co/edit/Tsqkv1nd6CC8e5Kr9pdU?p=preview](http://plnkr.co/edit/Tsqkv1nd6CC8e5Kr9pdU?p=preview)

#### Requirements
 
+ Latest jQuery
+ AngularJS 1.3+
 

#### Markup  

    <p read-more>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
    Maecenas sit amet ultrices urna. Donec sagittis euismod diam eget luctus. 
    Aenean imperdiet justo sed dui vehicula porttitor. 
    Nulla commodo elementum malesuada. 
    Mauris lacinia pharetra mi, id ornare lacus venenatis non.</p>

or


    <p read-more content="{{scope}}"></p>


#### Options

|  Attributes       | Default           |   |
| ------------- |:-------------:| -----:|
| moreText      | "Read More..." | (string) |
| lessText      | "Less ^" |   (string) |
| ellipsis | ""      |    (string) |
| words | null   |  null |
| char | null (default active)      |    null |
| limit | 150    |  (int)  |
| content | null     |   {{scope}}, (string) | 


#### Other Examples

+ (Default) Separated by number of characters

`<p read-more>Lorem ipsum dolor sit amet.</p>`

+ Separated by number of words

`<p read-more words></p>`


+ Change *Read More...* text

`<p read-more more-text="VIEW MORE..."></p>`


+ Change *Less ^* text

`<p read-more less-text=“VIEW LESS”></p>`


+ Change ellipsis

`<p read-more ellipsis=“…”></p>`


+ Change character/word limit

`<p read-more limit=“250”></p>`



