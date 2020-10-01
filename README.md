<p align="center">
<b>Tron Connect - Batida Remota</b>
</p>

#### :electron: Requisitos

**Node JS :** **https://nodejs.org/**

**Nativifier :** **https://github.com/jiahaog/nativefier**
<br>

#### :hammer: Ferramentas
**Inno Setup :** **https://jrsoftware.org/isinfo.php**
<br>
 
#### :computer: Comandos

**Windows 32 Bits**
```console
nativefier --name "Tron Connect" http://connect.tron.com.br/#/coleta-coletiva -a ia32 --zoom 0.8 -i icon.ico
```

**Windows 64 Bits**
```console
nativefier --name "Tron Connect" http://connect.tron.com.br/#/coleta-coletiva -a x64 --zoom 0.8 -i icon.ico
```

***

**--name** nome do aplicativo

**-a** versão do pacote (ia32 - 32 Bits ou x64 - 64 Bits)

**--zoom** % de zoom da visualização

**-i** ícone