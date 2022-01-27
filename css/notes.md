# Notes for Web Development



[ https://youtu.be/6pidsgeLLzE ]



```css
@import url('https://fonts.googleapis.com/css2?family=Bellefair&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');


/* ***************** */

.template-bg{
    background-image: url("../img/5053309.jpg");
    background-size: 100vw 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
}

.flexgrid {
    display: flex;
    flex: 1 1 100%
}

.flexgrid * {
    flex-wrap: wrap;
}


/* *************** */


ul{
list-style-type:none;
margin:0;
padding:0;
overflow:hidden;
}
 
li{
float:left
}
 
 
a:link, a:visited{
display:block;
font-weight:bold;
color:#FFFFFF;
background-color:#98bf21;
width:120px;
text-align:center;
padding:4px;
text-transform:uppercase;
text-decoration:none;
}
 
a:hover, a:active{
background-color:#7A991A;
}
```



- style the list inside nav differently for different screen sizes
    - make it a list on a pop-up glassy panel by default (for mobile devices)


