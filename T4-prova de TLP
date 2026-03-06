<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<title>Programa Escolar HTML e CSS</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f0f0f0;
}

/* MENU SUPERIOR */

.topo{
background:#333;
color:white;
padding:15px;
display:flex;
align-items:center;
}

.menu-btn{
font-size:25px;
cursor:pointer;
margin-right:20px;
}

.top-links a{
color:white;
margin:10px;
text-decoration:none;
font-weight:bold;
}

/* MENU LATERAL */

.sidebar{
height:100%;
width:0;
position:fixed;
background:#444;
overflow-x:hidden;
transition:0.3s;
padding-top:60px;
}

.sidebar a{
display:block;
color:white;
padding:10px;
text-decoration:none;
}

.sidebar a:hover{
background:#666;
}

/* CONTEÚDO */

section{
background:white;
margin:20px;
padding:20px;
border-radius:6px;
}

table{
border-collapse:collapse;
}

th,td{
border:1px solid black;
padding:8px;
}

button{
padding:8px;
}

footer{
background:#333;
color:white;
text-align:center;
padding:15px;
}

</style>

<script>
function abrirMenu(){
document.getElementById("menu").style.width="200px";
}

function fecharMenu(){
document.getElementById("menu").style.width="0";
}
</script>

</head>

<body>

<div class="topo">
<span class="menu-btn" onclick="abrirMenu()">☰</span>

<div class="top-links">
<a href="#home">Home</a>
<a href="#t1">T1</a>
<a href="#t2">T2</a>
<a href="#t3">T3</a>
<a href="#t4">T4</a>
<a href="#t5">T5</a>
</div>
</div>

<div id="menu" class="sidebar">
<a href="javascript:void(0)" onclick="fecharMenu()">Fechar ✖</a>
<a href="#home">Home</a>
<a href="#t1">Primeiro Trimestre</a>
<a href="#t2">Segundo Trimestre</a>
<a href="#t3">Terceiro Trimestre</a>
<a href="#fim">Fim</a>
</div>

<section id="home">
<h2>Sejam Bem-Vindos</h2>
<p>Programa criado por <b>Augusto Zamba</b></p>
</section>

<section id="t1">

<h2>Primeiro Trimestre</h2>

<h3>Lista</h3>
<ul>
<li>HTML</li>
<li>Formulário</li>
<li>Tabela</li>
</ul>

<h3>Tabela</h3>

<table>

<tr>
<th>Nome</th>
<th>Email</th>
</tr>

<tr>
<td>Augusto</td>
<td>augusto@email.com</td>
</tr>

<tr>
<td>Maria</td>
<td>maria@email.com</td>
</tr>

</table>

<h3>Formulário</h3>

<form>

Nome<br>
<input type="text"><br><br>

Email<br>
<input type="email"><br><br>

Mensagem<br>
<textarea></textarea><br><br>

<input type="submit" value="Enviar">

</form>

<h3>Imagem</h3>
<img src="imagem.jpg" width="200">

<h3>Áudio</h3>
<audio controls>
<source src="audio.mp3">
</audio>

<h3>Vídeo</h3>
<video width="300" controls>
<source src="video.mp4">
</video>

</section>

<section id="t2">

<h2>Segundo Trimestre</h2>

<h3>Introdução ao CSS</h3>

<p>
CSS significa Cascading Style Sheets.
Ele serve para melhorar o design das páginas web.
</p>

<ul>
<li>Mudar cores</li>
<li>Mudar fontes</li>
<li>Criar layouts</li>
</ul>

</section>

<section id="t3">

<h2>Terceiro Trimestre</h2>

<h3>A importância do CSS no desenho web</h3>

<p>
O CSS ajuda a deixar os sites bonitos, organizados e profissionais.
</p>

<p>
Ele separa o conteúdo HTML do design da página.
</p>

</section>

<section id="t4">
<h2>T4</h2>
📋 Estrutura HTML Completa
Tags usadas nos exemplos de Listas e Tabelas

1. Lista Não Ordenada (<ul>)
Usada para menus, navegação e agrupamentos sem ordem específica.

HTML Estrutural:
<!-- Lista básica -->
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>

<!-- Lista com classes para estilização -->
<ul class="modern-menu">
    <li>Dashboard</li>
    <li>Perfil</li>
    <li>Configurações</li>
</ul>

<!-- Lista com conteúdo complexo -->
<ul class="timeline">
    <li>
        <strong>2020</strong> - Início
        <p>Descrição do evento</p>
    </li>
    <li>
        <strong>2021</strong> - Avanço
        <p>Outra descrição</p>
    </li>
</ul>
Atributos importantes:
• class - Para aplicar estilos CSS específicos
• id - Identificador único (uso único na página)
Preview:
Item 1
Item 2
Item 3
2. Lista Ordenada (<ol>)
Usada quando a ordem dos itens importa (procedimentos, rankings).

HTML Estrutural:
<!-- Lista numerada padrão -->
<ol>
    <li>Primeiro passo</li>
    <li>Segundo passo</li>
    <li>Terceiro passo</li>
