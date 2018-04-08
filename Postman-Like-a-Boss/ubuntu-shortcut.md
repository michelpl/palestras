## Atalho no Ubuntu para o Postman

### Seguir os passos a seguir, sempre substituindo {{ username }} pelo seu nome de usuário no sistema
- Baixar o ícone do Postman da internet e salvar na pasta de instalação
- Criar o arquivo /home/{{ username }}/.local/share/applications/postman.desktop
- Inserir o conteúdo a seguir e pronto!

```
[Desktop Entry]
Version=1.0
Type=Application
Name=Postman
Icon=/home/{{ username }}/Postman/logo-icon.png
Exec="/home/{{ username }}/Postman/Postman" %f
Comment=Postman Native App
Categories=Application;
Terminal=false
StartupWMClass=postman
``
