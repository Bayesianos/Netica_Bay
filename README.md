# Netica - funcionamento
![image](https://github.com/user-attachments/assets/98873343-89e2-466a-baef-09af2ad813eb)

## Índice
- [Sobre o NETICA](#sobre-o-netica)
- [Lógica](#funcionalidades)
- [Instalação e Execução](#instalação-e-execução)
- [Slides](#endpoints)
- [Vídeo no YouTube](#tecnologias-utilizadas)

## Sobre o netica
Para o entendimento da lógica e maior entendimento do projeto, foi utilizado o programa "NETICA" que consiste em um software de análise de redes bayesianas.

## Lógica
- Cada nodo corresponde a um único nodo pai chamado "Risco_final".
- Utiliza um levantamenti alemão de pedidos de empréstimo bancário. (link da pesquisa: https://www.kaggle.com/datasets/kabure/german-credit-data-with-risk).
- Retorna um status de elegibilidade para o empréstimo baseado na análise probabilística.
- Esses dados são baseados na lógica de Bayes onde cada filho influencia na decisão final.

### Instalação e execução
1: Abra o arquivo : " https://drive.google.com/file/d/1C1WVk9s_qxVkRWgegdbd9CE4fjwLM_Ix/view " e baixe-o
2: No disco C: haverá um arquivo nética e ele estará disponível para uso em sua versão limitada.

## Vídeo no YouTube
Segue em anexo o link do vídeo da explicação do conteúdo completa: 

Exemplo de payload de recebimento:
```json
{
  "emprestimo_valido": true
}

