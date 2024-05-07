<div id="top"></div>

<br />

<div align="center">
  <a href="https://github.com/sayuri-gui/ChallengeAlgorithms.git">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/47/Logo_del_ITESM.svg" alt="Logo" width="80" height="80">
  </a>
<h3 align="center">Actividad 3.1. Analizador léxico</h3>
  <p align="center">
        Tania Sayuri Guizado Hernandez
</div>

### Construido con
<div>
<img width="45px" height="50px" src="https://seeklogo.com/images/C/c-programming-language-logo-9B32D017B1-seeklogo.com.png"/>
</div>

### Instrucciones

Genere un código LEX para analizar el ejemplo del laboratorio 03.

Una línea de código válida en ac podría ser:
```
// basic code

//float b
f b

// integer a
i a

// a = 5
a = 5

// b = a + 3.2
b = a + 3.2

//print 8.5
p b
```

La salida deberia ser:

```
COMMENT
COMMENT
floatdcl id
COMMENT
intdcl id
COMMENT
id assign inum
COMMENT
id assign id plus fnum
COMMENT
print id
```
