# Projeto-Sujeito-Progamador
# Calculadora Álcool vs Gasolina

Uma calculadora web para determinar qual combustível é mais vantajoso financeiramente com base no preço por litro.

## Funcionalidades

- **Comparação em tempo real**: Insira os preços do álcool e da gasolina para receber uma recomendação instantânea.
- **Explicação do cálculo**: Link integrado para uma página que detalha a fórmula utilizada.
- **Design responsivo**: Adaptável a diferentes tamanhos de tela.
- **Feedback visual**: Resultado destacado com animação e cores intuitivas.

## Como Usar

1. **Acesse a calculadora**:
   - Abra o arquivo `index.html` em um navegador.

2. **Insira os preços**:
   - Preencha os campos "Álcool (Preço por Litro)" e "Gasolina (Preço por Litro)".
   - Exemplo: `Álcool: R$ 4.90` | `Gasolina: R$ 6.80`.

3. **Calcule**:
   - Clique no botão "Calcular" para ver a recomendação.

4. **Resultado**:
   - A seção "Compensa usar..." será exibida com:
     - Recomendação (Álcool ou Gasolina).
     - Preços inseridos formatados.

## Como o Cálculo é Feito

A fórmula utiliza a **relação entre os preços**:
(Preço do Álcool / Preço da Gasolina)
- **Resultado < 0.7**: Compensa usar Álcool.
- **Resultado ≥ 0.7**: Compensa usar Gasolina.

Para detalhes, clique em *"Clique aqui"* no canto inferior direito da página.

## Tecnologias Utilizadas

- **HTML**: Estrutura do conteúdo.
- **CSS**: Estilização e responsividade.
- **JavaScript**: Lógica de cálculo e interatividade.

## Estrutura de Arquivos
<p>├── index.html # Página principal<p>
<p>├── style.css # Estilos globais<p>
<p>├── script.js # Lógica da calculadora<p>
<p>├── calculo.html # Explicação da fórmula<p>
<p>└── source/<p>
<p>└── imagens/<p>
<p>├── Bombadecombustivel.jpg # Logo do projeto<p>
<p>└── duvida.png # Ícone de ajuda<p>

## Execução Local

1. Clone o repositório ou baixe os arquivos.
2. Certifique-se de que a pasta `source/imagens` contém as imagens:
   - `Bombadecombustivel.jpg`
   - `duvida.png`
3. Abra `index.html` em um navegador.

## Autor

**Andrey Beserra**  
Projeto desenvolvido para estudos em programação web com base em atividades do Sujeito Progamador