</ol>

<!-- Lista com tipo diferente -->
<ol type="A">
    <li>Opção A</li>
    <li>Opção B</li>
</ol>

<!-- Lista com start específico -->
<ol start="5">
    <li>Item 5</li>
    <li>Item 6</li>
</ol>
Atributos especiais:
• type="1|A|a|I|i" - Define o tipo de marcador
• start="número" - Inicia a numeração em número específico
• reversed - Ordem decrescente
Preview:
Primeiro passo
Segundo passo
Terceiro passo
3. Tabela Básica (<table>)
Estrutura completa de uma tabela HTML semântica.

HTML Estrutural:
<table class="dashboard-table">
    
    <!-- Cabeçalho da tabela -->
    <thead>
        <tr>
            <th>Nome</th>
            <th>Cargo</th>
            <th>Status</th>
        </tr>
    </thead>
    
    <!-- Corpo da tabela -->
    <tbody>
        <tr>
            <td>Ana Silva</td>
            <td>Designer</td>
            <td>Ativo</td>
        </tr>
        <tr>
            <td>Bruno Costa</td>
            <td>Dev</td>
            <td>Ativo</td>
        </tr>
    </tbody>
    
    <!-- Rodapé (opcional) -->
    <tfoot>
        <tr>
            <td colspan="3">Total: 2 usuários</td>
        </tr>
    </tfoot>
    
</table>
Tags essenciais:
• <table> - Container principal
• <thead> - Agrupa cabeçalhos
• <tbody> - Agrupa dados
• <tfoot> - Rodapé (opcional)
• <tr> - Table Row (linha)
• <th> - Table Header (célula de cabeçalho)
• <td> - Table Data (célula de dados)
Preview:
Nome	Cargo	Status
Ana Silva	Designer	Ativo
Bruno Costa	Dev	Ativo
4. Tabela com Células Mescladas
Uso de colspan e rowspan para layouts complexos.

HTML Estrutural:
<table class="complex-table">
    <thead>
        <tr>
            <th rowspan="2">Produto</th>
            <th colspan="2">Valores</th>
        </tr>
        <tr>
            <th>Custo</th>
            <th>Venda</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Notebook</td>
            <td>R$ 3.000</td>
            <td>R$ 4.500</td>
        </tr>
    </tbody>
</table>
Atributos de mesclagem:
• colspan="n" - Mescla n colunas horizontalmente
• rowspan="n" - Mescla n linhas verticalmente
Preview:
Produto	Valores
Custo	Venda
Notebook	R$ 3.000	R$ 4.500
5. Exemplo Completo - Estrutura HTML Documento
Como organizar tudo em um arquivo HTML válido.

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página</title>
    <style>
        /* CSS aqui ou link externo */
        ul { list-style: none; }
        table { border-collapse: collapse; }
    </style>
</head>
<body>

    <header>
        <h1>Título do Site</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Sobre</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Lista de Tarefas</h2>
            <ul>
                <li>Tarefa 1</li>
                <li>Tarefa 2</li>
            </ul>
        </section>

        <section>
            <h2>Dados</h2>
            <table>
                <thead>
                    <tr>
                        <th>Nome</th>
                        <th>Idade</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>João</td>
                        <td>25</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </main>

    <footer>
        <p>© 2024 Meu Site</p>
    </footer>

</body>
</html>
📌 Resumo das Tags
Listas
<ul> - Lista não ordenada
<ol> - Lista ordenada
<li> - Item de lista
<dl>, <dt>, <dd> - Lista de definição
Tabelas
<table> - Tabela
<thead>, <tbody>, <tfoot> - Seções
<tr> - Linha
<th> - Cabeçalho
<td> - Dado/célula
<p>Área de exercícios.</p>
</section>

<section id="t5">
<h2>T5</h2>
Listas e Tabelas Estilizadas
Dominando Pseudo-classes CSS para Interfaces Modernas

O que são Pseudo-classes?
Pseudo-classes são palavras-chave adicionadas a seletores CSS que especificam um estado especial do elemento selecionado. Elas permitem estilizar elementos com base em sua posição, estado de interação, ou relacionamento com outros elementos, sem precisar adicionar classes extras no HTML.

:hover
Ativado quando o usuário passa o mouse sobre o elemento
:nth-child()
Seleciona elementos com base em sua posição entre irmãos
:first-child
Seleciona o primeiro elemento filho de seu pai
:last-child
Seleciona o último elemento filho de seu pai
:not()
Seleciona elementos que NÃO correspondem ao seletor
:checked
Aplica a elementos de formulário marcados/checados
Listas Estilizadas
Transforme listas simples em componentes de interface interativos e visualmente atraentes.

Exemplo 1: Menu de Navegação Moderno
Dashboard
Perfil do Usuário
Configurações
Relatórios
Sair
.modern-menu li {
    padding: 1rem 1.5rem;
    transition: all 0.3s ease;
    border-left: 4px solid transparent;
    position: relative;
}

