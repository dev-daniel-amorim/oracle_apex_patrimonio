# Projeto Oracle Apex patrimônio (portfólio)

Tive a missão de desenvolver para prefeitura de Jõao Pessoa/PB em oracle Apex, dois aplicativos para controlar os ativos juntamente com leitor RFID também desenvolvido por mim e
disponível [AQUI!](https://github.com/dev-daniel-amorim/RFID_UHF/blob/main/README.md)

***
O sistema de patrimônio é dividido em duas aplicações:
- PATRIMÕNIO APP: Aplicativo mobile desenvolvido para fazer a comunicação entre o leitor RFID e o aplicativo PATRIMÔNIO DESKTOP, enviando as leituras das etiquetas 
RFID para o banco oracle ([mais detalhes clique aqui](https://github.com/dev-daniel-amorim/RFID_UHF/blob/main/README.md)).

- PATRIMÔNIO DESKTOP: O aplicativo DESKTOP controla todos os ativos, desde a criação do empenho, leitura das notas fiscais XML para geração dos tombamentos consequentemente
geração do patrimônio, distribuição dos ativos entre os setores, geranciamento da movimentação dos ativos, transferências, controle de baixas, manutenções, depreciação cessão de uso
e controle de inventário periódicos.

# Software Patrimônio Desktop
### Login

<p align="center">
  <img src="https://github.com/user-attachments/assets/c3cdfe6a-9c7d-4a65-8ccc-0208bf8b769a" width="30%" />
</p>
Os usuários são cadastrados previamente com email e cpf e uma senha padrão que pode ser mudada no primeiro acesso.

### Página principal
<p align="center">
  <img src="https://github.com/user-attachments/assets/ab8bd39f-0486-447d-ba9f-31f7dac9e112" width="60%" />
</p>

Na página principal o usuário tem acesso direto à informações de seu setor de lotação como:
- Transferências pendentes
- Recebomentos pendentes;
- Total de equipamentos (do seu setor);
- Eventos;
- Cessão de uso;
- Não localizados.

### Menu da página principal
<p align="center">
  <img src="https://github.com/user-attachments/assets/47507ae9-75cd-4862-bca0-de5274be46ce" width="60%" />
</p>

No mega menu, o usuário consegue ver todo o mapa da aplicação e nele é possível navegar entre todas as telas, que são divididas em
categorias:

- cadastros;
- movimentações de equipamentos;
- inventário;
- outros.

### Telas de cadastros
#### Cadastramento de prédios (matriz e filiais)

<p align="center">
  <img src="https://github.com/user-attachments/assets/91fef4b6-a1df-465f-adca-8122497d931c" width="60%" />
</p>

#### Cadastramento de setores/salas

<p align="center">
  <img src="https://github.com/user-attachments/assets/e2fbb1a1-b915-4ed9-bfed-34aaf1fc32fe" width="60%" />
</p>

#### Cadastramento de usuário por sala ou setor

<p align="center">
  <img src="https://github.com/user-attachments/assets/d868442e-0293-4897-9538-3ac25995e982" width="60%" />
</p>



#### Cadastramento Leitor RFID para usuário inventariante

<p align="center">
  <img src="https://github.com/user-attachments/assets/851d88f5-95e0-4c4b-89ec-78398d71f3ca" width="60%" />
</p>
 Nesta tela, cadastramos cada leitor RFID vinculado a um usuário inventariante, essa etapa é muito importante
 pois o leitor RFID só ficará apto a iniciar um invetário se estiver vinculado à pessoa e ela responsável por 
 cada cada entrada de tombamento dos ativos.


### Telas de movimentações de equipamentos
#### Transferir equipamentos

<p align="center">
  <img src="https://github.com/user-attachments/assets/41ff28a8-c33f-4ace-8d81-a1a17a6d693d" width="60%" />
</p>

Nessa tela o usuário consegue fazer a transferência de equipamentos para outros setores ou prédios (matriz ou filiais).

#### Rastrear movimentação

<p align="center">
  <img src="https://github.com/user-attachments/assets/942c0e65-17c6-4385-8db1-1fd6f14547e9" width="60%" />
</p>

Aqui o usuário consegue verificar toda movimentação de um ativo através do seu tombo desde sua criação no patrimônio.

#### Pendência equipamento

<p align="center">
  <img src="https://github.com/user-attachments/assets/c4d5e1dc-862b-4a6f-ae27-b6a2da8f6089" width="60%" />
</p>

Pendências, são as movimentações efetuadas no seu setor/sala, equipamentos transferidos, recebidos ou enviados para eventos ou emprestimos.


#### Não encontrados

<p align="center">
  <img src="https://github.com/user-attachments/assets/a60e17d2-9398-4b92-8139-0f0e1c13e8a1" width="60%" />
</p>

Equipamentos podem ser perder no meio dos processos (transferências, recebimentos, eventos e etc), estes são transferidos para lista
de equipamentos não encontrados até que seja solucionado (encontrado e relocado ou dado baixa).



<hr>
[<< Voltar para página inicial](https://github.com/dev-daniel-amorim)

