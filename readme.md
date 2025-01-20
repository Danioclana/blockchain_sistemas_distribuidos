
# Blockchain Interface

Este é um projeto de uma interface para interagir com uma blockchain simples. Ele permite que você crie transações, mine blocos e visualize a blockchain atual. Além disso, oferece a possibilidade de registrar e sincronizar novos nós, formando uma rede descentralizada.

## Funcionalidades

- **Criar Transação**: Envie transações entre os participantes da blockchain.
- **Minerar Bloco**: Minerar novos blocos e adicioná-los à blockchain.
- **Exibir Blockchain**: Veja o conteúdo atual da blockchain.
- **Registrar Nó**: Registre um novo nó para fazer parte da rede.
- **Sincronizar Blockchain**: Resolva conflitos de consenso e sincronize a blockchain com outros nós.

## Como Executar o Projeto

1. Clone este repositório para o seu computador:
   ```bash
   git clone https://github.com/seu-usuario/blockchain-interface.git
   ```

2. Instale as dependências:
   ```bash
   cd blockchain-interface
   pip install -r requirements.txt
   ```

3. Execute o servidor Flask:
   ```bash
   python app.py
   ```

   O servidor estará disponível em `http://127.0.0.1:5000`

## Como Usar

1. **Criar uma Transação**:
   - Envie transações entre um remetente e um destinatário, especificando a quantidade.
   
2. **Minerar Bloco**:
   - Clique no botão "Minerar" para minerar um novo bloco e adicioná-lo à blockchain.

3. **Exibir Blockchain**:
   - Clique no botão "Carregar Blockchain" para visualizar o estado atual da blockchain.

4. **Registrar Nó**:
   - Registre um novo nó na rede para que ele possa compartilhar e sincronizar a blockchain.
      
   Crie outros nós usando:
   ```bash
   python app.py -p <porta>
   ```

5. **Sincronizar Blockchain**:
   - Ao minerar ou adicionar um nó, a blockchain será sincronizada automaticamente.

## Estrutura do Projeto

- `app.py`: Arquivo principal do servidor Flask que gerencia as requisições e a lógica da blockchain.
- `templates/`: Contém os arquivos HTML da interface.
- `static/`: Contém os arquivos de estilo (CSS) e outros recursos estáticos.

## Contribuindo

Se você deseja contribuir para este projeto, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch para sua nova feature (`git checkout -b feature/nova-feature`).
3. Faça suas alterações e commit (`git commit -am 'Adiciona nova feature'`).
4. Faça um push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.