# Unid 42 - Palo Alto Networks (https://unit42.paloaltonetworks.com/about-unit-42/)
Lista de Indicadres de Compromiso (IPs, Dominios, URLs o Hash) de amenazas o ataques encontradas por Unid 42 de Palo Alto Networks

Gallium (https://unit42.paloaltonetworks.com/atoms/gallium/)
-------
La Unidad 42 monitorea activamente la infraestructura asociada con varios grupos APT. Un grupo en particular, [GALLIUM](https://attack.mitre.org/groups/G0093/) (también conocido como Operation Soft Cell), estableció su reputación al apuntar a empresas de telecomunicaciones que operan en el sudeste asiático, Europa y África. La orientación geográfica del grupo, el enfoque específico del sector y la competencia técnica, combinados con su uso de malware y tácticas, técnicas y procedimientos (TTP) de actores de amenazas chinos conocidos, han dado como resultado [evaluaciones] de la industria (https://www.cybereason.com/blog/research/operation-soft-cell-a-worldwide-campaign-against-telecommunications-providers) que GALLIUM es probablemente un grupo patrocinado por el estado chino.

Comportamiento:
https://unit42.paloaltonetworks.com/pingpull-gallium/

Indicadores de Compromiso
- Domains (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/Domains/Gallium)
- IPs (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/IPs/Gallium)

Pickaxe (https://unit42.paloaltonetworks.com/atoms/pickaxe/)
-------
PickAxe es un actor de amenazas activo desde al menos agosto de 2017 y continúa activo hasta el día de hoy. El objetivo del adversario es instalar y mantener un popular minero de criptomonedas en la máquina de la víctima. El minero en cuestión es una herramienta de código abierto llamada XMRig que genera la criptomoneda Monero. El malware se entrega a través de descargas a través de la popular plataforma de publicidad Adfly. Los usuarios a menudo son engañados al hacer clic en un anuncio malicioso que hace que la carga útil se entregue a la víctima. Una vez instalado, el malware aprovecha los scripts VBS y los servicios de redirección, como bitly, para finalmente descargar y ejecutar XMRig. Se ha descubierto que más de 15 millones de víctimas confirmadas están infectadas en campañas recientes, y es probable que las cifras reales oscilen entre 30 y 45 millones de víctimas. Las víctimas se encuentran en todo el mundo.

Indicadores de Compromiso
- Domains (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/Domains/Pickaxe)
