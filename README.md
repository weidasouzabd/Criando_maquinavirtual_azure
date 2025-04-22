README
# Criando_maquinavirtual_azure
Laboratório da DIO curso - XP Inc. - Cloud com Inteligência Artificial
📚 Introdução
Este guia fornece instruções detalhadas para criar uma máquina virtual (VM) no Microsoft Azure. As máquinas virtuais do Azure oferecem infraestrutura computacional sob demanda com controle completo sobre o ambiente de computação.

🔑 Pré-requisitos
Conta ativa no Microsoft Azure
Acesso ao portal.azure.com

🚀 Passo a Passo
1. Acessar o Portal do Azure
Abra seu navegador e acesse 
portal.azure.com
Faça login com suas credenciais da Microsoft

2. Criar uma Nova Máquina Virtual
No Portal do Azure, clique em "Criar um recurso" no canto superior esquerdo
Na barra de pesquisa, digite "Máquina Virtual" e selecione a opção correspondente
Clique no botão "Criar" para iniciar o processo de configuração

3. Configurações Básicas
Assinatura: Selecione sua assinatura do Azure
Grupo de recursos:DIO
Nome da máquina virtual: AzureAprendiz
Região: (South America) Brasil South
Opções de disponibilidade: Zona Auto Selecionada - Zona 1
Tipo de segurança: Computadores virtuais de Inicialização confiável
Imagem: Windows 11 Pro, version 24H2 - X64 Gen2
Tamanho: Standard _B1s - 1 VCPU 1 GB de memória
Clique em "Próximo: Discos"
4. Configurações de Disco
Tipo de disco do SO:  SSD Standard 
Opções avançadas: Configure as opções de criptografia, se necessário
Clique em "Próximo: Rede"
5. Configurações de Rede
Rede virtual: AzureAprendiz-Vnet
Sub-rede: (novo) - default(10.0.0.0/24)
IP público: AzureAprendiz-ip
Grupo de segurança de rede: Basico
Portas de entrada: permitir todas selecionadas
Marque a opção Excluir o IP público e a NIC quando a VM for excluída
Clique em "Próximo: Gerenciamento"
7. Configurações de Gerenciamento
Microsoft Defender
Habilitar plano básico gratuitamente
Desligamento automático:19:00 horario de brasilia
8. Revisão e Criação
Revise todas as configurações para garantir que estão corretas
Clique em "Criar" para iniciar a implantação da VM
Aguarde a conclusão da implantação (pode levar alguns minutos)

    
