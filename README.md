# comandos_uteis_terminal-
### 1. **Navegar entre diretórios**
- **Ir para o diretório pai:**
  ```bash
  cd ..
  ```

### 2. **Manipulação de arquivos e diretórios**
- **Listar arquivos em um diretório:**
  ```bash
  ls
  ```
- **Remover um arquivo específico:**
  ```bash
  rm <nome_do_arquivo>
  ```
  Exemplo:
  ```bash
  rm 53d5a415da537c321e24-images.png
  ```

- **Remover um diretório e todo o seu conteúdo:**
  ```bash
  rm -r <nome_do_diretorio>
  ```

- **Criar um diretório:**
  ```bash
  mkdir <nome_do_diretorio>
  ```

### 3. **Manipulação do Git**
- **Adicionar alterações ao próximo commit:**
  ```bash
  git add <arquivo_ou_diretório>
  ```

- **Fazer commit das alterações:**
  ```bash
  git commit -m "Mensagem do commit"
  ```

- **Enviar mudanças para o repositório remoto:**
  ```bash
  git push origin <nome_da_branch>
  ```

- **Atualizar branch local com as mudanças da branch remota:**
  ```bash
  git pull origin <nome_da_branch>
  ```

### 4. **Manipulação de serviços com PM2**
- **Iniciar uma aplicação com PM2:**
  ```bash
  pm2 start <nome_arquivo>.js --name <nome_da_app>
  ```

- **Parar uma aplicação:**
  ```bash
  pm2 stop <nome_da_app>
  ```

- **Reiniciar uma aplicação:**
  ```bash
  pm2 restart <nome_da_app>
  ```

- **Verificar o status das aplicações:**
  ```bash
  pm2 status
  ```

### 5. **Permissões de arquivos**
- **Dar permissão de execução a um script:**
  ```bash
  chmod +x <nome_do_script>
  ```

### 6. **Manipulação do Docker**
- **Listar os containers em execução:**
  ```bash
  docker ps
  ```

- **Iniciar um container:**
  ```bash
  docker start <container_id>
  ```

- **Parar um container:**
  ```bash
  docker stop <container_id>
  ```

