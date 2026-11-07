
# 💻 Portfólio Profissional - Anna Queiroz

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5.3.3-7952B3?logo=bootstrap&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?logo=github&logoColor=white)

## 📖 Sobre o projeto

Este projeto foi desenvolvido como atividade da **Agenda 15 da disciplina de Desenvolvimento de Sistemas I**, do curso Técnico em Desenvolvimento de Sistemas da ETEC.

O objetivo da atividade foi criar e personalizar um portfólio profissional utilizando HTML, CSS e Bootstrap, aplicando os conhecimentos estudados durante as aulas.

O site apresenta informações sobre meu perfil profissional, formação acadêmica, tecnologias estudadas, projetos desenvolvidos e formas de contato.

## 👩‍💻 Aluna

**Anna Beatriz Queiroz Di Souza**

Disciplina: Desenvolvimento de Sistemas I

## 🛠️ Tecnologias utilizadas

- **HTML5:** estrutura e organização dos conteúdos do site.
- **CSS3:** personalização de imagens, tamanhos e elementos visuais.
- **Bootstrap 5.3.3:** criação do layout responsivo, menu de navegação, carousel, cards e botões.
- **Devicon:** biblioteca utilizada para exibir os ícones das tecnologias.
- **Visual Studio Code:** edição e desenvolvimento do código.
- **GitHub Pages:** publicação do portfólio na internet.

## ⚙️ Funcionamento do projeto

O portfólio está organizado em diferentes seções:

### Menu de navegação

O menu fica localizado na parte superior da página e permite acessar diretamente as seções Perfil, Formação, Projetos e Contato.

Foi desenvolvido utilizando a Navbar do Bootstrap, com links internos que direcionam o usuário para cada seção.

### Carousel de imagens

Na página inicial, foi utilizado um carousel com três imagens e botões laterais para avançar ou retornar aos slides.

Também foram realizados ajustes para padronizar a apresentação das imagens.

### Perfil profissional

A seção apresenta minha fotografia, nome, área de formação, interesses profissionais e tecnologias estudadas.

Também contém cards com informações sobre localização, formação, objetivos e área de interesse.

### Formação acadêmica

A seção apresenta minha trajetória acadêmica.

### Projetos

A seção apresenta três cards com imagens, títulos, descrições e botões para visualização dos projetos.

Os cards foram organizados em colunas utilizando o sistema de grid do Bootstrap.

### Contato

A seção apresenta botões de contato por e-mail, GitHub e LinkedIn, além da localização.

Os elementos foram organizados dentro de um card centralizado.

## 🔧 Personalizações e melhorias realizadas

O projeto inicial apresentado na Agenda 15 foi utilizado como base, mas algumas modificações foram realizadas para personalizar o portfólio. 

### Personalização das informações

- Substituição do nome fictício João Silva pelo meu nome, Anna Queiroz.
- Alteração da localização para Campinas/SP.
- Inclusão de uma fotografia pessoal na seção de perfil.
- Substituição das imagens utilizadas no carousel e nos cards de projetos.
- Atualização do resumo profissional, destacando minha formação em Ciências Biológicas, meu interesse em análise de dados e a busca por novas habilidades tecnológicas.
- Personalização das informações de formação e objetivos profissionais.
- Atualização dos links de contato para meus perfis pessoais.

### Melhorias no código e no layout

Durante o desenvolvimento, foram realizados ajustes para melhorar a organização e o funcionamento do site.

**1. Correção dos botões do carousel**

Inicialmente, os botões de navegação apresentaram problemas para mudar entre as três imagens.

Foram corrigidos os atributos `data-bs-slide-to`, permitindo a navegação correta pelos slides.

**2. Organização da seção Perfil**

Foram corrigidos fechamentos de tags HTML, principalmente `div` e `section`, para manter a fotografia, os textos e os cards dentro da mesma seção.

**3. Organização das tecnologias**

Os cards de tecnologias foram reorganizados utilizando `row g-4` e `col-md-6`, permitindo que HTML, CSS e Bootstrap aparecessem ao lado de Python, GitHub e VS Code.

**4. Organização dos projetos**

Os três projetos foram colocados dentro da mesma `row g-4`, utilizando `col-md-6 col-xl-4` para organizar os cards em colunas.

**5. Padronização das imagens dos projetos**

Foi utilizada a classe CSS `project-img` para definir uma altura padrão de 220 pixels para as imagens.

A propriedade `object-fit: cover` foi utilizada para ajustar as imagens sem deformá-las.

**6. Ajuste das imagens do carousel**

Foi utilizado CSS para controlar a altura dos slides e melhorar a adaptação das imagens aos diferentes tamanhos de tela.

**7. Organização da seção Contato**

Foram corrigidos os fechamentos das tags HTML para que o título, a descrição, os botões e a localização aparecessem dentro de um único card centralizado.

Essas correções foram adicionadas pois, ao copiar e colar o código da Agenda no VS Code, alguns detalhes, como hífens, se perdiam. Logo, foram feitos ajustes durante a construção do projeto, com base nas explicações da Agenda 15 e com auxílio do ChatGPT para identificar erros e compreender melhor a organização do código.

## 🎓 Recurso novo adicionado: Formação Acadêmica

Como recurso adicional solicitado na atividade, foi criada uma nova seção chamada **Formação Acadêmica**, que não fazia parte do modelo original desenvolvido durante a aula.

Essa seção apresenta meus três cursos, suas respectivas instituições e os períodos de formação.

O objetivo foi tornar o portfólio mais completo e destacar minha trajetória acadêmica, incluindo minha formação na área de Ciências Biológicas e meus estudos em tecnologia e sustentabilidade.

### Como o recurso foi implementado

A nova seção foi desenvolvida utilizando HTML e classes do Bootstrap já estudadas na Agenda 15.

Primeiramente, foi criada uma nova tag `section` com o identificador `id="formacao"`.

Dentro dela, foi utilizado um `container` para organizar o conteúdo e uma `row g-4` para distribuir os três cards.

Cada formação foi inserida em uma coluna com a classe `col-md-6 col-xl-4`, permitindo que os cards fiquem lado a lado em telas grandes e se reorganizem em telas menores.

Também foram utilizadas as classes `card`, `card-body`, `shadow-sm`, `rounded-4` e `badge bg-primary` para apresentar as informações de maneira organizada.

Por fim, foi acrescentado um novo link no menu de navegação:

```html
<a class="nav-link" href="#formacao">Formação</a>
```

Esse link permite acessar diretamente a nova seção.