/* Efeito hover com movimento */
.modern-menu li:hover {
    background: linear-gradient(90deg, #6366f1, #8b5cf6);
    color: white;
    padding-left: 2.5rem;
    transform: translateX(10px);
}

/* Ícone aparece no hover */
.modern-menu li::before {
    content: '→';
    position: absolute;
    left: -20px;
    transition: left 0.3s ease;
}

.modern-menu li:hover::before {
    left: 15px;
}

/* Cores alternadas */
.modern-menu li:nth-child(odd) {
    background: linear-gradient(90deg, #ede9fe, #ddd6fe);
}
Exemplo 2: Timeline Vertical
2020 - Início da jornada
Primeiros passos no desenvolvimento web

2021 - Especialização
Foco em CSS avançado e animações

2022 - Projetos Grandes
Liderança em equipes de frontend

2023 - Inovação
Implementação de design systems

/* Linha vertical conectando itens */
.timeline::before {
    content: '';
    position: absolute;
    left: 20px;
    width: 2px;
    background: linear-gradient(to bottom, var(--primary), var(--secondary));
}

/* Marcadores circulares */
.timeline li::before {
    content: '';
    position: absolute;
    left: 11px;
    width: 20px;
    height: 20px;
    background: var(--primary);
    border-radius: 50%;
    border: 4px solid white;
    transition: all 0.3s ease;
}

/* Efeito glow no hover */
.timeline li:hover::before {
    background: var(--secondary);
    box-shadow: 0 0 20px var(--secondary);
}
Tabelas Estilizadas
Tabelas não precisam ser monótonas. Com pseudo-classes, criamos dashboards interativos e responsivos.

Exemplo 1: Tabela de Dashboard
Usuário	Cargo	Status	Último Acesso
Ana Silva	Designer	Ativo	2 min atrás
Bruno Costa	Developer	Ativo	1 hora atrás
Carla Dias	Manager	Pendente	3 dias atrás
Daniel Souza	Analista	Inativo	1 semana atrás
Elisa Lima	Marketing	Ativo	5 min atrás
/* Linhas zebradas */
.dashboard-table tbody tr:nth-child(even) {
    background: #f8fafc;
}

/* Efeito hover com elevação */
.dashboard-table tbody tr:hover {
    background: #e0e7ff;
    transform: scale(1.01);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

/* Destaque na primeira linha de dados */
.dashboard-table tbody tr:first-child td {
    border-top: 3px solid var(--accent);
}

/* Remove borda da última linha */
.dashboard-table tbody tr:last-child td {
    border-bottom: none;
}
Exemplo 2: Tabela Comparativa
Recurso	Básico	Pro	Enterprise
Usuários	5	Ilimitado	Ilimitado
Armazenamento	10GB	100GB	1TB
Suporte	Email	24/7	Prioritário
API Access	✗	✓	✓
Preço	Grátis	R$29/mês	R$99/mês
/* Destaque na coluna do meio (Plano Pro) */
.compare-table tbody td:nth-child(3) {
    background: #ecfdf5;
    font-weight: 700;
    color: #059669;
}

/* Ícone de estrela no cabeçalho (exceto primeira coluna) */
.compare-table thead th:not(:first-child)::after {
    content: '★';
    position: absolute;
    top: 5px;
    right: 5px;
    color: #fbbf24;
}

/* Primeira coluna diferenciada */
.compare-table tbody td:first-child {
    font-weight: 600;
    text-align: left;
    background: #f1f5f9;
}
Checklist Interativo
Exemplo prático combinando :checked com listas. Clique nos itens abaixo:

Entender a sintaxe de pseudo-classes
Praticar com :hover e :focus
Dominar :nth-child() e :nth-of-type()
Criar tabelas responsivas
Aplicar em projetos reais
/* Estado padrão */
.checklist li::before {
    content: '☐';
    color: var(--primary);
}

/* Quando marcado (classe .checked adicionada via JS) */
.checklist li.checked {
    background: rgba(16, 185, 129, 0.1);
    text-decoration: line-through;
    opacity: 0.7;
}

.checklist li.checked::before {
    content: '☑';
    color: var(--accent);
}
Dicas Essenciais
Performance
Evite aninhar muitas pseudo-classes complexas. :nth-child() com fórmulas complexas podem impactar a renderização em listas muito grandes.

Acessibilidade
Sempre combine :hover com :focus para usuários de teclado. Use :focus-visible para estilos de foco mais elegantes.

Especificidade
Pseudo-classes têm o mesmo peso que classes (0,1,0). :not() não adiciona especificidade, mas seu conteúdo sim.

Pratique esses conceitos e crie interfaces incríveis! 🚀

Conteúdo didático sobre CSS Moderno
<p>Área de conteúdos.</p>
</section>

<section id="fim">

<h2>Tipos de folhas de estilos</h2>

<ul>
<li>Inline</li>
<li>Interno</li>
<li>Externo</li>
</ul>

</section>

<footer>
© 2026 Trabalho Escolar HTML e CSS
</footer>

</body>
</html>
