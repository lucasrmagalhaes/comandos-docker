<table>
  
  <tr>
    <th>Comando:</th>
    <th>Descrição:</th>
  </tr>
 
  <tr>
    <td>docker</td>
    <td>Lista os comandos.</td>
  </tr>
  
  <tr>
    <td>docker ps</td>
    <td>Lista os processos em execução.</td>
  </tr>
  
  <tr>
    <td>docker ps -a</td>
    <td>Lista todos os processos.</td>
  </tr>
  
  <tr>
    <td>docker images</td>
    <td>Lista as imagens.</td>
  </tr>
  
  <tr>
    <td>docker pull nome-imagem</td>
    <td>Faz o download da imagem.</td>
  </tr>
  
  <tr>
    <td>docker pull nome-imagem:14.0</td>
    <td>Faz o download da imagem com a versão informada.</td>
  </tr>
  
  <tr>
    <td>docker run -it --name nome-container nome-imagem</td>
    <td>Cria o container.</td>
  </tr>
  
  <tr>
    <td>docker inspect numero-id</td>
    <td>Mostra informações do container.</td>
  </tr>
  
  <tr>
    <td>docker stop numero-id</td>
    <td>Para a execução do container.</td>
  </tr>
  
  <tr>
    <td>docker start numero-id</td>
    <td>Inicia a execução do container.</td>
  </tr>
  
  <tr>
    <td>docker attach numero-id</td>
    <td>Entra no container.</td>
  </tr>
  
  <tr>
    <td>docker diff numero-id</td>
    <td>Mostra todas as alterações dentro do container.</td>
  </tr>
  
  <tr>
    <td>docker commit -a Lucas -m teste numero-id debian/minha_imagem:1.0</td>
    <td>Cria uma imagem a partir de um container.</td>
  </tr>
</table>
