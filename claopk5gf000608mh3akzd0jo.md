# What is Flexbox?

Flexbox delivers a more efficient way to assign space around elements. There is no need to know the screen size to use flexbox.

And one more thing to note is that flex's default direction is the **row** in web development whereas in android development its default direction is the **column**.

For a better perceptive let's take an example.

# 1. Container Without Flex.
![container.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1668907262605/uwQDLluNA.PNG align="left")

```css
.container{
    border: 3px solid black;
    width: 50%;
}
.container-items {
    font-size: 35px;
    border: 2px dotted black;
}
``` 

# 2. Container With Flex.

![row.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1668935705338/q_IM63PAc.PNG align="left")
```css
.container{
    border: 3px solid black;
    width: 50%;
    display: flex; /* Adding Flex in code.*/
}
.container-items {
    font-size: 35px;
    border: 2px dotted black;
}
``` 
As we can see by just adding **"display: flex"** it takes all the properties of flexbox and as I mentioned earlier about the flex-direction it takes the **row** as the default value.

In the next article, we will go through all flexbox properties.


