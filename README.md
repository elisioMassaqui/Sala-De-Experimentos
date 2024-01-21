# Sala de Experimentos

Bem-vindo à Sala de Experimentos! Este é um projeto dedicado a testar diversas possibilidades para projetos principais. Utilizamos esta sala para experimentar, prototipar e validar ideias antes de incorporá-las em projetos mais extensos.

## Experimento: Controle de Porta com Arduino e Unity

Neste experimento, exploramos a integração entre a Unity (C#) e um Arduino (C++) para controlar uma porta. A configuração é realizada da seguinte forma:

1. **Abertura de Porta com C#:**
   Utilizamos C# na Unity para criar um timer. Quando o timer está contando e um botão toggle está ativado, a porta virtual se abre. Essa ação é acionada por uma lógica de abertura de porta na Unity.

2. **Lógica C++ no Arduino:**
   A lógica para receber os dados da Unity e controlar a LED está implementada em C++ no Arduino. Quando os dados indicam que a porta deve ser aberta, a LED pisca.

3. **Temporizador Automático:**
   O botão toggle desativa automaticamente após alguns segundos, proporcionando uma funcionalidade temporizada definida pelo usuário.

4. **Mudança de Cor com Dropdown:**
   Além disso, implementamos um dropdown na Unity para permitir que o usuário escolha a cor da imagem representativa. A cor da imagem muda de acordo com a seleção no dropdown.

![Experimentos Nível 001](https://github.com/elisioMassaqui/Sala-De-Experimentos/blob/main/Assets/Anota%C3%A7%C3%A3o%202024-01-21%20180305.png)

## Experimento: Outro Título

Aqui, você pode adicionar mais informações sobre outros experimentos de nível 001 ou de outros níveis, conforme necessário.

## Configuração do Experimento

1. **Clonar o Repositório:**
   ```bash
   git clone https://github.com/seu-usuario/Sala-De-Experimentos.git
   cd Sala-De-Experimentos

Abra o Projeto Unity:
Abra o projeto Unity e explore a pasta do experimento "Controle_de_Porta".

Configuração do Arduino:
Carregue o código C++ no Arduino para estabelecer a comunicação e controlar a LED.

Execute o Experimento:
Execute o experimento na Unity e observe o comportamento da porta, a LED e a mudança de cor da imagem.

Contribuição
Se você tem sugestões ou melhorias para este experimento, sinta-se à vontade para abrir uma issue ou enviar um pull request. Estamos abertos a colaborações!

Licença
Este projeto é licenciado sob a Licença MIT, o que significa que você é livre para utilizar, modificar e distribuir o conteúdo.
