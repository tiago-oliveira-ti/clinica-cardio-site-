🫀 CardioVita — Site de Clínica Médica
Projeto de estudo de Front-End | HTML5 + CSS3 | Estruturas sem

📁 Estrutura de Pastas
clinica-cardio/
│
├── index.html                  ← Página Principal (Home)
│
├── pages/
│   ├── sobre.html              ← Sobre a Clínica
│   ├── horario.html            ← Horários e Valores
│   └── contato.html            ← Contato e Formulário
│
├── assets/
│   └── css/
│       └── style.css           ← Folha de estilo global
│
└── README.md                   ← Este arquivo
📄Função de Cada Página
Página	Arquivo	Descrição
Lar	index.html	Banner principal, diferenciais da clínica e resumo da especialidade com CTA
Sobre	pages/sobre.html	História, linha do tempo, missão/visão/valores e equipe médica
Horários	pages/horario.html	Tabelas completas de horários por especialidade, valores de exames e convênios
Contato	pages/contato.html	Formulário de contato, endereços, telefones, WhatsApp e área de mapa
🏷️ Tags HTML Utilizadas
Estrutura e Semântica (HTML5)
Marcação	Uso no projeto
<!DOCTYPE html>	Declaração do tipo de documento
<html lang="pt-BR">	Raiz do documento com idioma definido
<head>	Metadados, links de CSS e fontes
<meta charset>	Cod UTF-8
<meta name="viewport">	Responsividade móvel
<meta name="description">	SEO — descrição da página
<title>	Título da aba do navegador
<link>	Vinculação de CSS externa e fontes
<header>	Cabeçalho semântico com logo e nav
<nav>	Navegação principal e breadcrumbs
<main>	Conteúdo principal (implícito nas seções)
<section>	Seções temáticas de conteúdo
<article>	Cartões de médicos e diferenciais
<aside>	Informações complementares
<footer>	Rodapé com links e direitos autorais
<address>	Informações de contato na pág. Contato
Texto e Tipografia
Marcação	Uso no projeto
<h1>um<h4>	Hierarquia de títulos
<p>	Parágrafos de texto
<strong>	Texto em destaque/negrito semântico
<small>	Textos auxiliares e notas
<span>	Elementos estilizados em linha
<caption>	Título da tabela (acessível)
Listas e Tabelas
Marcação	Uso no projeto
<ul>	Listas de navegação, serviços, convênios
<li>	Itens de lista
<table>	Tabela de horários e exames
<thead>/<tbody>	Divisão seminal da
<tr>	Linha da V
<th scope="col">	Cabeçalho da coluna (acessível)
<td>	Célula de dados
Formulário
Marcação	Uso no projeto
<form>	chance de contato
<label for="">	Rótulo acessível limitado à entrada
<input type="text">	Campo de texto (nome)
<input type="email">	Campo de e-mail com validação HTML5
<input type="tel">	Campo de telefone
<select>	Campo de seleção (assunto/origem)
<option>	Opções para selecionar
<textarea>	Campo de mensagem longa
<button type="submit">	Botão de envio
<button type="reset">	Botão de limpar
Links e Mídia
Marcação	Uso no projeto
<a href>	Links de navegação, email, telefone, WhatsApp
<a target="_blank" rel="noopener">	Links externos seguros
<img alt>	Imagens com texto alternativo (estrutura)
Acessibilidade e ARIA
Atribuição	Uso no projeto
role="banner"	Identifique o cabeçalho do leitor de tela
role="contentinfo"	Identificar o rodapé
role="list"/role="listitem"	Listas semânticas explícitas
aria-label	Descrição para elementos sem texto visível
aria-labelledby	Seção Vincula ao seu título h2
aria-current="page"	Indica a página ativa no breadcrumb
aria-required="true"	Campos obrigatórios do formulário
aria-live="polite"	Anuncia mensagem de sucesso ao leitor
aria-hidden="true"	Elementos ocultos decorativos do leitor
🎨 Decisões de Design
Paleta: Azul-marinho ( #0a2540) + vermelho cardíaco ( #c8102e) — cores que remetem à seriedade médica e ao coração
Tipografia: Playfair Display (títulos) + Source Sans 3 (texto) — combinação refinada e legível
Layout: CSS Grid e Flexbox puros, sem framework
Responsividade: Consultas de mídia em 768px e 560px
Variáveis ​​CSS: Todo o design system usa var(--cor-*), var(--font-*), facilitando personalização
🔧 Como Personalizar
Trocar especialidade: Soluções e Substituição "Cardiologia" / "CardioVita" pelo nome desejado em todos os arquivos
Núcleos: Edite as variáveis ​​no :rootdestyle.css
Logotipo: Substitua ou <div class="logo__icone">por uma tag<img>
Mapa real: Na página de Contato, descomente o <iframe>do Google Maps e insira o link do seu endereço
Formulário funcional: Integre com Formspree , EmailJS ou backend próprio
Imagens: Substitua os placeholders pelos <img src="assets/img/nome.jpg" alt="...">correspondentes
🚀 Sugestões de Melhoria Futura (para portfólio GitHub)
Nível Básico (próximas semanas)
Adicionar fotos reais no lugar dos placeholders
Integrar o formulário ao Formspree ou EmailJS
Incorporar o Google Maps com iframe real
Adicionar favicon personalizado
Nível Intermediário
Criar página de Blog / Artigos sobre saúde cardiológica
Implementar página 404 personalizada
animações de entrada com CSS @keyframesou AdicionarIntersection Observer
Criar modo escuro com prefers-color-schemee botão toggle
Adicionar filtro de tabela (JavaScript) para buscar exames por nome
Nível Avançado
Migrar para React + Vite mantendo o mesmo design
Criar sistema de agendamento com localStorage ou backend (Node.js + Express)
Implementar PWA (Progressive Web App) com service worker
Adicionar testes automatizados com Cypress ou Playwright (ótimo para QA!)
Fazer implantar no GitHub Pages com GitHub Actions CI/CD
Configurar domínio customizado (ex: cardiovita.com.br)
Implementar Google Analytics para métricas de acesso
QA / Qualidade (foco na carreira)
Criar plano de testes manual para o formulário
Documentar casos de teste em planilha (positivos, negativos, borda)
Implementar testes E2E com Cypress cobrindo o fluxo de contato
Fazer auditorias de acessibilidade com a extensão ax DevTools
Rodar Lighthouse e documentar as métricas de desempenho
📚 Conceitos de Front-End Demonstrados
✅ Estrutura semântica HTML5
✅ CSS com variáveis ​​customizadas (Design System básico)
✅ Layout com CSS Grid e Flexbox
✅ Responsividade com Media Queries
✅ Navegação entre várias páginas
✅ Formulário com validação HTML5 nativa
✅ Acessibilidade (ARIA, funções, rótulos)
✅ JavaScript básico (alternar menu, feedback de formulário)
✅ Boas práticas de SEO básicas (meta tags, títulos, alt)
✅ Organização de projeto em massas
Projeto desenvolvido como estudo de Front-End — ADS / Análise e Desenvolvimento de Sistemas.

Dio_me
