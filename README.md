# Caso práctico curso Analista de datos de Google realizado en R

Este código pertenece al curso Analista de datos de Google, está realizado en R, puede descargarse en archivo html: analisis_cuaderno.html o verse analisis_cuaderno.md en R Studio.

# Escenario

Eres un analista de datos júnior que trabaja en el equipo de analistas de marketing de **Bellabeat**, fabricante de productos de alta tecnología orientados a la salud de la mujer. Bellabeat es una empresa pequeña exitosa, pero tiene el potencial para convertirse en un actor más grande en el mercado global de dispositivos inteligentes. **Urška Sršen**, cofundadora y directora creativa de Bellabeat, cree que analizar los datos de actividad física de los dispositivos inteligentes podría desplegar nuevas oportunidades de negocio para la empresa. Te han pedido que te concentres en uno de los productos de Bellabeat y analices los datos de los dispositivos inteligentes para conocer el uso que hacen los consumidores de sus dispositivos inteligentes. Los hallazgos que descubras ayudarán a orientar la estrategia de marketing de la empresa. Presentarás tu análisis al equipo ejecutivo de Bellabeat junto con tus recomendaciones de alto nivel para la estrategia de marketing de Bellabeat.

## Personajes y productos

### Personajes

- **Urška Sršen**: Cofundadora y directora creativa de Bellabeat
- **Sando Mur**: Matemático y cofundador de Bellabeat, miembro clave del equipo ejecutivo de Bellabeat.
- **Equipo de análisis computacional de datos de marketing de Bellabeat**: Un equipo de analistas de datos que se encarga de recopilar, analizar e informar datos que ayudan a conducir la estrategia de marketing de Bellabeat. Te incorporaste a este equipo hace seis meses y te has dedicado a conocer la misión y las metas de negocios de Bellabeat, y a ver cómo puedes ayudar a la empresa a lograr estos objetivos desde tu lugar de analista de datos júnior.

### Productos

- **Aplicación Bellabeat**: La aplicación Bellabeat proporciona a los usuarios datos de salud relacionados con su actividad física, sueño, estrés, ciclo menstrual y hábitos de conciencia plena. Estos datos pueden ayudar a los usuarios a comprender sus hábitos actuales y adoptar decisiones saludables. La aplicación Bellabeat se conecta a su línea de productos de bienestar inteligentes.
- **Leaf**: Dispositivo de seguimiento clásico de bienestar de Bellabeat que se puede usar como pulsera, collar o clip. El dispositivo Leaf se conecta a la aplicación Bellabeat para hacer un seguimiento de la actividad física, el sueño y el estrés.
- **Time**: Este reloj de bienestar combina el aspecto intemporal de un reloj clásico con la tecnología inteligente para hacer el seguimiento de la actividad física, el sueño y el estrés del usuario. El reloj Time se conecta a la aplicación Bellabeat para proporcionar información sobre el bienestar diario.
- **Spring**: Es una botella de agua que hace el seguimiento diario del consumo de agua mediante el uso de tecnología inteligente para garantizar la hidratación adecuada a lo largo del día. La botella Spring se conecta a la aplicación Bellabeat para hacer el seguimiento de los niveles de hidratación.
- **Membresía de Bellabeat**: Bellabeat también ofrece a los usuarios un programa de membresía mediante suscripción. La membresía brinda a los usuarios un acceso 24/7 a una orientación totalmente personalizada sobre nutrición, actividad física, sueño, salud y belleza, y conciencia plena según el estilo de vida y las metas del usuario.

## Acerca de la empresa

**Urška Sršen** y **Sando Mur** fundaron Bellabeat, una empresa de alta tecnología que fabrica productos inteligentes focalizados en el cuidado de la salud. Sršen usó su experiencia como artista para desarrollar una tecnología con un bonito diseño que informará e inspirará a las mujeres de todo el mundo. Recopilar datos sobre la actividad física, el sueño, el estrés y la salud reproductiva le ha permitido a Bellabeat proporcionar a las mujeres conocimientos sobre su propia salud y sus hábitos. Desde su fundación, en 2013, Bellabeat creció a un ritmo vertiginoso y rápidamente se posicionó como empresa de bienestar impulsada por la tecnología para las mujeres.

En 2016, Bellabeat ya había inaugurado oficinas en todo el mundo y lanzado múltiples productos. Los productos Bellabeat pasaron a estar disponibles en línea a través de un creciente número de comerciantes minoristas, además del canal de comercio electrónico propio de Bellabeat en su sitio web. La empresa invirtió en medios publicitarios tradicionales, como radio, cartelería en la vía pública, prensa gráfica y televisión, pero se centra mayormente en el marketing digital. Bellabeat invierte todo el año en Google Search, mantiene activas las páginas de Facebook e Instagram e interactúa de manera constante con los consumidores en Twitter. A su vez, Bellabeat publica anuncios por video en YouTube y avisos publicitarios en la Red de Display de Google para apoyar las campañas en fechas de marketing claves.

Sršen sabe que el análisis de los datos de consumo disponibles de Bellabeat revelaría nuevas oportunidades de crecimiento. Ella le pidió al equipo de análisis computacional de datos de marketing que se concentrara en un producto Bellabeat y analizara los datos de uso de dispositivos inteligentes para conocer cómo las personas están usando sus dispositivos inteligentes. Después, con esta información, le gustaría recibir recomendaciones de alto nivel sobre cómo estas tendencias pueden colaborar en la estrategia de marketing de Bellabeat.

