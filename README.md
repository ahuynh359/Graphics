# Graphics
Actually you can use `graphics.h` on the lastest version of `Visual Studio`

 1. Download `graphics.h` and `graphics.lib` files in https://github.com/ahuynh359/Graphics
2. Drag these two files and drop to your sub project. For example if my project named `Project1` I will add these two files to `Project1\Project1`
[![enter image description here][1]][1]
3. Change to `x86` in `Configuration Manager` next to the `Debug` box
[![enter image description here][2]][2]
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
  [2]: https://i.stack.imgur.com/D8aw8.png
