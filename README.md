[README-GOOGLE-SHEETS.md](https://github.com/user-attachments/files/27057216/README-GOOGLE-SHEETS.md)
# Formulario Gestor Escolar 2025 + Google Sheets

Arquivos:

- [index.html](C:\Users\SEMED\Documents\New project\index.html)
- [google-apps-script.gs](C:\Users\SEMED\Documents\New project\google-apps-script.gs)

## Como ligar ao Google Sheets

1. Abra o Google Sheets e crie uma planilha nova no seu Drive.
2. No menu da planilha, abra `Extensoes > Apps Script`.
3. Apague o codigo padrao e cole todo o conteudo de `google-apps-script.gs`.
4. Salve o projeto.
5. Clique em `Implantar > Nova implantacao`.
6. Escolha `Aplicativo da web`.
7. Em `Quem tem acesso`, selecione a opcao adequada para receber respostas do formulario.
8. Conclua a implantacao e copie a `URL do Web App`.
9. Abra [index.html](C:\Users\SEMED\Documents\New project\index.html) no navegador.
10. No painel lateral `Google Sheets`, cole a URL e clique em `Salvar URL`.
11. Preencha o formulario e clique em `Enviar para Google Sheets`.

## Resultado

- Cada envio cria uma nova linha na aba `Respostas`.
- O script cria o cabecalho automaticamente no primeiro envio.
- O formulario continua podendo salvar localmente no navegador tambem.

## Observacao

- Se o Google pedir autorizacao na primeira publicacao do Apps Script, aprove essa etapa na sua conta.
- O envio para o Google Sheets so funciona depois que a URL do Web App estiver publicada.
