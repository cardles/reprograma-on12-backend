# RESOLUÇÃO <h1>

*1. Faça um algoritmo que mostre o passo a passo de uma troca de lâmpada queimada.*

(inicio)  
inserir 'interruptor'  
inserir 'lâmpada atual'  
inserir 'lâmpada nova'  
inserir 'escada'  
ligar o 'interruptor'  
se a 'lâmpada atual' acender  
prosseguir para "fim"  
se a 'lâmpada atual' não acender  
prosseguir para "troca de lâmpada"  
(troca de lâmpada)  
desligar o 'interruptor'  
inserir a 'escada' sob a 'lâmpada atual'  
pegar a 'lâmpada nova'  
subir na 'escada' com a 'lâmpada nova'  
retirar a 'lâmpada atual'  
rosquear a 'lâmpada nova' no soquete  
descer a 'escada' com a 'lâmpada atual'  
ligar o 'interruptor'  
se a 'lâmpada nova' acender  
prosseguir para "fim"  
se a 'lâmpada nova' não acender  
prosseguir para "troca de lâmpada"  
(fim)  

*2. Faça um algoritmo que mostre o passo a passo de uma lavar pratos.*

(inicio)  
inserir 'prato sujo'  
inserir 'bucha'  
inserir 'detergente'  
inserir 'torneira'  
inserir 'escorredor'  
colocar o 'detergente' na 'bucha'  
abrir a 'torneira'  
molhar a 'bucha'  
molhar o 'prato sujo'  
fechar a 'torneira'  
esfregar a 'bucha' no 'prato sujo'  
abrir a 'torneira'  
enxaguar o 'prato sujo'  
se 'prato sujo' estiver sujo  
voltar para "inicio"  
se 'prato sujo' estiver limpo  
posicionar ele no 'escorredor'  
(fim)  



*3. Faça um algoritmo que mostre o passo a passo de uma troca de um pneu furado.*

(inicio)  
inserir 'carro'  
inserir 'roda'  
inserir 'pneu furado'  
inserir 'estepe'  
inserir 'macaco'  
inserir 'chave de roda'  
(suspender)  
posicionar 'macaco' sob o 'carro'  
levantar carro com o 'macaco' até que o 'pneu furado' fique suspenso  
(soltar parafusos)  
encaixar a 'chave de roda' em um 'parafuso' da 'roda'  
girar a 'chave de roda' no sentido horário até que o 'parafuso' se solte  
(soltar roda)  
repetir "soltar parafusos" em 'parafuso' até que o número de 'parafuso' restante seja igual a 0  
(trocar roda)  
retirar 'pneu' do eixo  
inserir 'estepe' no eixo  
(parafusar estepe)  
inserir 'parafuso' no 'estepe'  
girar a 'chave de roda' no sentido anti-horário até que o 'parafuso' esteja firme  
(finalização)  
repetir "parafusar estepe" até que o número de 'parafuso' restante seja igual a 0  
abaixar o 'carro' com o 'macaco' até que o 'espete' toque o chão   
retirar o 'macaco' do 'carro'  
guardar 'roda' com 'pneu furado', 'macaco' e 'chave de roda' no 'carro'  
(fim)  


*4. Faça um algoritmo que mostre o passo a passo de um débito num caixa eletrônico.*

(inicio)  
inserir o cartão  
reconhecer 'dados do usuário'  
processar 'dados do usuário'  
se estiverem incorretos   
voltar para "inicio"  
se estiver corretos   
prosseguir para "saque"  
(saque)  
entrar na conta bancária do usuário  
apresentar as opções de botões: 'saque', 'saldo', 'pagamentos', 'depósito', 'transferência' e 'outros'  
reconhecer 'saque' selecionado  
processar 'saque'  
solicitar 'valor'  
reconhecer 'valor' inserido  
processar 'valor'  
se 'saldo' menor que o 'valor' do 'saque'  
sugerir entrar no cheque especial  
se 'saldo' igual ou acima do 'valor' do 'saque'  
prosseguir para "confirmação de dados"  
(confirmação de dados)  
solicitar confirmação de 'dados do usuário'  
reconhecer 'dados do usuário'  
processar 'dados do usuário'  
se estiverem incorretos  
voltar para "confirmação de dados"  
se estiverem corretos  
prosseguir para "liberação de notas"  
(liberação das notas)  
debitar o 'valor' de 'saque' da conta bancária do usuário  
avisar ao usuário sobre o local de saída  
selecionar as notas referentes ao 'valor' inserido  
posicionar as notas na gaveta de saída  
liberar as notas  
reconhecer a retirada das notas  
processar a retirada das notas  
prosseguir para "fim"  
(finalização)  
apresentar as opções nos botões: 'finalizar' e 'voltar à tela inicial'  
reconhecer solicitação 'finalizar'  
processar 'finalizar'  
finalizar a conta do usuário  
(fim)  


*5. Faça um algoritmo que mostre o passo a passo de um professor corrigindo uma pilha (de quantidade indefinida) de provas, com 5 questões cada.*

