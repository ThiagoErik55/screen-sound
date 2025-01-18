# 🎵 Screen Sound

**Screen Sound** é um aplicativo de console em C# para gerenciar bandas musicais. Ele permite registrar bandas, avaliar suas performances com notas, e exibir a média de notas atribuídas a cada banda.

---

## 🚀 Funcionalidades

1. **Registrar Bandas**  
   Permite ao usuário adicionar novas bandas ao sistema.

2. **Mostrar Todas as Bandas**  
   Exibe todas as bandas registradas no sistema.

3. **Avaliar uma Banda**  
   Permite ao usuário atribuir uma nota (inteira) a uma banda já registrada.

4. **Exibir Média de Notas de uma Banda**  
   Calcula e exibe a média de notas atribuídas a uma banda.

5. **Sair do Sistema**  
   Encerra a aplicação de forma elegante.

---

## 🛠️ Estrutura do Código

### Principais Métodos
- `ExibirOpcoesDoMenu()`: Exibe o menu principal com as opções disponíveis.
- `RegistrarBanda()`: Registra uma nova banda no sistema.
- `MostrarBandasRegistradas()`: Lista todas as bandas registradas.
- `AvaliarUmaBanda()`: Permite avaliar uma banda com uma nota.
- `ExibirMediaBanda()`: Calcula e exibe a média das notas de uma banda.
- `ExibirTituloDaOpcao(string titulo)`: Exibe um título formatado com asteriscos.

---

## 🎮 Como Usar

1. Execute o programa no seu ambiente de desenvolvimento em C#.
2. Navegue pelo menu principal digitando o número correspondente à opção desejada:
   - `1`: Registrar uma banda.
   - `2`: Mostrar todas as bandas.
   - `3`: Avaliar uma banda.
   - `4`: Exibir a média de uma banda.
   - `-1`: Sair do programa.
3. Siga as instruções exibidas na tela para interagir com o sistema.

---

## 📋 Exemplo de Fluxo

1. Ao iniciar, o programa exibe o seguinte menu:

   ```
   ░██████╗░█████╗░██████╗░███████╗███████╗███╗░░██╗  ░██████╗░█████╗░██╗░░░██╗███╗░░██╗██████╗░
   ...
   Boas vindas ao Screen Sound

   Digite 1 para registrar uma banda
   Digite 2 para mostrar todas as bandas
   Digite 3 para avaliar uma banda
   Digite 4 para exibir a média de uma banda
   Digite -1 para sair
   ```

2. O usuário escolhe uma opção, como **Registrar Banda**, digita o nome da banda, e recebe uma mensagem de sucesso.

3. Após registrar algumas bandas, o usuário pode avaliar suas performances ou calcular a média de notas.

---

## ⚙️ Requisitos

- [.NET SDK](https://dotnet.microsoft.com/) instalado.
- Um editor de código, como [Visual Studio](https://visualstudio.microsoft.com/) ou [Visual Studio Code](https://code.visualstudio.com/).

---

## 📂 Estrutura do Projeto

```plaintext
ScreenSound/
├── Program.cs    # Código principal da aplicação
└── README.md     # Documentação do projeto
```

---

## 💡 Melhorias Futuras

1. Salvar os dados das bandas em um arquivo ou banco de dados.
2. Adicionar validações para notas e nomes de bandas.
3. Melhorar a interface para uso com navegadores ou aplicativos gráficos.

---

## 📜 Licença

Este projeto é de uso livre e está sob a licença [MIT](LICENSE).

---

Feito com ❤️ para gerenciar suas bandas favoritas! 🎸
```
