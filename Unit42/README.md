# Unid 42 - Palo Alto Networks (https://unit42.paloaltonetworks.com/about-unit-42/)
Lista de Indicadres de Compromiso (IPs, Dominios, URLs o Hash) de amenazas o ataques encontrados por Unid 42 de Palo Alto Networks

Gallium (https://unit42.paloaltonetworks.com/atoms/gallium/)
-------
La Unidad 42 monitorea activamente la infraestructura asociada con varios grupos APT. Un grupo en particular, [GALLIUM](https://attack.mitre.org/groups/G0093/) (también conocido como Operation Soft Cell), estableció su reputación al apuntar a empresas de telecomunicaciones que operan en el sudeste asiático, Europa y África. La orientación geográfica del grupo, el enfoque específico del sector y la competencia técnica, combinados con su uso de malware y tácticas, técnicas y procedimientos (TTP) de actores de amenazas chinos conocidos, han dado como resultado [evaluaciones] de la industria (https://www.cybereason.com/blog/research/operation-soft-cell-a-worldwide-campaign-against-telecommunications-providers) que GALLIUM es probablemente un grupo patrocinado por el estado chino.

Comportamiento:
https://unit42.paloaltonetworks.com/pingpull-gallium/

Indicadores de Compromiso
- Domains (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/Domains/Gallium)
- IPs (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/IPs/Gallium)

Lockbit-2.0-ransomware	(https://unit42.paloaltonetworks.com/atoms/lockbit-2.0-ransomware/)
-------
LockBit 2.0 (anteriormente conocido como ABCD ransomware) es un ransomware como servicio (RaaS) de tres años que se ha relacionado con varios ataques de alto perfil. Aprovecha las campañas de marketing para reclutar nuevos afiliados y afirma ofrecer el cifrado más rápido en el mercado de ransomware.

Indicadores de Compromiso
- Domains (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/Domains/Lockbit-2.0-ransomware)

Maze-ransomware
-------
Maze es un ransomware que se descubrió en mayo de 2019 cuando Fallout Exploit Kit lo dejó caer en ese momento. Lo único que hizo que este ransomware fuera diferente es que detectaría el tipo de computadora que comprometió y establecería el rescate en consecuencia. Los rescates más altos se reservarían para los tipos de servidores de víctimas. Los operadores detrás de Maze Ransomware son los pioneros de la doble exorción de sus víctimas. Amenazan a sus víctimas con usar información confidencial para realizar campañas maliciosas y divulgar información confidencial al público si no se paga el rescate. Para probar su punto, los operadores detrás del ransomware Maze tienen un sitio dedicado donde enumeran las identidades de las víctimas y muestras de datos de aquellas que no cumplieron con sus demandas.

Indicadores de Compromiso
- Domains (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/Domains/Maze-ransomware)
- IPs (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/IPs/Maze-ransomware)

Pickaxe (https://unit42.paloaltonetworks.com/atoms/pickaxe/)
-------
PickAxe es un actor de amenazas activo desde al menos agosto de 2017 y continúa activo hasta el día de hoy. El objetivo del adversario es instalar y mantener un popular minero de criptomonedas en la máquina de la víctima. El minero en cuestión es una herramienta de código abierto llamada XMRig que genera la criptomoneda Monero. El malware se entrega a través de descargas a través de la popular plataforma de publicidad Adfly. Los usuarios a menudo son engañados al hacer clic en un anuncio malicioso que hace que la carga útil se entregue a la víctima. Una vez instalado, el malware aprovecha los scripts VBS y los servicios de redirección, como bitly, para finalmente descargar y ejecutar XMRig. Se ha descubierto que más de 15 millones de víctimas confirmadas están infectadas en campañas recientes, y es probable que las cifras reales oscilen entre 30 y 45 millones de víctimas. Las víctimas se encuentran en todo el mundo.

Indicadores de Compromiso
- Domains (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/Domains/Pickaxe)