(inicio)  
inserir 'gabarito'  
inserir 'diário de sala'  
inserir 'pilha de X provas'  
(seleção)  
selecionar 'prova' no topo da 'pilha de X provas'  
checar os dados do aluno no 'diário de sala'  
se não estiverem presentes   
criar 'segunda pilha de provas' para checar com o 'diário de sala' de outra turma  
se estiverem presentes  
prosseguir para "correção"  
(correção)  
checar 'resposta questão 1'  
se a 'resposta questão 1' da 'prova' for igual a 'resposta questão 1' do 'gabarito'  
escrever 'correta' na 'prova'  
se a 'resposta questão 1' da 'prova' não for igual a 'resposta questão 1' do 'gabarito'  
escrever 'incorreta' na 'prova'  
(repetir correção)  
repetir "correção" para 'resposta questão 2'  
repetir "correção" para 'resposta questão 3'  
repetir "correção" para 'resposta questão 4'  
repetir "correção" para 'resposta questão 5'  
(pontos)  
questões de resposta 'correta' valem 2 pontos  
questões de resposta 'incorreta' valem 0 pontos  
escrever pontos no campo correspondente no 'diário de sala'  
(repetir pontos)  
repetir "pontos" para 'resposta questão 2'  
repetir "pontos" para 'resposta questão 3'  
repetir "pontos" para 'resposta questão 4'  
repetir "pontos" para 'resposta questão 5'  
(nota final)  
somar 'resposta questão 1', 'resposta questão 2', 'resposta questão 3', 'resposta questão 4' e 'resposta questão 5'  
o resultado da operação é denominado 'soma final'  
escrever 'soma final' no campo correspondente no 'diário de sala'  
se a 'soma final' for igual ou maior que 5, o aluno está 'aprovado'  
se a 'soma final' for menor que 5, o aluno está 'reprovado'  
escrever no campo 'nota final' do 'diário de sala' a 'soma final' na cor azul se 'aprovado'  
escrever no campo 'nota final' do 'diário de sala' a 'soma final' na cor vermelho se 'reprovado'  
(provas restantes)  
voltar a "seleção" até que 'X' em 'pilha de X provas' seja igual a 0  
(fim)  


*6. Faça um algoritmo que represente a brincadeira "Morto! Vivo!".*

(inicio)  
inserir 'moderador'  
inserir 'jogadores'  
inserir 'jogador1'  
inserir 'jogador2'   
inserir movimento 'abaixar'  
inserir movimento 'levantar'  
inserir comando 'morto'  
inserir comando 'vivo'  
(regras)  
se 'moderador' disser o comando 'morto'  
'jogadores' realizam o movimento 'abaixar'  
se 'moderador' disser o comando 'vivo'  
'jogadores' realizam o movimento 'levantar'  
(exemplo de eliminação)  
se 'moderador' disser o comando 'morto' e 'jogador1' realizar o movimento 'levantar'  
'jogador1' está fora do jogo  
se 'moderador' disser o comando 'vivo' e 'jogador2' realizar o movimento 'abaixar'  
'jogador2' está fora do jogo  
(resultado)  
repetir "eliminação" até que o número de 'jogadores' seja igual a 1  
o restante é denominado 'jogador vencedor'  
(fim)  


*7. Faça um algoritmo que some três números.*

(inicio)  
inserir variável 'X'  
inserir variável 'Y'  
inserir variável 'Z'  
somar 'X', 'Y' e 'Z'   
o resultado da operação é denominado 'resultado final'  
(fim)  


*8. Faça um algoritmo que descubra se um número é par ou ímpar.* 

(inicio)  
inserir variável 'X'  
se 'X' divido por 2 resultar em um número inteiro  
'X' é um número par  
se 'X' dividido por 2 resultar em um número real que não seja nem inteiro e nem natural  
'X' é um número ímpar  
(fim)  


*9. Faça um algoritmo para calcular a média aritmética entre duas notas de um aluno e mostrar sua situação, que pode ser aprovado ou reprovado.*

(inicio)  
inserir variável 'nota1'  
inserir variável 'nota2'  
inserir 'nota de corte'  
somar 'nota1' com 'nota2'  
o resultado da operação é denominado 'resultado1'  
dividir 'resultado1' por 2  
o resultado da operação é denominado 'media final'  
se 'media final' for maior ou igual a 'nota de corte'  
o aluno está 'aprovado'  
se 'media final' for inferior a 'nota de corte'  
o aluno está 'reprovado'  
(fim)  


*10. Faça um algoritmo para calcular o novo salário de um funcionário. Sabe-se que os funcionários que recebem atualmente salário de até R$500 terão aumento de 20%; os demais terão aumento de 10%.*

(inicio)  
inserir 'salário atual'  
se 'salário atual' for igual ou menor que 500,00 reais  
multiplicar 'salário atual' por 0,2  
o resultado da operação é denominado 'acréscimo'  
somar 'acréscimo' com 'salário atual'  
o resultado da operação é denominado 'salário final'  
se 'salário atual' for maior que 500,00 reais  
multiplicar 'salário atual' por 0,1  
o resultado da operação é denominado 'acréscimo'  
somar 'acréscimo' com 'salário atual'  
o resultado da operação é denominado 'salário final'  
(fim)