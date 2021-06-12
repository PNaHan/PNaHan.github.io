---
layout: post
title: "Graphics Design"
author: "PNaHan"
---

![grap](../images/graphics.jpg)

Computer Graphics Design

Adobe PhotoShop, OpenGL 



* Simple OpenGL
``` <OpenGL> 
    void display() {
      glBegin(GL_POLYGON);
      glVertex2f(-0.5f, -0.5f);
      glVertex2f(0.5f, -0.5f);
      glVertex2f(0.5f, 0.5f);
      glVertex2f(-0.5f, 0.5f);
      glEnd();
      glFinish();
    }
    int main(int argc, char** argv) {
      glutInit(&argc, argv);
      glutCreateWindow("OpenGL");
      glutDisplayFunc(display); // 여기서 그릴 함수를 넣어준다.
      glutMainLoop();
      return 0;
    }
```
