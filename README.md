# Quiz 8: Imaging Technique Inspiration and Coding Technique Exploration

## Part 1：Imaging Technique Inspiration

My inspiration comes from p5.js Ping Pong. It uses simple geometric shapes, like two white rectangles as paddles and a white square as the ball. These elements are placed on a dark background, making the motion very clear. It looks relatively simple to make. It doesn't rely on complex images, but its high interactivity keeps users engaged. Since I'm not skilled in art, this simple interactive game gives me a good direction. It also directly corresponds to one dimension of the assignment, "user input."

### Website

[p5.js Ping Pong Example](https://p5js.org/examples/games-ping-pong/)

### Images

![Ping Pong screenshot 1](images/微信图片_20260508072048_201_52.png)

![Ping Pong screenshot 2](images\微信图片_20260508072048_202_52.png)

---

## Part2：Coding Technique Exploration

在 Ping Pong 示例中，玩家通过键盘控制挡板上下移动。程序也会检测球是否碰到挡板、上下墙壁，或者是否越过画布边缘。这个技术在最终项目中，让用户可以直接控制屏幕上的视觉对象。它可以把静态的视觉作品变成一个互动体验，让用户的移动改变画面中发生的事情。最重要的是，它没有使用了复杂的数学公式来计算角度！

```js
speedX = -speedX;
vy_new = (ballY - paddleCenterY) / number;
```

就做出了这个游戏！当然，在最终作业中，也能通过让用户输入，让球留下运动轨迹，来作画。

### Coding Technique Image

![Ping Pong screenshot 3](images\微信图片_20260508072048_203_52.png)

![Ping Pong screenshot 4](images\微信图片_20260508072048_204_52.png)

### Example Implementation

[p5.js Ping Pong Example](https://p5js.org/examples/games-ping-pong/)