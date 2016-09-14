/*
* We should use the log specification
* for every modification
* such as
*/

[`modify type`] [`module`] [`modify version`]
[`what`] `a statement for what a modification you do`
[`why`]  `a statement for why you select this way to modify it`
[`how`]  `a statement for how to implement it`

enum:
modify type-->
bugfix  :  fix a bug
feature :  add/modify a function to the program
config  :  just configuration 

module  -->   //module rely on the concrete code, such as:
network  :  the network module has been changed
graphic  :  the graphic module has been changed
...etc

modify version  -->    //not the push revision, maybe->
alpha : the alpha version
beta,,
releas,,

or 
Question 1,,
Question 2,,
...

or
event 1,,
event 2,,

most of the modify version was put forward by the developer
if the modify version was null, choose 0 to commit is right.



and then, the what why how ,  are all the being fully described.

/*
*其实文本内容是什么都没关系
*中文也可以的！
*编辑器我一般用sublime或者ultraedit
*/
