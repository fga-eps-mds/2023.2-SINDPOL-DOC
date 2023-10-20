# Guia de estilo

## 1. Introdução
O Guia de Estilo de um projeto de software, na parte de design, define as normas estéticas e de usabilidade que devem ser seguidas para criar uma interface de usuário coerente e atraente. Isso inclui diretrizes para layout, cores, tipografia, ícones e elementos de interação, assegurando que a aparência e a experiência do usuário sejam consistentes em todo o software.

## 2. Identidade Visual
### 2.1 Logo Principal

<img src="../../assets/logo.png" alt="Logo" style="width: 50% !important;" />

### 2.2 Tipografia

As principais famílias tipográficas definidas para o projeto foram a Inter e Rubik, e suas variações de estilo.

### Fonte Inter

<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Inter:400,500,700">

| Tipo       |    Alfabeto     |
| :--------- |    :----------- |
|<span style="font-family: 'Inter', sans-serif;">Regular</span>| <span style="font-family: 'Inter', sans-serif;">abcdefghijklmnopqrstuvz<br>ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>1234567890 .,:;/()&?!@</span>|
|<span style="font-family: 'Inter', sans-serif; font-weight: 500;">Medio</span>| <span style="font-family: 'Inter', sans-serif; font-weight: 500;">abcdefghijklmnopqrstuvz<br>ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>1234567890 .,:;/()&?!@</span>|
|<span style="font-family: 'Inter', sans-serif; font-weight: bold;">Negrito</span>| <span style="font-family: 'I', sans-serif; font-weight: bold;">abcdefghijklmnopqrstuvz<br>ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>1234567890 .,:;/()&?!@</span>|

### Fonte Rubik

<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Rubik:400,500,700">

| Tipo       |    Alfabeto     |
| :--------  |    :----------- |
|<span style="font-family: 'Rubik', sans-serif;">Regular</span>| <span style="font-family: 'Rubik', sans-serif;">abcdefghijklmnopqrstuvz<br>ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>1234567890 .,:;/()&?!@</span>|
|<span style="font-family: 'Rubik', sans-serif; font-weight: 500;">Medio</span>| <span style="font-family: 'Rubik', sans-serif; font-weight: 500;">abcdefghijklmnopqrstuvz<br>ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>1234567890 .,:;/()&?!@</span>|
|<span style="font-family: 'Rubik', sans-serif; font-weight: bold;">Negrito</span>| <span style="font-family: 'Rubik', sans-serif; font-weight: bold;">abcdefghijklmnopqrstuvz<br>ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>1234567890 .,:;/()&?!@</span>|





### 2.3 Cores

**Cores Primárias**
<br><br>
<div style="display:flex; flex-direction: row; justify-content: space-around;">
    <div style="background: #FFA500; width: 200px; height: 200px; border-radius: 50%; font-size: 14px; display: flex; flex-direction: column; justify-content: center; align-items: center;">
        <p style="color: black;">HEX: #FFA500</p>
        <p style="color: black;">RGB: 255, 165, 0</p>
    </div>
    <div style="background: #FFFFFF; width: 200px; height: 200px; border-radius: 50%; font-size: 14px; display: flex; flex-direction: column; justify-content: center; align-items: center;">
        <p style="color: black;">HEX:  #FFFFFF</p>
        <p style="color: black;">RGB: 255, 255, 255</p>
    </div>
</div>

<br>
**Cores Secundárias**
<br><br>

<div style="display: flex; flex-direction: row; justify-content: space-around;">
    <div style="background: #131313; width: 200px; height: 200px; border-radius: 50%; font-size: 14px; display: flex; flex-direction: column; justify-content: center; align-items: center;">
        <p style="color: white;">HEX: #131313</p>
        <p style="color: white;">RGB: 19, 19, 19</p>
    </div>
    <div style="background: #000000; width: 200px; height: 200px; border-radius: 50%; font-size: 14px; display: flex; flex-direction: column; justify-content: center; align-items: center;">
        <p style="color: white;">HEX: #000000</p>
        <p style="color: white;">RGB: 0, 0, 0</p>
    </div>
        <div style="background: #B01212; width: 200px; height: 200px; border-radius: 50%; font-size: 14px; display: flex; flex-direction: column; justify-content: center; align-items: center;">
            <p style="color: white;">HEX: #B01212</p>
            <p style="color: white;">RGB: 176, 18, 18</p>
        </div>
</div>

<div style="display: flex; flex-direction: row; justify-content: space-around; margin-top:20px;">
    <div style="background: #FFCD71; width: 200px; height: 200px; border-radius: 50%; font-size: 14px; display: flex; flex-direction: column; justify-content: center; align-items: center;">
        <p style="color: black;">HEX: #FFCD71</p>
        <p style="color: black;">RGB: 255, 205, 113</p>
    </div>
    <div style="background: #FFF7E8; width: 200px; height: 200px; border-radius: 50%; font-size: 14px; display: flex; flex-direction: column; justify-content: center; align-items: center;">
        <p style="color: black;">HEX: #FFF7E8</p>
        <p style="color: black;">RGB: 255, 247, 232</p>
    </div>
    <div style="background: #F6F6F3; width: 200px; height: 200px; border-radius: 50%; font-size: 14px; display: flex; flex-direction: column; justify-content: center; align-items: center;">
        <p style="color: black;">HEX: #F6F6F3</p>
        <p style="color: black;">RGB: 246, 246, 243</p>
    </div>
</div>



### 2.4 Icones

Os icones utilizados na aplicação são obtidos a partir da biblioteca [Tabler-icons](https://tabler-icons.io/)

## 3. Histórico de Revisão

| Data       | Versão |      Modificação      |    Autor     |
| :--------- | :----- | :-------------------- | :----------- |
|20/10/2023| 0.1 | Criação do documento | Carlos Eduardo <br> Alexandre Lema <br> Bruno Bragança |

