# SBS1-TDD-Python

Estudando TDD com Python
<br />
<br />

## **Criando o Ambiente**
<br />
<br />

### Instalar o [ASDF](https://asdf-vm.com/guide/getting-started.html#_1-install-dependencies).

1- Depois de Instalado o ASDF. Adicionar um plugin local do Python na versão 3.10.2

```
asdf plugin add python
asdf install nodejs 3.10.0
asdf local python 3.10.2
```

2- Instalar o virtualenv
```
pip install virtualenv
```

3- Dentro da pasta do projeto criar um virtualenv
Exemplo:

```
python -m venv .venv
```

4- Para ativar o virtualenv
```
source .venv/bin/activate 
```

5- Para desativar o virtualenv
```
deactivate
```

6 - Instalar o Django e o Selenium

```
pip install "django<2.2" "selenium<4"
```