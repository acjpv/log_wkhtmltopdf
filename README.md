![alt tag](https://raw.githubusercontent.com/felipeunefa/log_wkhtmltopdf/master/static/description/jpv2.png)
![alt tag](https://raw.githubusercontent.com/felipeunefa/log_wkhtmltopdf/master/static/description/jpb.jpg)
![alt tag](https://raw.githubusercontent.com/felipeunefa/log_wkhtmltopdf/master/static/description/bachaco.jpg)
#Log para la libreria Wkhtmltopdf.

Este módulo de Odoo, una vez instalado genera en la descripción del mismo el diseño, código y resultado del subproceso del **último** .pdf generado, adicionalmente guarda en el log de Odoo la misma información y otra extra de **todos** los .pdf generados. Que le será de utilidad para revisar cualquier error de diseño, rendimiento o de proceso con Wkhtmltopdf con Odoo. 

Se recomienda una vez realizado la revisión del test Desintalarlo.

#### Ejemplos:
Una vez instalado el módulo y generado un .pdf en su sistema, este modulo reescribirá la descripción con la siguiente Información del .pdf:

Presentación de la descripción.

![alt tag](https://raw.githubusercontent.com/felipeunefa/log_wkhtmltopdf/master/static/description/ejemplo1.png)
***
Diseño del pdf que el motor de repotes de odoo le entrga a Wkhtmltopdf.

![alt tag](https://raw.githubusercontent.com/felipeunefa/log_wkhtmltopdf/master/static/description/ejemplo2.png)
***
El código html que el motor de reportes de odoo le entrga a Wkhtmltopdf.

![alt tag](https://raw.githubusercontent.com/felipeunefa/log_wkhtmltopdf/master/static/description/ejemplo3.png)
***
Información de la ***base del dominio*** (Esto impacta en el rendimiento, cuando se genera un conjunto de pdf al mismo tiempo) y el proceso de ejecución de  wkhtmltopdf.

![alt tag](https://raw.githubusercontent.com/felipeunefa/log_wkhtmltopdf/master/static/description/ejemplo4.png)
***
Adiciónalmente guarda información más expecifica en odoo.log de ***cada*** .pdf generado.

![alt tag](https://raw.githubusercontent.com/felipeunefa/log_wkhtmltopdf/master/static/description/ejemplo5.png)
![alt tag](https://raw.githubusercontent.com/felipeunefa/log_wkhtmltopdf/master/static/description/ejemplo6.png)
***







