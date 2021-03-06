# Parte 1 - Docker: criando e gerenciando containers

- [x] 1. Conhecendo o Docker
  - [x] 1.1 Apresentação
  - [x] 1.2 Conhecendo o problema
  - [x] 1.3 Conflitos e versionamento
  - [x] 1.4 Como containers funcionam
  - [x] 1.5 Containers por baixo dos panos
  - [x] 1.6 Instalando o Docker no Windows
  - [x] 1.7 Preparando o ambiente: Windows
  - [x] 1.8 Instalando o Docker no Linux
  - [x] 1.9 Preparando o ambiente: Linux
- [x] 2. Os primeiros comandos
  - [x] 2.1 Conhecendo o Docker Hub
  - [x] 2.2 O comando docker run
  - [x] 2.3 Fluxo da criação de containers
  - [x] 2.4 Etapas do run
  - [x] 2.5 Outros comandos importantes
  - [x] 2.6 Run vs Exec
  - [x] 2.7 Mapeando portas
  - [x] 2.8 Visualizando mapeamentos
  - [x] 2.9 Faça como eu fiz: Acessando portas externamente
- [x] 3. Criando e compreendendo imagens
  - [x] 3.1 Entendendo imagens
  - [x] 3.2 Detalhes sobre imagens
  - [x] 3.3 Criando a primeira imagem
  - [x] 3.4 Instruções no Dockerfile
  - [x] 3.5 Faça como eu fiz: Construindo uma imagem
  - [x] 3.6 Incrementando a imagem
  - [x] 3.7 ARG vs ENV
  - [x] 3.8 Subindo a imagem para o Docker Hub
- [x] 4. Persistindo dados
  - [x] 4.1 O problema de persistir dados
  - [x] 4.2 Tipos de persistência
  - [x] 4.3 Utilizando bind mounts
  - [x] 4.4 Criando um bind
  - [x] 4.5 Utilizando volumes
  - [x] 4.6 Vantagens de volumes
  - [x] 4.7 Faça como eu fiz: Criando um volume
  - [x] 4.8 Utilizando tmpfs
- [x] 5. Comunicação através de redes
  - [x] 5.1 Conhecendo a rede bridge
  - [x] 5.2 Redes do Docker
  - [x] 5.3 Criando uma rede bridge
  - [x] 5.4 As redes none e host
  - [x] 5.5 Host vs None
  - [x] 5.6 Comunicando aplicação e banco
  - [x] 5.7 Faça como eu fiz: Comunicação de containers
- [x] 6. Coordenando containers
  - [x] 6.1 Conhecendo o Docker Compose
  - [x] 6.2 Utilização do Docker Compose
  - [x] 6.3 Definindo os serviços
  - [x] 6.4 Parâmetros para serviços
  - [x] 6.5 Faça como eu fiz: Coordenando containers
  - [x] 6.6 Complementando o Compose

# Parte 2 - Docker Swarm: Orquestrador de containers

- [x] 7. Cluster com Docker Swarm Ver primeiro vídeo
  - [x] 7.1 Introdução
  - [x] 7.2 Ambiente e versões
  - [x] 7.3 Preparando o ambiente
  - [x] 7.4 Revisão Docker
  - [x] 7.5 O que é Docker Swarm?
  - [x] 7.6 Benefícios do Swarm
  - [x] 7.7 Usando a Docker Machine
  - [x] 7.8 Papel da Docker Machine
  - [x] 7.9 Para saber mais: Cloud e Docker Machine
  - [x] 7.10 Criando o cluster
  - [x] 7.11 Comando para criar clusters
  - [x] 7.12 Consolidando o seu conhecimento
- [x] 8. Responsabilidade dos nós workers
  - [x] 8.1 Criando o primeiro worker
  - [x] 8.2 Nós workers
  - [x] 8.3 Listando e removendo nós
  - [x] 8.4 Restrição de comandos
  - [x] 8.5 Subindo um serviço
  - [x] 8.6 docker service vs docker run
  - [x] 8.7 Tarefas e o Routing Mesh
  - [x] 8.8 Acessando serviços
  - [x] 8.9 Consolidando o seu conhecimento
- [x] 9. Gerenciando o cluster com managers
  - [x] 9.1 O papel do manager
  - [x] 9.2 Desastres no Swarm
  - [x] 9.3 Como fazer backup do Swarm
  - [x] 9.4 Caminho do backup
  - [x] 9.5 Criando mais managers
  - [x] 9.6 Identificando managers
  - [x] 9.7 Algoritmo de consenso RAFT
  - [x] 9.8 Exigências do RAFT
  - [x] 9.9 Consolidando o seu conhecimento
- [x] 10. Separando as responsabilidades
  - [x] 10.1 Readicionando um manager
  - [x] 10.2 Removendo managers
  - [x] 10.3 Restringindo nós
  - [x] 10.4 Atualizando nós
  - [x] 10.5 Restringindo serviços
  - [x] 10.6 Aplicando constraints
  - [x] 10.7 Para saber mais: Outras restrições
  - [x] 10.8 Consolidando o seu conhecimento
- [x] 11. Serviços globais e replicados
  - [x] 11.1 Serviços replicados
  - [x] 11.2 Nós e serviços replicados
  - [x] 11.3 Para saber mais: service scale
  - [x] 11.4 Serviços globais
  - [x] 11.5 Por que global?
  - [x] 11.6 Consolidando o seu conhecimento
- [x] 12. Driver Overlay
  - [x] 12.1 A rede ingress
  - [x] 12.2 O papel da rede ingress
  - [x] 12.3 Service Discovery
  - [x] 12.4 Limitações da rede ingress
  - [x] 12.5 User-Defined Overlay
  - [x] 12.6 Redes customizadas
  - [x] 12.7 Para saber mais: Containers e Overlay
  - [x] 12.8 Consolidando o seu conhecimento
- [x] 13. Deploy com Docker Stack
  - [x] 13.1 Lembrando do Docker Compose
  - [x] 13.2 Definindo o arquivo de composição
  - [x] 13.3 Analisando o yml
  - [x] 13.4 Subindo a stack
  - [x] 13.5 docker stack deploy
  - [x] 13.6 Para saber mais: Volumes no Swarm
  - [x] 13.7 Consolidando o seu conhecimento
- [x] 14. Conclusão

