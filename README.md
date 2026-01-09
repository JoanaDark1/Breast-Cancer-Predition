# Resumo do projeto

## O problema
Nos últimos anos, as taxas de incidência de câncer de mama aumentaram 0,6% ao ano. 
O câncer de mama é a segunda principal causa de morte por câncer em mulheres. A chance de qualquer mulher morrer de câncer de mama é de cerca de 2,5%.
Ferramentas de diagnóstico modernas podem ajudar a salvar a vida de mais mulheres. 

## Abordagem
Primeiramente foi feita uma análise exploratória para investigar a correlação entre algumas variáveis e o diagnóstico de massa maligna. 
Então foi implementada uma busca pelos melhores parâmetros para a criação de uma árvore de decisão.

## Resultados
* Acurácia: 94.74%
* Recall : De todos os casos benignos o modelo classificou corretamente 95% deles como benigno, De todos os casos malignos o modelo classificou corretamente 94% deles como maligno
* Precision: Na precisão da classificação da massa ser benigna, de todas as vezes que o modelo classificou uma massa como benigna ele acertou 96%, e de todas as vezes que o modelo classificou uma massa como maligna ele acertou 92%
