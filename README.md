# Behrend BJJ — Site Institucional

Site do centro de treinamento Behrend BJJ, desenvolvido para apresentar a academia, divulgar modalidades e horários e facilitar o contato de interessados.

🌐 **[Acesse o site]behrend-bjj.netlify.app**

## Sobre o projeto

O projeto reúne informações da academia em um único lugar, permitindo que visitantes conheçam os treinos, consultem horários, encontrem a localização e entrem em contato pelo WhatsApp.

## Recursos

- Apresentação da academia.
- Páginas de Jiu-Jítsu adulto e infantil.
- Páginas de Judô adulto e infantil.
- Página de Muay Thai.
- Consulta de horários.
- Localização com Google Maps.
- Links para WhatsApp e redes sociais.
- Menu de navegação para telas menores.

## Tecnologias

- **HTML5:** estrutura e conteúdo das páginas.
- **CSS3:** estilos, layout e efeitos visuais.
- **JavaScript:** interação do menu.
- **Font Awesome:** ícones.
- **Netlify:** hospedagem do site.

## Estrutura do projeto

```text
Behrend-Bjj/
├── img/                    # Imagens e arquivos de mídia
├── js/
│   └── script.js           # Interações do site
├── index.html              # Página inicial
├── sobre.html              # Informações da academia
├── horarios.html           # Horários dos treinos
├── endereço.html           # Localização
├── jiujitsuadulto.html      # Jiu-Jítsu adulto
├── jiujitsuinfantil.html    # Jiu-Jítsu infantil
├── judoadulto.html          # Judô adulto
├── judoinfantil.html        # Judô infantil
├── muaythay.html            # Muay Thai
├── style.css               # Estilos do site
└── README.md               # Documentação do projeto
```

## Como executar localmente

O site é estático e não exige instalação de pacotes, banco de dados ou etapa de compilação.

1. Baixe o repositório em **Code → Download ZIP** e extraia os arquivos, ou clone com Git:

   ```bash
   git clone https://github.com/gab8485/Behrend-Bjj.git
   ```

2. Abra a pasta do projeto no Visual Studio Code.
3. Instale a extensão **Live Server**, de Ritwick Dey.
4. Clique com o botão direito em `index.html`.
5. Selecione **Open with Live Server**.

Também é possível abrir o `index.html` diretamente no navegador. Recursos externos, como mapas e ícones, dependem de conexão com a internet.

## Publicação no Netlify

Para publicar manualmente:

1. Acesse sua conta no Netlify.
2. Crie um projeto e escolha a opção de envio de arquivos.
3. Envie a pasta que contém o `index.html`, junto dos demais arquivos.
4. Aguarde a conclusão da publicação.

Para atualizar um projeto existente, envie a pasta atualizada pela seção **Deploys**.

## Estado atual

O projeto é um site institucional estático. O contato com a academia é direcionado ao WhatsApp.

O formulário presente na página inicial ainda precisa ser integrado a um serviço de envio para receber mensagens. Não há sistema de cadastro, autenticação ou agendamento implementado.

## Melhorias planejadas

- Revisar a exibição em celulares, tablets e computadores.
- Melhorar a acessibilidade com descrições de imagens e navegação por teclado.
- Otimizar imagens para reduzir o tempo de carregamento.
- Revisar links, textos e estrutura das páginas.
- Integrar o formulário a um serviço de recebimento de mensagens.
- Avaliar uma funcionalidade de agendamento de aula experimental.

## Verificação manual

Após alterações, conferir:

- Carregamento das imagens.
- Navegação entre as páginas.
- Abertura dos links de WhatsApp e redes sociais.
- Exibição dos horários e do mapa.
- Funcionamento do menu em telas menores.
- Ausência de erros no console do navegador.

## Créditos

Desenvolvido por Gabriel Gonçalves, Gabriel Pereira e Edric, conforme os créditos presentes no site.

Perfil responsável pelo repositório: [gab8485](https://github.com/gab8485).
