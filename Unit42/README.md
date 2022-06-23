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

Mespinoza-ransomware (https://unit42.paloaltonetworks.com/atoms/mespinoza-ransomware/)
-------
Mespinoza, un grupo prolífico también conocido como PYSA, que nuestro grupo consultor de seguridad cibernética Unit 42 ha observado ataques en los EE. UU. contra organizaciones editoriales, inmobiliarias, de fabricación industrial y educativas. El FBI publicó recientemente una alerta sobre el grupo luego de una ola de piratería en escuelas K-12, colegios, universidades e incluso seminarios en los Estados Unidos, así como en el Reino Unido.

Para obtener más información sobre este grupo, monitoreamos su infraestructura, incluido un servidor de comando y control (C2) que usa para administrar ataques y un sitio de fugas donde publica datos de víctimas que se negaron a pagar grandes rescates. Estos son algunos hallazgos clave:

Mespinoza es extremadamente disciplinado. Después de acceder a una nueva red, los analistas del grupo estudian los sistemas comprometidos en lo que creemos que es una clasificación para determinar si hay suficientes datos valiosos para justificar el lanzamiento de un ataque a gran escala. Buscan palabras clave como "secreto" y "fraude", lo que sugiere que están buscando archivos confidenciales que tendrían el mayor impacto si se filtraran.

Está publicando datos sobre muchas víctimas. El sitio de filtración de la pandilla proporcionó datos que, según afirma, pertenecen a 147 organizaciones de víctimas, a las que se refiere como "socios". El uso de ese término sugiere que tratan de dirigir el grupo como una empresa profesional y ven a las víctimas como socios comerciales que financian sus ganancias.

Está recibiendo mucho dinero. Nuestros consultores han observado demandas de rescate de hasta 1,6 millones de dólares y pagos de hasta 470.000 dólares.

Indicadores de Compromiso
- Domains (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/Domains/Mespinoza-ransomware)
- IPs (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/IPs/Mespinoza-ransomware)

Maze-ransomware (https://unit42.paloaltonetworks.com/atoms/maze-ransomware/)
-------
Maze es un ransomware que se descubrió en mayo de 2019 cuando Fallout Exploit Kit lo dejó caer en ese momento. Lo único que hizo que este ransomware fuera diferente es que detectaría el tipo de computadora que comprometió y establecería el rescate en consecuencia. Los rescates más altos se reservarían para los tipos de servidores de víctimas. Los operadores detrás de Maze Ransomware son los pioneros de la doble exorción de sus víctimas. Amenazan a sus víctimas con usar información confidencial para realizar campañas maliciosas y divulgar información confidencial al público si no se paga el rescate. Para probar su punto, los operadores detrás del ransomware Maze tienen un sitio dedicado donde enumeran las identidades de las víctimas y muestras de datos de aquellas que no cumplieron con sus demandas.

Indicadores de Compromiso
- Domains (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/Domains/Maze-ransomware)
- IPs (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/IPs/Maze-ransomware)
- URLs (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/URLs/Maze-ransomware)

Pickaxe (https://unit42.paloaltonetworks.com/atoms/pickaxe/)
-------
PickAxe es un actor de amenazas activo desde al menos agosto de 2017 y continúa activo hasta el día de hoy. El objetivo del adversario es instalar y mantener un popular minero de criptomonedas en la máquina de la víctima. El minero en cuestión es una herramienta de código abierto llamada XMRig que genera la criptomoneda Monero. El malware se entrega a través de descargas a través de la popular plataforma de publicidad Adfly. Los usuarios a menudo son engañados al hacer clic en un anuncio malicioso que hace que la carga útil se entregue a la víctima. Una vez instalado, el malware aprovecha los scripts VBS y los servicios de redirección, como bitly, para finalmente descargar y ejecutar XMRig. Se ha descubierto que más de 15 millones de víctimas confirmadas están infectadas en campañas recientes, y es probable que las cifras reales oscilen entre 30 y 45 millones de víctimas. Las víctimas se encuentran en todo el mundo.

Indicadores de Compromiso
- Domains (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/Domains/Pickaxe)
- IPs (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/IPs/Pickaxe)

Zero-day-microsoft-exchange-vulnerabilities (https://unit42.paloaltonetworks.com/atoms/zero-day-microsoft-exchange-vulnerabilities/)
-------
El 2 de marzo de 2021, Volexity informó sobre la explotación en estado salvaje de varias vulnerabilidades de Microsoft Exchange: CVE-2021-26855, CVE-2021-26857, CVE-2021-26858 y CVE-2021-27065.
Como resultado de la explotación de estas vulnerabilidades, los adversarios pueden acceder a los servidores de Exchange y permitir la instalación de herramientas adicionales para facilitar el acceso a largo plazo a los entornos de las víctimas. Múltiples grupos han utilizado el método de explotación inicial, lo que significa que la actividad posterior a la explotación puede variar.
Estas vulnerabilidades afectan a las versiones de los servidores de Microsoft Exchange: Microsoft Exchange 2013, 2016, 2019
Microsoft ha publicado una actualización de seguridad de emergencia para corregir estas vulnerabilidades. Recomendamos enfáticamente actualizar todos los servidores de Microsoft Exchange a la última actualización disponible de Microsoft inmediatamente.

Indicadores de Compromiso
- IPs (https://github.com/olivaresfabrizi/Security/blob/main/Unit42/IPs/Zero-day-microsoft-exchange-vulnerabilities)
