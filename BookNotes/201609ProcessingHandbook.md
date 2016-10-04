# Processing - A Programming Handbook for Visual Designers and Artists

Processing relates software concepts to principles of visual form, motion, and interatcion.

最开始时，Processing 主要用来生成和处理图像，使绘制线、椭圆、曲线等图形元素变得容易。Processing 简单易上手。

Basic beliefs:

- Software is a unique medium with unique qualities
- Every programming language is a distinct material
- Sketching is necessary for the development of ideas
- Programming is not just for engineers

Processing strives to make it possible and advantageous for people within the visual arts to learn how to build their own tools.

The Processing approach to programming blends with established methods. The core language and additional libraries make use of Java, which also has elements identical the C programming language.

### 程序结构

setup() 在程序开始时运行一次

draw() 循环运行，这是实现动画和互动的关键

A function is a block of code within a program that performs a specific task.

Object-oriented programming is a way of structuring code into objects, units of code that contain both variablies(data) and functions.

> Coding is Writing

expressions (like a phrase 表达式，有 value), statements（多个表达式组成）

### Draw

坐标原点：左上角

![](http://7xjpra.com1.z0.glb.clouddn.com/ProcessingCoordination.jpg)

![](http://7xjpra.com1.z0.glb.clouddn.com/ProcessingGeometryPrimitives.jpg)

![](http://7xjpra.com1.z0.glb.clouddn.com/ProcessingDrawingModes.jpg)

### Color

屏幕颜色是加成的 Additive color。屏幕原本黑色，加成光亮后有了颜色。

Blend mode: blend, add, subtract, darkest, lightest, difference, exclusion, multiply, screen, replace.

![](http://7xjpra.com1.z0.glb.clouddn.com/ProcessingBlending.jpg)

### Interactivity

Mouse and keyboard

### Repeat

### Synthesis

### Text

### Typography

### Image
display ``PImage img;``

filter: THRESHOLD, GRAY,INVERT, POSTERIZE, BLUR, OPAQUE, ERODE, DILATE

mask() method of  PImage sets the transparency values of an image based on the contents of another image.

### Transform
pushMatrix() 记录现在 transformations 的状态； popMatrix() 恢复

The pushMatrix() function is used to add a new coordinate matrix to the stack, and popMatrix() is used to remove one from the stack.

### Vertices

### 3D Drawing

![](http://7xjpra.com1.z0.glb.clouddn.com/3D-coordination.jpg)

camera

Processing offers an explicit mapping of the camera analogy through ist function, which is derived from OpenGL.

Lights, Materials

### Shapes
display SVG

SVG format specifies 2D graphics. SVG is an open standard that stores data in XML format.

### Debugging

- scrutinize the newest code
- check related code
- display output
- isolate the problem
- learn from previous bugs
- take a break

### Calculate
![](http://7xjpra.com1.z0.glb.clouddn.com/ExponentialEquations.jpg)
Exponential Equations

Easing, also called interpolation, is a technique for moving between two numbers with nonlinear increments.

![](http://7xjpra.com1.z0.glb.clouddn.com/Degrees&Radians.jpg)

### Random

### Motion
mechanical motion

organic motion

kinctic tpyography

### Time
