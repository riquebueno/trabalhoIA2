# TIME
- Week 1: 21/05 até 27/05 - DONE
- Week 2: 28/05 até 03/06 - DONE
- Week 3: 04/06 até 10/06 - DONE
- Week 4: 11/06 até 17/06
-- fechar estrutura do dataset (qtas perguntas com 1 atributo, 2 ...), 
-- fechar proposta de preenchimento das consultas em linguagem natural (vou escrever alguns automaticamente e pedirei para outras pessoas colaborarem), 
-- enviar email para autor pedindo rede treinada, 
-- gerar primeira versão do artigo, 
-- conversar com Aline sobre nova proposta para o trabalho (foco na montagem do dataset, talvez não consiga rodar muita coisa), 
-- começar a implementar código que gerará o dataset. 
- Week 5: 18/06 até 24/06
- Week 6: 25/06 até 27/06
- APRESENTAÇÃO: 28/06

# TO DO
- Rodando WikiSQL ok
- Rodando SQLNet ok 


- Montar arquitetura geral da solução: quantas redes? qual será a base? vai rolar tradução? vai testar na prática?
- ok Estudar/Executar SQLNet
- Criar dataset português -> SQL? Precisa?
- Estudar/Executar alguma rede neural que traduza de português para inglês
- Escrever artigo

# DONE
- 
- 
- 
# COMO INSTALAR SQLNET
- download do git
- extrair zip
- tar -xjvf data.tar.bz2
- pip install torch torchvision
- pip install -r requirements.txt


- estou tentando fazer o script python extract_vocab.py rodar. Estou baixando o glove.42B.300z.zip. Depois vou extrair e rodar o script de novo.
- conseguir rodar o treinamento toy (interrompi na epoch 7) e depois o teste
- https://github.com/matheuss/google-translate-api

- Preciso escrever o que fiz até agora
- Preciso pensar em como montar o dataset
- Acredito que a principal entrega desse trabalho será um dataset





# trabalhoIA2
Código do trabalho 2 da disciplina Inteligência Artificial do doutorado no Instituto de Computação da UFF no primeiro semestre de 2018.

WIKISql
https://github.com/salesforce/WikiSQL

SQLNet
https://github.com/xiaojunxu/SQLNet
