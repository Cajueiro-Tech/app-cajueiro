# app-cajueiro
# Projeto Cajueiro Tech

## Visão Geral

Cajueiro Tech é um projeto de site fictício desenvolvido como parte de uma atividade acadêmica. A plataforma simula um portal digital de aprendizagem voltado para o desenvolvimento de cursos e treinamentos para empreendedores e criadores de startups. O objetivo da Cajueiro Tech é oferecer conteúdos educativos, mentorias e ferramentas de apoio para auxiliar pessoas que desejam criar novos negócios, inovar em seus projetos e acelerar suas ideias.

Este projeto foi concebido para demonstrar habilidades em desenvolvimento front-end, incluindo a criação de uma interface de usuário moderna, responsiva e interativa.

## Origem do Projeto

A criação deste site fictício foi uma atividade proposta pelo Professor **Celso Barreto**, do **SENAI CIMATEC**, como parte da avaliação da disciplina de Codificação para Front-End do Novo Ensino Médio - SESI.

## Estrutura do Site Proposta Originalmente

O escopo original do projeto previa as seguintes seções/páginas:

1.  **Página Inicial (Home):**
    * Banner com o nome da empresa e slogan.
    * Apresentação resumida da empresa.
    * Destaques dos cursos com botões para mais informações.
2.  **Sobre a Cajueiro Tech:**
    * História e missão da empresa.
    * Visão voltada à educação empreendedora.
    * Público-alvo.
3.  **Programas de Cursos:**
    * Apresentação de 3 modalidades de curso:
        * **Startup One:** Acesso a vídeos de treinamento e apostilas digitais.
        * **Startup Plus:** Inclui vídeos, apostilas e mentorias sobre construção de produtos e outros cursos.
        * **Startup Master:** Todos os benefícios anteriores, mais conteúdos sobre como construir uma startup do zero, com materiais extras de aceleração.
    * Cada curso apresentado em cards ou seções visuais atrativas.
4.  **Formulário de Contato:**
    * Campos para Nome, E-mail, Assunto e Mensagem.
    * (Originalmente, a implementação funcional em PHP era um desafio proposto).

## Tecnologias Utilizadas (Nesta Implementação)

* **HTML5:** Para a estrutura semântica do conteúdo.
* **Tailwind CSS (via CDN):** Para estilização rápida e responsiva, utilizando classes utilitárias.
* **CSS3 Personalizado:**
    * Variáveis CSS para gerenciamento da paleta de cores.
    * Classes personalizadas (em português) utilizando a diretiva `@apply` do Tailwind para agrupar estilos de componentes.
    * Animações e transições para melhorar a experiência do usuário.
* **JavaScript:**
    * Manipulação do DOM para interatividade (ex: menu mobile).
    * `IntersectionObserver` para animações de entrada ao rolar a página.

*(Nota: A solicitação original do professor incluía o uso preferencial de Bootstrap e a implementação de um formulário de contato funcional em PHP. Esta versão do projeto focou em HTML, Tailwind CSS e JavaScript para a interface, conforme iterações posteriores com o solicitante do desenvolvimento.)*

## Funcionalidades Implementadas (Página Inicial - `index.html`)

* **Design Responsivo:** O site se adapta a diferentes tamanhos de tela (desktop, tablet e mobile).
* **Paleta de Cores Moderna:** Utilização de tons de azul suaves com um laranja vibrante para acentos.
* **Cabeçalho Fixo e Interativo:**
    * Logo.
    * Navegação principal para desktop.
    * Menu mobile funcional com ícone de hambúrguer/fechar.
* **Seção Herói Impactante:**
    * Título e subtítulo claros.
    * Botão de Call-to-Action (CTA).
    * Ilustração com animação sutil de flutuação.
* **Seções de Conteúdo Informativas:**
    * Apresentação dos benefícios da Cajueiro Tech com ícones e descrições.
    * Destaque dos programas de curso em formato de cards.
* **Animações Suaves:**
    * Efeitos de `hover` em elementos interativos.
    * Animações de entrada para elementos das seções conforme o usuário rola a página.
* **Rodapé:** Com informações de copyright e links para redes sociais (exemplo).
* **Imagens Placeholder:** Utilizadas para simular o conteúdo visual.

## Como Executar

1.  Clone este repositório (se aplicável) ou salve o arquivo `index.html`.
2.  Abra o arquivo `index.html` em qualquer navegador web moderno.

Não há dependências de back-end ou processos de build complexos para esta versão da página inicial.

## Próximos Passos (Sugestões)

* Desenvolver as demais páginas do site (Sobre, Cursos, Contato).
* Integrar um sistema de back-end para o formulário de contato (se desejado).
* Substituir imagens placeholder por imagens finais e otimizadas.
* Refinar as animações e interações.
* Realizar testes de usabilidade e acessibilidade.

---

Este README fornece uma visão geral do projeto Cajueiro Tech e da sua implementação atual.
