![valid XHTML][checkmark]
[checkmark]: https://raw.githubusercontent.com/mozgbrasil/mozgbrasil.github.io/master/assets/images/logos/Red_star_32_32.png "MOZG"
[url-method]: http://www.braspag.com.br/
[requirements]: http://mozgbrasil.github.io/requirements/
[uninstall-mods]: http://devdocs.magento.com/guides/v1.0/install-gde/install/install-cli-uninstall-mods.html
[contact-braspag]: http://suporte.braspag.com.br/
[tickets]: https://cerebrum.freshdesk.com/support/tickets/new
[preco]: http://www.cerebrum.com.br/preco/

# Mozg\Braspag

## Sinopse

Integração a [Braspag][url-method]

## Motivação

Atender o mercado de módulos para Magento oferecendo melhorias e um excelente suporte

## Suporte / Dúvidas

Para obter o devido suporte [Clique aqui][tickets], relatando o motivo da ocorrência o mais detalhado possível e anexe o print da tela para nosso entendimento

## Preço

[Clique aqui][preco]

## Recursos

- Non Non

## Característica técnica

Non Non

## Instalação - Atualização - Desinstalação

Este módulo destina-se a ser instalado usando o composer.

Antes de executar os processos, [clique aqui][requirements] e leia os pré-requisitos e sugestões

--

Para instalar o módulo execute o comando a seguir no terminal do seu servidor

	composer require mozgbrasil/magento2-braspag-php56 -vvv && php bin/magento setup:upgrade

Você pode verificar se o módulo está instalado, indo ao backend em:

	STORES -> Configuration -> ADVANCED/Advanced -> Disable Modules Output

--

Para atualizar o módulo execute o comando a seguir no terminal do seu servidor

	composer --version && sudo composer self-update && composer clear-cache && composer update -vvv && composer diagnose && composer show -i && php bin/magento setup:upgrade

--

Para [desinstalar][uninstall-mods] o módulo execute o comando a seguir no terminal do seu servidor

	bin/magento module:uninstall --remove-data --backup-code --backup-media --backup-db Mozg_Braspag

~~composer remove mozgbrasil/magento2-braspag-php56 && composer clear-cache && composer update && php bin/magento setup:upgrade~~

## Como configurar o método de entrega

Antes de configurar o módulo você deve cadastrar o CEP de origem, indo ao backend em:

	STORES -> Configuration -> Sales/Shipping Settings -> Origin

Para configurar o método de entrega, acesse no backend em:

	STORES -> Configuration -> Sales/Shipping Methods -> Braspag (powered by MOZG)

Você terá os campos a seguir

- **Ativar**

Para "ativar" ou "desativar" o uso do método

- **Ordem de exibição**

É a ordem apresentada em métodos de entrega no passo de fechamento de pedido

- **Título**

Nome do método que deve ser exibido

- **Serviços**

Selecione os serviços desejado, para selecionar mais de um, segure a tecla "Ctrl" e clique nos serviços



## Quais os recursos do módulo

- [✓] Cálculo do frete
- [✓] Rastreamento

## Perguntas mais frequentes "FAQ"

### Non Non

Non Non

### Dados de contato - Braspag

implantacao.operacoes@braspag.com.br

Rodrigo Santos
rsantos@braspag.com.br
(11) 3320-9050 - Ramal 5

Rodolfo de Lucena
rmoreira@braspag.com.br
(11) 3320-9058

ou acesse

Para entrar em contato com a [Braspag][contact-braspag]

## Manual

http://www.braspag.com.br/suporte/desenvolvedores/

## Contribuintes

Equipe Mozg

## License

[Comercial License] (LICENSE.txt)

## Badges

[![Join the chat at https://gitter.im/mozgbrasil](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/mozgbrasil/)
[![Latest Stable Version](https://poser.pugx.org/mozgbrasil/magento2-braspag-php56/v/stable)](https://packagist.org/packages/mozgbrasil/magento2-braspag-php56)
[![Total Downloads](https://poser.pugx.org/mozgbrasil/magento2-braspag-php56/downloads)](https://packagist.org/packages/mozgbrasil/magento2-braspag-php56)
[![Latest Unstable Version](https://poser.pugx.org/mozgbrasil/magento2-braspag-php56/v/unstable)](https://packagist.org/packages/mozgbrasil/magento2-braspag-php56)
[![License](https://poser.pugx.org/mozgbrasil/magento2-braspag-php56/license)](https://packagist.org/packages/mozgbrasil/magento2-braspag-php56)
[![Monthly Downloads](https://poser.pugx.org/mozgbrasil/magento2-braspag-php56/d/monthly)](https://packagist.org/packages/mozgbrasil/magento2-braspag-php56)
[![Daily Downloads](https://poser.pugx.org/mozgbrasil/magento2-braspag-php56/d/daily)](https://packagist.org/packages/mozgbrasil/magento2-braspag-php56)

:cat2:
