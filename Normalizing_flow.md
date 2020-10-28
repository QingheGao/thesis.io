## Normalizing flow

Before we actually get into the normalizing flow, we need to discuss some concept of Jacobian.


### Jacobian matrix

Consider a simple transition:
f([x,y]) = [x+sin(y), y+sin(x)]


![Image](images/v2-d6e7e48f04af2bd44ea56acf4ad5bd1b_b.gif)

We can see that this transition is quite complex and difficult to discuss. 

But this transition has an important property: Local linearly.

![Image](images/v2-0b540bc082b2dc44c0ba92139d24e30d_b.gif)

It is clear to see that local transition is linearly transform. Thus, we can use this property.

Linearly transform of x and y means the coordinates after linear transformation are actually parallel to each other.

First, consider a small distance dx as green arrow shows.
![Image](images/截屏2020-10-28 13.30.06.png)

https://zhuanlan.zhihu.com/p/100287713
