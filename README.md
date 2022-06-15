# Graphics.h In Visual Studio

Actually you can use `graphics.h` on the lastest version of `Visual Studio`

 1. Download `graphics.h` and `graphics.lib` files in https://github.com/ahuynh359/Graphics
2. Drag these two files and drop to your sub project. For example if my project named `Project1` I will add these two files to `Project1\Project1`

[![enter image description here][1]][1]

3. Change to `x86` 

<img width="526" alt="Untitled" src="https://user-images.githubusercontent.com/32415728/173909656-1b929b6e-9c6b-4bb2-a274-96700329d041.png">


4. Implement these code 
```
#include "graphics.h"
#pragma comment(lib,"graphics.lib")
int main()
{
    initwindow(500, 500);
    getch();
    closegraph();
    return 0;
}
```


  [1]: https://i.stack.imgur.com/uLYc6.png
  [2]: https://i.stack.imgur.com/UQ3rN.png
  [3]: https://i.stack.imgur.com/WecwB.png
  
  5. Project 
  - https://github.com/ahuynh359/QuanLyMayBay
