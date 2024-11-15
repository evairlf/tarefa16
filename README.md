## Atividade 16 - Praticando Testes Unitários

## cessando o Console H2

- Para acessar o console do H2:

        Abra o navegador e vá para http://localhost:8080/h2-console.
        Configure o campo "JDBC URL" como jdbc:h2:mem:testdb, com o username sa e deixe o password em branco.
        Clique em "Connect" para visualizar o banco de dados.

- Rodar os Testes
    Agora, você pode rodar os testes de várias maneiras.

        Rodar Testes Específicos
         Abra a classe de teste que você deseja rodar.
        No topo da classe de teste, clique no ícone de execução (um play verde) ao lado do nome da classe ou do método de teste específico.
        O IntelliJ irá compilar e executar os testes, exibindo os resultados na janela de Run.
        Rodar Todos os Testes

- Como rodar pelo terminal

        copie e cole este comando se voce tiver maven
                
                mvn test