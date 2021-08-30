# gdkstudy

Компиляция
```bash
gcc `pkg-config --cflags gtk+-3.0` -o app example-0.c `pkg-config --libs gtk+-3.0`
```
или
```bash
gcc example-0.c -o app `pkg-config --cflags --libs gtk+-3.0`
```
