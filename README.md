# Install-HL1202-on-OpenSUSE
English:
Step by step tutorial for installation of Brother HL-1202 on OpenSuse. Will work for other models of the same manufacturer with the necessary changes on step 5:


Step 1: Try going directly to Brotherś installation tool page at https://support.brother.com/g/b/faqend.aspx?c=us&lang=en&prod=hll2300d_us_eu_as&faqid=faq00100556_000  If it doesn´t work, search for 
'To install the printer driver easily using a tool. (Linux)' on google. The first link should take you to the instructions page.
Step 2: The instructions page will offer you a link for the download of the tool. click to download it. In the download page choose 'Linux' and 'Linux(RPM).
Step 3: Extract the content to some folder you choose.
Step 4: Open the terminal and proceed to the folder where you have extracted your files. 
Step 5: type the command: sudo bash linux-brprinter-installer-2.2.3-1 (version number) HL-1202(or other model)
Step 6: Since you have used the sudo, you will be prompted to insert your root password
Step 7: Accept the EULA with 'y';
Step 8: If you will use the printer on a network, choose 'y' for adding the URI when prompted. If your printer will be on a USB connection, choose 'n'.

This should do it. In the end You will be prompted to print a test page.

Português:
Tutorial passo a passo para instalar  uma impressora HL-1202 no OpenSuse. Funciona para outros modelos da Brother, desde que feitos os ajustes necessários no passo 5:

Passo 1: Tente ir direto para a página de download da ferramenta da Brother em https://support.brother.com/g/b/faqend.aspx?c=us&lang=en&prod=hll2300d_us_eu_as&faqid=faq00100556_000   Se não funcionar, busque a frase 'To install the printer driver easily using a tool. (Linux)' no google. O primeiro link deve te levar para o lugar certo;
Passo 2: Na página de instruções, deve ter um link logo no começo escrito 'click here to download the tool'. Clique nele para fazer o download. Na página seguinte, escolha 'Linux' e Linux(RPM).
Passo 3: Extraia o conteúdo baixado para uma pasta. É uma boa criar uma pasta só para isso.
Passo 4: Abra o terminal e prossiga até a pasta em que você extraiu os arquivos.
Passo 5: Digite o comando sudo bash linux-brprinter-installer-2.2.3-1 (número da versão do arquivo) HL-1202(ou outro nome de modelo de impressora).
Passo 6: Por ter usado o comando sudo, você terá que fornecer sua senha de root;
Passo 7: Aceite o EULA (Contrato de usuário) com y.
Passo 8: Quando perguntar se você vai fornecer a URI, escolha 'y' se você for usar uma impressora em rede ou 'n' se for usar USB.

Isso deve ser o suficiente. Por fim, deve surgir a opção de imprimir uma página de teste. Escolha 'y' para sim ou 'n' para não.
