# PAP2027-DinoFinder
mapa interativo de formações geológicas de fosseis pré históricos 
# Dino Finder

**PAP 2027**  
**TGPSI, Escola Secundária de Vergílio Ferreira**  
Aluno: Miguel Soares | Turma: 12.º 13 | N.º18]  
Professor orientador: Jorge Silva  

## Descrição
O **Dino Finder** é um site web interativo de pesquisa e localização de espécies de dinossauros e respetivas formações rochosas. A plataforma resolve a falta de ferramentas visuais e intuitivas para explorar dados paleontológicos, permitindo aos utilizadores pesquisar espécimes e visualizar a sua localização geográfica exata através de um mapa 2D interativo. Ao interagir com o mapa, o sistema apresenta dinamicamente imagens dos vestígios fósseis e dados detalhados guardados centralmente numa base de dados.

## Objetivos
- Criar uma interface web intuitiva e responsiva com um mapa 2D interativo para pesquisa de fósseis.
- Desenvolver uma base de dados relacional (MySQL) para gerir espécies, formações geológicas e imagens dos vestígios.
- Integrar o Front-End com o Back-End em PHP para carregar dinamicamente os pontos geográficos e detalhes dos achados.

## Funcionalidades

### Núcleo mínimo (obrigatório)
- [ ] Pesquisa de espécies e formações rochosas por nome.
- [ ] Mapa 2D interativo com marcadores (pins) nas coordenadas dos achados.
- [ ] Visualização de popup/janela com detalhes e imagem dos vestígios fósseis ao clicar num ponto.
- [ ] Base de dados relacional com ligação PHP para consulta dinâmica.

### Extras (se houver tempo)
- [ ] Área de administração com sistema de login para inserir novos registos e imagens.
- [ ] Filtro avançado por período geológico (ex.: Cretácico, Jurássico, Triásico).

## Tecnologias

| Camada | Tecnologia |
| :--- | :--- |
| **Interface** | HTML5, CSS3, JavaScript, Bootstrap 5, Leaflet.js |
| **Servidor** | PHP (WampServer) |
| **Base de dados** | MySQL (phpMyAdmin) |
| **Outras** | GitHub (Controlo de versões) |

## Base de dados (tabelas previstas)
- `especies` (id_especie, nome_especie, dieta, descricao_vestigios, imagem_vestigio)
- `formacoes_rochosas` (id_formacao, nome_formacao, localizacao, era_geologica)
- `fossaes_encontrados` (id_fosil, id_especie, id_formacao, latitude, longitude, data_descoberta)
- `utilizadores` (id_utilizador, login, senha)

## Planeamento

| Fase | Período | Estado |
| :--- | :--- | :--- |
| Análise e modelação da base de dados | [nov] | Por fazer |
| Desenvolvimento do núcleo mínimo | [dez - mar] | Por fazer |
| Testes e correções | [abr] | Por fazer |
| Relatório e apresentação | [mai - jun] | Por fazer |

## Registo de progresso
- **[Outubro 2026]**: Criação do repositório e apresentação inicial do projeto Dino Finder.
