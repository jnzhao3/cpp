# cpp
cpp snippets

## OpenGL
* Running on Mac Silicon:
```
g++ main.cpp -o opengl_program -I/opt/homebrew/include -L/opt/homebrew/lib -lglfw -lGLEW -framework OpenGL
```

## Raw String Literals
Introduced in C++ 11. No need to escape for special characters. Here's a comparison:
```
const char* str = "C:\\Users\\User\\Documents\\file.txt";
```
```
const char* str = R"(C:\Users\User\Documents\file.txt)";
```