📌 Assistente de Voz para Controle do PC
1. Visão Geral

O Assistente de Voz para Controle do PC é um sistema desenvolvido em Python que permite ao usuário executar comandos no computador através de voz.

O sistema captura o áudio do microfone, converte em texto, interpreta o comando e executa ações no sistema operacional Windows.

O objetivo é criar um assistente local, leve e extensível, com arquitetura modular e organizada.

2. Objetivo do Projeto

Automatizar tarefas no computador através de comandos de voz

Demonstrar integração com o sistema operacional

Aplicar conceitos de arquitetura em camadas

Desenvolver um projeto organizado e escalável

Criar um diferencial para portfólio

3. Escopo do Sistema
3.1 Funcionalidades Iniciais

Capturar áudio do microfone

Converter fala para texto

Reconhecer comandos pré-definidos

Abrir programas

Criar arquivos

Desligar ou reiniciar o computador

Automatizar ações simples com teclado/mouse

3.2 Funcionalidades Futuras

Integração com API de IA (OpenAI)

Sistema de aprendizado de comandos personalizados

Interface gráfica (GUI)

Histórico de comandos executados

Sistema de permissões e segurança

4. Arquitetura do Sistema

O sistema será dividido em camadas:

4.1 Camada de Captura de Voz

Responsável por capturar o áudio do microfone.
Tecnologia: PyAudio

4.2 Camada de Reconhecimento de Fala

Responsável por converter áudio em texto.
Tecnologia: SpeechRecognition

4.3 Camada de Processamento de Comandos

Interpreta o texto reconhecido e identifica qual ação deve ser executada.

Estrutura inicial: if/else

Evolução futura: mapeamento por dicionário ou NLP

4.4 Camada de Execução de Ações

Executa comandos no sistema operacional.

Tecnologias:

os

subprocess

PyAutoGUI

4.5 Camada Opcional de Inteligência Artificial

Integração com API externa para interpretar comandos mais complexos.

Tecnologia opcional:

OpenAI API

5. Requisitos do Sistema
5.1 Requisitos Funcionais

O sistema deve capturar áudio do microfone

O sistema deve converter fala para texto

O sistema deve reconhecer comandos pré-definidos

O sistema deve executar ações no Windows

5.2 Requisitos Não Funcionais

O sistema deve ser modular

O sistema deve permitir fácil expansão

O sistema deve rodar localmente

O sistema deve ter organização profissional de código

6. Fluxo de Execução do Sistema

Sistema inicia

Microfone é ativado

Usuário fala o comando

Áudio é convertido em texto

Texto é processado

Comando correspondente é executado

Sistema retorna confirmação

7. Tecnologias Utilizadas

Python 3.x

SpeechRecognition

PyAudio

PyAutoGUI

os / subprocess

(Opcional) OpenAI API
