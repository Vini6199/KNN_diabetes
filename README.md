# KNN

O **KNN (K-Nearest Neighbour)** é um dos modelos mais simples de se entender, onde temos uma variável target (y) e uma ou mais variáveis explicativas (x), e a partir disso, queremos calcular a distância entre os novos inputs e os k pontos mais próximos dos grupos de classes já conhecidos que melhor separem os dados.

K se refere a quantidade de vizinhos mais próximos que podem ser usados para fazer a votação de qual classe o input pertence. Então para K = 10, se houverem 7 vizinhos mais próximos da classe A e 3 vizinhos mais próximos da classe B, a classe A será a escolhida para esse input.

**Quando usar KNN?** Quando nossos conjuntos de dados forem menores e nossa target não for muito complexa, pois o KNN é um modelo "preguiçoso", e não aprende padrões, apenas mede distâncias.

# Variáveis do meu case de diabetes

Diversas restrições foram aplicadas na seleção dessas instâncias a partir de um banco de dados maior. Em particular, todos os pacientes aqui são mulheres com pelo menos 21 anos de idade e de ascendência indígena Pima.

## Descrição das Variáveis

- **Pregnancies**: Número de vezes que a paciente esteve grávida.
- **Glucose**: Concentração de glicose plasmática após 2 horas em um teste oral de tolerância à glicose.
- **BloodPressure**: Pressão arterial diastólica (mm Hg).
- **SkinThickness**: Espessura da dobra cutânea do tríceps (mm).
- **Insulin**: Nível de insulina sérica após 2 horas (mu U/ml).
- **BMI**: Índice de massa corporal (peso em kg / altura em m²).
- **DiabetesPedigreeFunction**: Função de pedigree para diabetes.
- **Age**: Idade (em anos).
- **Outcome**: Variável de classe (0 ou 1), indicando se o paciente possui diabetes ou não.
