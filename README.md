Resumo:

Foram executados testes automatizados utilizando o framework Cucumber para testar diferentes funcionalidades do site Starbugs. 

Funcionalidade de Catálogo de Cafés:
Foram definidos cenários de teste para verificar o acesso ao catálogo de cafés na página principal.
Cenários foram criados para iniciar a compra de diferentes tipos de café e verificar se o usuário é redirecionado para a página de checkout ou se recebe um aviso caso o produto esteja indisponível.

Funcionalidade de Uso de Cupons no Checkout:
Cenários foram escritos para testar a aplicação de cupons de desconto durante o checkout.
Testes incluem casos de sucesso, cupom expirado e cupom inválido.

Funcionalidade de Pedidos:
Foram definidos cenários para testar a realização de um pedido bem-sucedido no site.
Os testes verificam se o usuário consegue navegar até a página de confirmação de pedidos e se o prazo de entrega é informado corretamente.

Ferramentas Utilizadas:
Cucumber: Framework de teste BDD usado para escrever e executar testes automatizados em linguagem natural.
Selenium: Ferramenta utilizada para automatizar a interação com navegadores web.
Geckodriver: Um dos componentes do Selenium, usado para controlar o navegador Firefox.
Capybara: Biblioteca em Ruby usada para simular interações de usuário em aplicativos web.
Ruby: Linguagem de programação utilizada para escrever os passos de teste e interagir com o Selenium, Capybara e outros componentes do sistema.
Os testes foram executados com sucesso, totalizando 7 cenários e 30 passos, sem falhas. O tempo total de execução foi de aproximadamente 16.108 segundos.
