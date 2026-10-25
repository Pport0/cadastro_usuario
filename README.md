# Cadastro de Usuário (Flutter)

Atividade prática da disciplina de Desenvolvimento Mobile (Flutter e Dart): Formulários e Validações.

Tela de cadastro com os campos nome completo, e-mail, CPF, telefone e senha, usando `TextFormField` dentro de um `Form`.

## Regras implementadas
- Todos os campos são obrigatórios.
- E-mail deve conter `@`.
- Senha com no mínimo 6 caracteres.
- CPF e telefone aceitam somente números (`FilteringTextInputFormatter.digitsOnly`).
- Erros exibidos abaixo de cada campo inválido.
- SnackBar de sucesso quando o cadastro é válido.

## Como executar
    flutter pub get
    flutter run
