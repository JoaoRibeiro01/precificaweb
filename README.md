
##PrecificaWeb - Projeto de Automação com Selenium - README

Objetivo:
O objetivo deste projeto é automatizar a busca de preços de produtos em dois sites diferentes, Buscapé e Google Shopping, filtrando produtos dentro de uma faixa de preço específica. Os resultados serão agregados em um DataFrame do Pandas e enviados por e-mail em formato HTML, simulando um relatório para uma empresa.

##Requisitos:

Python 3.x instalado no sistema.
Bibliotecas necessárias instaladas:
Selenium
Pandas
win32com.client (para envio de e-mails)
webdriver_manager (para gerenciamento de drivers do Selenium)

##Configuração:

Certifique-se de ter todas as bibliotecas mencionadas instaladas. Você pode instalá-las executando pip install nome_da_biblioteca.
Baixe o WebDriver correspondente ao seu navegador (por exemplo, ChromeDriver para o Google Chrome) e coloque-o no PATH do sistema ou especifique o caminho do driver no script.
Configure as credenciais do seu e-mail SMTP para enviar e-mails. Você pode configurar variáveis de ambiente para manter suas credenciais seguras.
Edite o arquivo config.py para ajustar os parâmetros como faixa de preço desejada, termos de busca e informações de e-mail.
Execução:

Execute o script main.py.
O script irá acessar os sites, buscar os produtos, filtrá-los e criar um DataFrame do Pandas com os resultados.
Em seguida, será gerado um e-mail com os resultados em formato HTML e enviado para o destinatário especificado no arquivo de configuração.

##Recomendações:

Certifique-se de não violar os Termos de Serviço dos sites ao automatizar as buscas.
Mantenha as configurações de e-mail seguras para evitar o acesso não autorizado à sua conta

