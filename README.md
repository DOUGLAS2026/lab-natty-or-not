# PROJETO BOOTCAMP DOUGLAS TEODORO

## 📒 Descrição
Entradas e Saídas variáveis 

## 🤖 Tecnologias Utilizadas
Plataforma DIO

## 🧐 Processo de Criação
# Recebe a Entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber uma área de aplicação e retornar sua respectiva descrição.
def descrever_aplicacao(area):
    if area == "saúde":
        return "diagnóstico precoce e tratamento personalizado"
        
    # COMPLETE AQUI: Preencha corretamente cada área de aplicação, considerando as descrições abaixo:        
    elif area == "segurança":
        return "monitoramento e prevenção de crimes"
        
    elif area == "transporte":
        return "veículos autônomos e otimização de rotas"
                            
    elif area == "educação":
        return "personalização do aprendizado e tutoria inteligente"
        
# Imprime a descrição da aplicação na área recebido na "entrada" através da função "descrever_aplicacao". 
print(descrever_aplicacao(entrada))

## 🚀 Resultados
Porjeto com entradas e saídas validas, e assim com confirmação de verificado!

## 💭 Reflexão (Opcional)
Pense, tudo que foi de nova tecnologia no passado, hoje pode ser dita como tecnologia do futuro, melhorada, e mais inteligente
