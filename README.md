# Modulokernel

Trabalho acadêmico para conclusão de nota da matéria de Sistemas Operacionais.

## Instalação

Siga as etapas abaixo para instalar e executar o projeto em seu ambiente.

1. Instale as dependências necessárias:<strong>sudo apt-get install build-essential linux-headers-$(uname -r)</strong>
2. Compile o projeto: <strong>make</strong>
3. Carregue o módulo do kernel: <strong>sudo insmod procFs.ko</strong>
4. Verifique o log do sistema para ver a mensagem de sucesso:<strong>dmesg</strong>



