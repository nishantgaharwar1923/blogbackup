# What is Flexbox?

Flexbox delivers a more efficient way to assign space around elements. There is no need to know the screen size to use flexbox.

And one more thing to note is that flex's default direction is the **column** in web development whereas in android development its default direction is the **row**.

For a better perceptive let's take an example.

# 1. Container Without Flex.
![container.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1668907262605/uwQDLluNA.PNG align="left")

```
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

![container with flex.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1668907488047/d7NqlMVuv.PNG align="left")
```
.container{
    border: 3px solid black;
    width: 50%;
}
.container-items {
    font-size: 35px;
    border: 2px dotted black;
    display: flex; /* Adding Flex in code.*/
}
``` 
As we can see by just adding **"display: flex"** it takes all the properties of flexbox and as I mentioned earlier about the flex-direction it takes the **column** as the default value.

In the next article, we will go through all flexbox properties.


