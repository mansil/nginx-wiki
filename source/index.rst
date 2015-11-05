
.. meta::
   :description: This is the NGINX Wiki. NGINX is a free, open-source, high-performance HTTP server, reverse proxy, and IMAP/POP3 proxy server.

Bem-vindo à documentação da Wiki do NGINX!
======================================

NGINX é um servidor HTTP de alto desempenho e um proxy invertido gratuito e de código aberto,
bem como um servidor proxy IMAP/POP3. NGINX é conhecido pelo seu alto desempenho,
estabilidade, conjunto de funções valiosas, configuração simples, e consumo reduzido de recursos.

NGINX é uma da mão cheia de servidores criados para endereçar o problema de `C10K <http://www.kegel.com/c10k.html>`_. Ao contrário dos servidores tradicionais, o NGINX não conta com sequências para manipular os pedidos.
Em vez disso, este utiliza uma arquitetura (assíncrona) muito mais escalável evento-direcionada.
Esta arquitetura utiliza pequenas, mas mais importe, quantidades predizíveis de memória sob carga. 
Mesmo que não espere manipular milhares de pedidos simultâneos, ainda pode beneficiar do alto desempenho do NGINX e pequenas áreas memória ocupada.
O NGINX escala em todas as direções: desde VPS mais pequenos até grandes conglomerados de servidores.

NGINX alimenta vários sites de alta visibilidade, tais como `Netflix <https://www.netflix.com/>`_, `Hulu <http://www.hulu.com/>`_, `Pinterest <https://www.pinterest.com/>`_, `CloudFlare <https://www.cloudflare.com/>`_, `Airbnb <https://www.airbnb.com/>`_, `WordPress.com <https://wordpress.com/>`_, `GitHub <https://github.com/>`_, `SoundCloud <https://soundcloud.com/>`_, `Zynga <https://www.zynga.com/>`_, `Eventbrite <https://eventbrite.com/>`_, `Zappos <http://www.zappos.com/>`_, `Media Temple <https://mediatemple.net/>`_, `Heroku <https://www.heroku.com/>`_, `RightScale <http://www.rightscale.com/>`_, `Engine Yard <https://www.engineyard.com/>`_, `MaxCDN <https://maxcdn.com/>`_ e muitos outros.

.. _introtable:

+----------------+------------------+---------------+----------------+
| |startedicon|_ | |communityicon|_ | |moduleicon|_ | |contribicon|_ |
+----------------+------------------+---------------+----------------+
| |startedtext|_ | |communitytext|_ | |moduletext|_ | |contribtext|_ |
+----------------+------------------+---------------+----------------+

.. toctree::
   :hidden:

   start/index
   community/index
   modules/index
   contributing/index
   nginScript

.. |moduleicon| replace:: :icon:`puzzle-piece`
.. _moduleicon: modules/index.html

.. |moduletext| replace:: 3\ :sup:`rd` Party Modules
.. _moduletext: modules/index.html

.. |communityicon| replace:: :icon:`users`
.. _communityicon: community/index.html

.. |communitytext| replace:: Community
.. _communitytext: community/index.html

.. |startedicon| replace:: :icon:`play`
.. _startedicon: start/index.html

.. |startedtext| replace:: Getting Started
.. _startedtext: start/index.html

.. |contribicon| replace:: :icon:`wrench`
.. _contribicon: contributing/index.html

.. |contribtext| replace:: Contributing
.. _contribtext: contributing/index.html
