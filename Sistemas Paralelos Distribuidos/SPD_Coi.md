# Sistemas Paralelos e Distribuídos

# Professor Ricardo Rios

rrios@uea.edu.br - AVA:

4APs - Apresentação individual, sistema funcional, código e relatório/artigo

Exercícios garantem até 2pts extras em APs

**Grupo: Eu, Luã e Francisco**

## Sistema IoT (Internet of Things)

Controle de cortinas, lâmpadas, sorround system, televisão…

Jarvis adapta o conteúdo (um filme) e ao detectar a presença de uma criança, omite cenas com conteúdo inapropriado, ou mostra apenas os highlights de um jogo do Brasil ao mesmo tempo que direciona propagandas para os celulares de cada pessoa identificada na sala, propagandas customizadas para o interesse de cada um

## SPO Layer

Smart Physical Object Layer, camada de software do sensor/atuador

sensor (temperatura, presença…)

atuador (caixa de som, lâmpada…)

---
### **Camadas:**

Acquisition Layer\
Wrapper\
SPO Layer

*O Wrapper (um proxy) uniformiza a comunicação com os diferentes SPOs, o da google, amazon e etc…*

---

## Sistema Distribuídos

Sistemas Distribuídos tem os componentes localizados em uma rede de computadores e se comunicam e coordenam ações através da troca de mensagens

- Concorrência de componentes
    - Gerenciar recursos compartilhados, como adição de recursos à rede
- Ausência de Relógio Global
    - Cooperação entre programas através da troca de mensagens com uma ideia compartilhada de tempo
- Falhas Independentes dos Componentes
    - Isolamento dos computadores, um computador pode estar isolado, mas não quer dizer que ele não está funcionando

## Recursos

Recursos podem ser Hardware, Software ou dados (áudio, vídeo, texto…)

Recursos são coisas compartilhadas entre sistemas