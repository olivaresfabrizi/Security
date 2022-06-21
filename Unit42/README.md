# Unid 42 - Palo Alto Networks
Lista de Indicadres de Compromiso (IPs, Dominios, URLs o Hash) de amenazas o ataques encontradas por Unid 42 de Palo Alto Networks

Pickaxe (https://unit42.paloaltonetworks.com/atoms/pickaxe/)
-------
PickAxe es un actor de amenazas activo desde al menos agosto de 2017 y continúa activo hasta el día de hoy. El objetivo del adversario es instalar y mantener un popular minero de criptomonedas en la máquina de la víctima. El minero en cuestión es una herramienta de código abierto llamada XMRig que genera la criptomoneda Monero. El malware se entrega a través de descargas a través de la popular plataforma de publicidad Adfly. Los usuarios a menudo son engañados al hacer clic en un anuncio malicioso que hace que la carga útil se entregue a la víctima. Una vez instalado, el malware aprovecha los scripts VBS y los servicios de redirección, como bitly, para finalmente descargar y ejecutar XMRig. Se ha descubierto que más de 15 millones de víctimas confirmadas están infectadas en campañas recientes, y es probable que las cifras reales oscilen entre 30 y 45 millones de víctimas. Las víctimas se encuentran en todo el mundo.

Indicadores de Compromiso
- IPs (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/Pickaxe)
